Run order:
1. fetch_geojsons
2. fetch_trip_ids
3. fetch_services
4. generate_gtfs

The first three steps can be done semi-simultaniously.
You can start the next one while the previous is still processing, to make it faster.