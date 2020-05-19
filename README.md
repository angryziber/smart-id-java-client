
[![Build Status](https://travis-ci.org/SK-EID/smart-id-java-client.svg?branch=master)](https://travis-ci.org/SK-EID/smart-id-java-client)
[![Coverage Status](https://img.shields.io/codecov/c/github/SK-EID/smart-id-java-client.svg)](https://codecov.io/github/SK-EID/smart-id-java-client/)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/ee.sk.smartid/smart-id-java-client/badge.svg)](https://maven-badges.herokuapp.com/maven-central/ee.sk.smartid/smart-id-java-client)
[![License: MIT](https://img.shields.io/github/license/mashape/apistatus.svg)](https://opensource.org/licenses/MIT)

# Smart-ID Java client

## Introduction

The Smart-ID Java client can be used for easy integration of the [Smart-ID](https://www.smart-id.com) solution to information systems or e-services.

## Features

* Simple interface for user authentication
* Simple interface for digital signature services

## Requirements

* Java 1.7
* Internet access to Smart-ID server environment

## How to use it

Take a look at the [examples](https://github.com/SK-EID/smart-id-java-client/wiki/Examples-of-using-it) 

To log requests going to Smart-ID API set ee.sk.smartid.rest.LoggingFilter to log at trace level.
For applications on Spring Boot this can be done by adding following line to application.yml:
```
logging.level.ee.sk.smartid.rest.LoggingFilter: trace
 ```

## Getting the library

### Maven
You can use the library as a Maven dependency from the [Maven Central](https://search.maven.org/search?q=a:smart-id-java-client).

```xml
<dependency>
    <groupId>ee.sk.smartid</groupId>
    <artifactId>smart-id-java-client</artifactId>
    <version>INSERT_VERSION_HERE</version>
</dependency>
```

### Gradle

`implementation 'ee.sk.smartid:smart-id-java-client:INSERT_VERSION_HERE'`

### Changes

* Listed in [changelog](CHANGELOG.md)

