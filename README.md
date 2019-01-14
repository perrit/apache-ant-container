# Container for Apache Ant

## Description

This is a container based off `openjdk:11-jdk` and adds the `ant` package from the APT repositories. It is to avoid having to install packages every time during a CI/CD pipeline that natively uses containers for each job. This speeds up the process slightly and it is more efficient to "solve" this problem once in a central location.

## Examples

### Docker Run

```bash
docker run --rm -ti perrit/apache-ant ant --help
docker run --rm -ti perrit/apache-ant ant -version
```

## Links

* https://ant.apache.org/
* https://hub.docker.com/_/openjdk/
* https://github.com/perrit/apache-ant-container
* https://gitlab.com/perrit/apache-ant-container
* https://hub.docker.com/r/perrit/apache-ant/
