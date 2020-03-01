# ASP.NET-Core-SignalR-Pluralsight
Demo implementation of SignalR as done in Pluralsight course


wiredbrain.js -> Client JS code
Hubs - Signalr Hub server side

In Startup.cs:

To use Azure SignalR: 

Under ConfigureServices:<br><br><code>
services.AddSignalR().AddAzureSignalR("<Azure SignalR Service key>")</code>

Under Configure:

<code>app.UseFileServer(); //app.UseStaticFiles for localhost SignalR </code>

Use Azure SignalR with Classic mode for running this application
