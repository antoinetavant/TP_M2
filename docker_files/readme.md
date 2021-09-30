# docker container for the TP M2PPF

Build it :

```
docker build --network=host  -t tpm2ppf .
```

with :
* `--network=host` for `pip install` to work over the internet
* `-t tpm2ppf` the name of the image, must be lowercase

tag it :

```
docker tag tpm2ppf:latest antoinelpp/tpm2ppf:latest
```

Push it :

``` 
docker image push antoinelpp/tpm2ppf:latest
```
