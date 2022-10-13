# Network Trigger
Network Trigger (NT) is an application that is designed to listen for specific events that occur on the network and perform an action when detected, such as running an application or shutting down the computer.

While there are various ways that NT accomplishes this, the typical way is by listening for wake on LAN ("magic" wake packets) that have been broadcast on the network. This allows NT to control the device it's running on without having to install a special application on a phone or another computer; simply install a wake on LAN app* or make use of the operating system's wake tool, if it has one. You can then configure NT to listen for that packet and perform an action like, say, run an application.
