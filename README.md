# Prince Server

> Official Docker Image Build Context for [`prince-server`](https://github.com/panosoft/prince-server)

## Usage

Ports:

- `8443` - HTTPS Prince server.

Volumes:

- `host:/credentials:ro`
	- `server.key`
	- `server.crt`


- `host:/usr/local/lib/prince/license:ro`
	- `license.dat`
