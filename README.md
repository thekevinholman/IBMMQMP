# IBM MQ SCOM Management Pack 3.2.1.4

## [Download Here][Download]

[Download]: https://github.com/thekevinholman/IBMMQMP/releases/download/3.2.1.4/IBM.MQ.mp

IBM MQ SCOM Management Pack

Management Pack to discover and monitor IBM MQ Servers on Windows

https://kevinholman.com/2020/07/20/ibm-websphere-mq-scom-management-pack/

Discovers and monitors:
* MQ Server (Service Running)
* Queue Managers (Status)
* Queues (Status, Queue Depth, Queue Percent Used, IPROCS, OPROCS)
* Listeners (Status, Sessions)
* Channels (Status)

Version History:
- 3.2.1.0 - Original Release
- 3.2.1.1 - Updated displayname properties on classes to match QueueManagerName, QueueName, ChannelName, ListenerName
- 3.2.1.2 - Added Queue Percent Used Monitor.  Optimized Queue Monitoring script to run much faster
- 3.2.1.3 - Fixed bugs in Channel, Listener, and QueueManager status monitors.  First version shipped as sealed MP.
- 3.2.1.4 - Fixed bug in Channel status monitor.  Added Channel Type class property and updated discovery for this property.
