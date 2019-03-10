# Experimental NServiceBus.Transport.Msmq for .net Core
This is an attempt to get the Msmq Transport running on .net Core.

# Current state
- The Installer is disabled because it is not supported. You need to create the queues manually.
- You can read and write to the queues, but the message format needs to be fixed.

# Original Packages
MSMQ transport for NServiceBus
https://github.com/Particular/NServiceBus.Transport.Msmq

Experimental port of System.Messaging (for .NET Core)
https://github.com/krazure/Experimental.System.Messaging
