# SimpleHTTPServer.ps1
Powershell - Simple HTTP Server

This gives you a simple HTTP server to use, similar to python's HTTP server module.

Serve up an HTTP server quickly with Powershell, so that you can transfer files to a host.

I mostly took the code from https://github.com/tobor88/PowerShell-Red-Team/blob/master/Start-SimpleHTTPServer.ps1 and modified it to suite my needs.

```powershell
. .\SimpleHTTPServer.ps1
SimpleHTTPServer -ListenHost 127.0.0.1 -Port 8000 -DirectoryListing $False
```