## deviceQuery for CUDA
-----

### Run (nvidia-docker v2)
```
docker run --rm --runtime=nvidia izone/device-query
```
### Run (nvidia-docker)
```
nvidia-docker run --rm izone/device-query:9.2
```

-----
#### Build
```
docker build -t izone/device-query .
```
```
docker build -t izone/device-query:9.2 ./9.2/
```
