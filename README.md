Dashboard for MMDVM using MQTT protocol

This project uses Jonathan G4KLX's latest implementations of the MMDVM suite.

Currently, the entire logging system is managed via the MQTT protocol, so a "broker" like Mosquitto must be installed to route the log streams.

Topic must be in the format mmdvm/[nodename] for MMDVMHost.ini

For [MODE]Gateway.ini, topic format must be: [mode]-gateway/[nodename]

You can find an example here: http://mqtt.freedmr.it:7000

developed by FreeDMR IT Dev Team.

