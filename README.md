##About wifi-toggle
The purpose of wifi-toggle is to help you automatically reconnect to your Wi-Fi should your connection drop. One of the simplest and most effective fixes is to toggle the power state of the Wi-Fi adapter and allow it to reconnect.
For those experiencing Wi-Fi connection issues since upgrading to Mac OS Yosemite, wifi-toggle aims to provide a seamless workaround until Apple resolves the issue.

##How to use
The application may be downloaded from GitHub by cloning or downloading it as a zip file. Once downloaded, you may place the app in your Applications directory for convenience.

To run the app, double-click the 'wifi-toggle.app' bundle or search for 'wifi-toggle' in Spotlight or Alfred.

##Configure Launch on Login
To setup wifi-toggle to automatically launch when you login:

1.  Open System Preferences

2.  Select Users & Groups

3.  Select your account

4.  Select Login Items

5.  Click the '+' icon to add an item to the list, and select 'wifi-toggle.app' from the directory in which you stored it.


##NOTE
While recent Macs have the wireless interface set to en0, it is possible yours may be different.

If your wireless interface is set to something other than en0, you may run the following command from the directory in which the app is located.

`./swapinterface en#`

where # is the number corresponding to your wireless interface.
