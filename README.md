# Graph-Demo

Summary
This document presents a step by step guide to getting a basic graph web demo up and running 
with DataStax (DSE)/Graph. The demo is built around the WebStorm IDE,  Node.js and vis.js  graph visualization. 
Benefits
"	The ability to build a demo that is highly customized
"	Examples of how to process graph output
"	Example of DataStax's Node.js driver 
Considerations
"	This application will not process all graph queries by default. DSE Graph's objects come back in different shapes and this application's parser will most likely need to be updated to accommodate.
"	This guide is not a substitute for knowing how to configure DSE and DataStax Studio.
Requirements
This demo was built on a Mac and uses the following components:
"	DataStax 5.x with graph enabled
"	DataStax Studio 2.x
"	DataStax Enterprise Node.js Driver Graph Extension 
"	Jet Brains WebStorm Version used: 2017.3.4
"	Any web browser. Chrome preferred. Node.js uses the Chrome JavaScript engine. 
"	vis.js graph library v4.21.0.
