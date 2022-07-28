# power-query-m
PowerBI Power Query scripts in M language

1. rest-api-paginated-data-with-await
- REST HTTP API data obtention
- Sleep times for sequential requests not to overload the server (three different approaches: two Value.WaitFor() variations and a Function.InvokeAfter() one)
- Auto table transformation and population with the received data
