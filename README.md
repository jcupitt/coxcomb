# Coxcomb charts 

This is a copy of http://bl.ocks.org/kgryte/5926740 but updated to d3-5.0 from
January 2018.

# Local development

Browsers enforce strict security permissions to prevent you from reading files
out of the local file system. To develop locally, you must run a local web
server rather than using `file://...`. 

Node’s http-server is recommended. To install:

	npm install -g http-server

To run:

	http-server & 

This will start the server on `http://localhost:8080` from the current working
directory.

