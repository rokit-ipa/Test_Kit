# Test_Kit
1. Setup InfluxDB. You need a token, organisation and bucket. Adapt the files read_database and write_database with your token,organisation and bucket. 
2. Start FastAPI with uvicorn 
```FastAPI.main:app --reload 
```
3. Before starting FastAPI, be sure to write something to the database, empty database will throw an error :) 
