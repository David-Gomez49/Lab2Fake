[![CI/CD Pipeline](https://github.com/David-Gomez49/Lab2Fake/actions/workflows/build.yml/badge.svg)](https://github.com/David-Gomez49/Lab2Fake/actions/workflows/build.yml)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=David-Gomez49_Lab2Fake&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=David-Gomez49_Lab2Fake)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=David-Gomez49_Lab2Fake&metric=bugs)](https://sonarcloud.io/summary/new_code?id=David-Gomez49_Lab2Fake)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=David-Gomez49_Lab2Fake&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=David-Gomez49_Lab2Fake)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=David-Gomez49_Lab2Fake&metric=coverage)](https://sonarcloud.io/summary/new_code?id=David-Gomez49_Lab2Fake)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=David-Gomez49_Lab2Fake&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=David-Gomez49_Lab2Fake)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=David-Gomez49_Lab2Fake&metric=reliability_rating)](https://sonarcloud.io/summary/new_code?id=David-Gomez49_Lab2Fake)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=David-Gomez49_Lab2Fake&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=David-Gomez49_Lab2Fake)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=David-Gomez49_Lab2Fake&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=David-Gomez49_Lab2Fake)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=David-Gomez49_Lab2Fake&metric=sqale_index)](https://sonarcloud.io/summary/new_code?id=David-Gomez49_Lab2Fake)


[![Coverage Status](https://coveralls.io/repos/github/David-Gomez49/Lab2Fake/badge.svg?branch=0e37ff4768563cd4c27e882ebd71a1dc2386c65f)](https://coveralls.io/github/David-Gomez49/Lab2Fake?branch=0e37ff4768563cd4c27e882ebd71a1dc2386c65f)

* Implementation of a Simple App with the next operations:

* Get random nations
* Get random currencies
* Get random Aircraft
* Get application version
* health check

Including integration with GitHub Actions, Sonarqube (SonarCloud), Coveralls and Snyk

### Folders Structure

In the folder `src` is located the main code of the app

In the folder `test` is located the unit tests

### How to install it

Execute:

```shell
$ mvnw spring-boot:run
```
to download the node dependencies

### How to test it

Execute:

```shell
$ mvnw clean install
```

### How to get coverage test

Execute:

```shell
$ mvwn -B package -DskipTests --file pom.xml
```
