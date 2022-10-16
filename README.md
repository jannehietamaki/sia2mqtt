# sia2mqtt

Posts incoming SIA DC-09 events to MQTT queue.

## Standard compatibility

Currently the option to configure this server as UDP is not implemented, it only receives non-encrypted TCP connections.

This service act as Central Station Receivers (CSR). Encryption support is mandatory for CSRs. So, **this is a non-standard project** at this time.

Based on [SIABroker](https://github.com/nhereveri/SIAbroker)

