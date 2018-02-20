This repo demonstrates how to load .Net assemblies over the Internet using Powershell using a concept called ".Net over .net".

#### DemoAssemblies/
This folder includes the DLLs used in the PoC.  IronPython is not necessary for ".Net over .net", but rather a powerful example of the flexibility of this technique.

If you want to try out the PoC, you need to host the DemoAssemblies on a web server somewhere.

You can set up a simple web server by using 'python -m SimpleHTTPServer 8888' and pointing the code to http://localhost:8888/

#### PoC/dotnetoverdotnet.poc.ps1
This code pulls the .Net assemblies over the net, just make sure you update the URL to point at the URL of the server you set up above.

#### More info
#TODO