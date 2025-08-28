# Changelog

## From Yesterday's Repo
- Preserved services and calculation logic (uses DataSetClean.csv fields correctly).

## From Today's Progress
- Added UI served by Nginx (port 3000).
- Added Gateway with YARP + CORS (port 5000).
- Updated Orchestrator to return JSON and add `/result/{runId}` (port 5001 private).
- RabbitMQ integration with container networking.
- Dockerfiles and docker-compose with correct ports.

## Dataset
- `DataSetClean.csv` included in `/data` and mounted into containers at `/app/data/DataSetClean.csv`.
