# Ember Data Spring

Example using Ember Data to access a Spring App using JSON REST API. This project illustrates the many hoops you have to jump through to get this working, even with as simple a domain model as this.

## Requirements

* JDK 8 (project may also build with JDK 7, but not tested)
* Recent Node.js with NPM
* Ember CLI 0.1.19+

## Build server

```
./gradlew
```

### Run server

```
./gradlew bootRun
```

Open [http://localhost:8080](http://localhost:8080) to verify.

## Build and run Ember UI

```
cd ui
npm install
bower install
ember serve
```

Open [http://localhost:4200](http://localhost:4200)
