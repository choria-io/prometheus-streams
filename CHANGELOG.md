|Date      |Issue |Description                                                                                              |
|----------|------|---------------------------------------------------------------------------------------------------------|
|2018/12/09|      |Release 1.0.0                                                                                            |
|2018/12/09|30    |Continue to publish own metrics while paused using the circuit breaker                                   |
|2018/12/08|54    |Emit a Choria lifecycle event on startup                                                                 |
|2018/12/08|58    |Use Choria backplane for management and remove unique management tool from this code                     |
|2018/12/07|60    |Update prometheus client code to a release version rather than beta                                      |
|2018/11/28|      |Release 0.2.1                                                                                            |
|2018/10/28|55    |Move to github.com/gofrs/uuid - a better maintained library                                              |
|2018/06/25|      |Release 0.2.0                                                                                            |
|2018/06/25|51    |Handle connection errors better, now requires NATS Streaming Server 0.10.0 or newer                      |
|2018/05/29|49    |Support SSL using the Choria Security subsystem, include enrollment in Puppet CA and manual configuration|
|2018/04/10|      |Release 0.1.0                                                                                            |
|2018/04/10|45    |The publisher name can be configured using the `identity` key in configuration and Puppet                |
|2018/04/06|      |Release 0.0.7                                                                                            |
|2018/04/05|41    |Support labeling metrics with the name of the poller                                                     |
|2018/04/04|      |Release 0.0.6                                                                                            |
|2018/04/04|33    |Do not use SRV records in the management agent                                                           |
|2018/04/04|35    |Log rotation improvements                                                                                |
|2018/04/04|34    |Announce version and config file at startup                                                              |
|2018/02/15|26    |Remove some log noise that should have been debug level                                                  |
|2018/02/15|25    |Simplify stats being kept that can be used to assist when last a host sent data                          |
|2018/02/15|      |Release 0.0.5                                                                                            |
|2018/02/15|21    |Publish the poller name in the seen stat to make more interesting graphs                                 |
|2018/02/15|20    |Use the hostname as target name for the auto generated `prometheus_streams` job                          |
|2018/02/15|19    |Allow `receiver_stream`, `publisher_stream`, `push_gateway` and `management` to not be supplied to puppet|
|2018/02/14|      |Release 0.0.4                                                                                            |
|2018/02/14|17    |Optionally keep stats about own operations                                                               |
|2018/02/13|13    |Treat target names as optional in the Puppet module                                                      |
|2018/02/13|14    |Expose the version as a fact                                                                             |
|2018/02/13|      |Release 0.0.3                                                                                            |
|2018/02/13|11    |Add a Puppet module to manage the poller and receiver                                                    |
|2018/02/13|6     |Export facts in a more meaningful way                                                                    |
|2018/02/12|      |Release 0.0.2                                                                                            |
|2018/02/12|6     |Add a Choria based management agent                                                                      |
|2018/02/12|      |Release 0.0.1                                                                                            |