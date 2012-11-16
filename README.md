iget_cached
===========

Wrapper script for iRODS iget that provides local caching of files to enhance data locality

11/16/2012 - Version 0.1
	Basic functionality in place for use in Agave apps
	Known defects
	- No sanity checking on parameters
	- No sanity checking on URL. Hard requirement for iplant/home
	- No support for target filename
	- Needs support to passively clean up old 'inflight' files 
	  at end of transfer process

