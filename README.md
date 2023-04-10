# kafka-connect-mongodb
Kafka Connect for MongoDB


## Sink
 The sink connector is a Kafka Connect connector that reads data from Apache 
 Kafka and writes data to your app, MongoDB for example.

There are two things you have to do:
1) configure kafka connect sink
2) Add sink.<your-app>.properties file

and start standalone connect with that properties file.
