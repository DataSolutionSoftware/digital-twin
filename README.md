# Digital Twin

Innovation and Vision

Manually Create the Table: Go to your Supabase project, navigate to SQL Editor, and run the following SQL to create the readings table:

CREATE TABLE readings (
  id SERIAL PRIMARY KEY,
  meter_id VARCHAR(255),
  reading FLOAT,
  timestamp TIMESTAMP
);
First open two terminals. Then CD into frontend and backend First you need to start the service by running : 

1. node server2.js  for Backend 
2. Then start the react app by running :

3. Repo : https://github.com/kukuu/digital-twin

## Production 

V1 https://digital-twin-neon.vercel.app/

V2 https://github.com/kukuu/digital-twin-v2

## AZURE Digital Twin 

https://github.com/Azure-Samples/digital-twins-explorer/tree/main/client
