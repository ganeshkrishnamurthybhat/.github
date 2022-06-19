Desktop-CGI is a desktop executable app that can be created from any CGI files or CGI web apps that can be served from an file, an embedded web server using proxy, or an remote proxy web server. It supports embedding and managing embeddable databases and executables. It supports all major Operating systems supported by electron like Windows, Linux, and MacOS supported by Electron.


`[Funding Invited]`


![Desktop CGI](https://github.com/desktop-cgi/desktop-cgi/blob/master/desktop-cgi.jpeg)


# Highlights


Desktop-CGI can serve any CGI files, OR CGI / Scripted / Interpreted languages like PHP, Ruby, Python, Perl, JSP, ASPX, Other Interpreted Languages through embedded webservers, OR any remote proxy (any protocol / webserver) apps 

Desktop-CGI runs an Electron - Node - Express - cgijs based application under the hood and supports major Operating systems like Windows, Linux, Mac or any operating systems supported by Electron.


##### Electron based Desktop application that runs CGI Server

* `cgijs` is Nodejs framework independent / agnostic for serving CGI or interpreted scripting apps via files, or server based web apps via proxies
    - Express Recommended and used for demo
* Run any script files that supports CGI based file script serving - using `cgijs file` module
* Run any host that serves a web app - using `cgijs proxy` module
    - In App / Local / Remote proxy support
* Allows
    - running multiple interpreters in one app
    - running multiple proxies (currently http, websockets, tcp, udp. grpc planned) in one app
    - multiple embedded servers in one app
* Allows embedding servers like httpd, nginx, etc to serve web applications - using `cgijs process` module
* Allows embedding database servers (in development) - using `cgijs process` module

The script can proxy to any File, most embeddable web servers, and/ or Proxy-able local / remote servers; even IIS Server (Allows Proxy)


##### Package Dependencies:

* Library dependencies:
    - Nodejs: (> 8.x)

* Application Dependencies:
    - cgi-js: (>=1.0.0)
    - electron": (>=18.1.0)
