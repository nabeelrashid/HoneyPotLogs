#Saving honeypots logs with Elasticsearch

This project will save the honeypot logs into elasticsearch database using elastic search v5.0

input sample:

{
"id":124,
"dateTime": " 2018-feb-07",
"srcPort": 38467,
"service": "http",
"dstPort": 80,
"protocol": "tcp",
"appLayerProtocol": "HTTP/1.1",
"severityScore": 1,
"category": "DDos Attack",
"origin": {
"ip": "95.108.189.84",
"country": "United States",
"countryCode": "US",
"internal": false,
"geoPoint": {
"lat": 55.75,
"lon": 37.6166
}
},
"destination": {
"sensorName": "sensor04",
"ip": "111.68.99.39",
"country": "Pakistan",
"city": "Islamabad",
"placement": "COMSATS",
"geoPoint": {
"lat": 33.1479,
"lon": 72.55
}
}}
