# Python3 code verifier


## Requirements

- [Docker](https://docs.docker.com/installation/) (or boot2docker on OS X and windows);
- [gcloud](https://cloud.google.com/sdk/#Quick_Start);
- bash and make (you will need to install [cygwin](http://cygwin.com/) on windows).

Note:
	
	On Linux, you might have to run the commands running sudo.


## Building the docker images

```
make images
```


## Test

The tests are run with docker.

```
make test
```


## Pushing image

You should be part of the 
[Singpath organization](https://registry.hub.docker.com/repos/singpath/) 
to publish the code verifier on docker hub.

```
make push-images
```