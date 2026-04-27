# ProDataSets-OpenEdge

# ProDataSets Project
## Progress OpenEdge 12.2

## Description
This project demonstrates ProDataSet usage including:
- Dataset definition and population
- Client/Server dataset passing via PASOE
- Dataset updates with change tracking
- Dataset events (AFTER-FILL, ROW-UPDATE)
- Batch data retrieval
- Error handling with datasets
- JSON serialization

## Project Structure
- Client/  → Client side ABL procedures
- Server/  → Server side ABL procedures
- Shared/  → Shared include files
- Examples/→ Example programs

## Requirements
- Progress OpenEdge 12.2
- Sports2020 database
- PAS for OpenEdge instance

## Setup
1. Start sports2020 database:
   proserve sports2020 -H localhost -S 50300

2. Start PASOE instance:
   pasman create -j 50309 -p 50310
   ProDataSets-Instance

3. Update appconfig.i with your settings

4. Import projects into PDSOE

5. Build all projects

## Database
Sports2020 database required.
Connection: localhost port 50300
