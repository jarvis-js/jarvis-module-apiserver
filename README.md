# Jarvis API Server module

Enables a RESTful api server (and optional web socket support) for Jarvis

## Configuration

An example configuration can be seen below.

	apiserver: {
		port: 8000,
		socket: true,
		debug: false
	}

### Port

The server port to listen for connections on

### Socket

Enable socket.io support

### Debug

Enable extra logging whilst in development
