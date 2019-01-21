# elkstack in docker
- is a fork from https://hub.docker.com/r/sebp/elk/

# build and bootup:
- Build with:
- docker build -t mpsoftdenmark/docker-elk .

- Run with:
- docker run -p 5601:5601 -p 9200:9200 -p 5044:5044 -it --name elk mpsoftdenmark/docker-elk

