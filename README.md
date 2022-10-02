# open-air-rotterdam 🛠

## Purpose

I am building a pipeline of telemetry events to a front-end component,
and I'm aiming to use the telemetry provided by the well-known [OpenSky REST API](https://openskynetwork.github.io/opensky-api/) and [LUCHTMEETNET 2020 OPENAPI](https://api-docs.luchtmeetnet.nl/). 
To keep the data moving, I will implement additional mechanisms that convert the telemetry events to data structures, and load the data into a streaming platform, ideally in real-time.
This repository will be a home for a Spring Reactive Web project with a Reactive Pulsar Adapter:

* https://github.com/lhotari/reactive-pulsar-in-5-minutes;
* https://github.com/datastax/reactive-pulsar
