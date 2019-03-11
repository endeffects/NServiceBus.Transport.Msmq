# NServiceBus.Transport.Msmq for .net Core
This is an attempt to get the Msmq Transport running on .net Core.

# Current state
- The Installer is disabled because all advanced features such as code access security, execute permissions and Active Directory integration is not supported. So you need to create the queues manually.
- You can read and write to the queues which works with the InMemoryPersistence. 
- The MsmqPersistence raises an invalid version exception.

# Original Packages
MSMQ transport for NServiceBus
https://github.com/Particular/NServiceBus.Transport.Msmq

Experimental port of System.Messaging (for .NET Core)
https://github.com/krazure/Experimental.System.Messaging
