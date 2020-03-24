# maven

This was created using [xyz gae generator](https://github.com/luanpotter/xyz-gae-generator).

Welcome to your newly created project! Edit this readme to add useful information.

The following might help you finish your setup:

## Docs

See the [Google App Engine standard environment documentation][ae-docs] for more
detailed instructions.

* [ae-docs](https://cloud.google.com/appengine/docs/java/)
* [Java 8](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
* [Maven](https://maven.apache.org/download.cgi) (at least 3.5)
* [Google Cloud SDK](https://cloud.google.com/sdk/) (aka gcloud)

## Setup

* Download and initialize the [Cloud SDK](https://cloud.google.com/sdk/)

    gcloud init

* Create an App Engine app within the current Google Cloud Project

    gcloud app create

## Running locally

    mvn appengine:run

To use vist: http://localhost:8080/

## Deploying

    mvn appengine:deploy

To use vist:  https://YOUR-PROJECT-ID.appspot.com

## Testing

    mvn verify

As you add / modify the source code (`src/main/java/...`) it's very useful to add [unit testing](https://cloud.google.com/appengine/docs/java/tools/localunittesting) to (`src/main/test/...`).  The following resources are quite useful:

* [Junit4](http://junit.org/junit4/)
* [Mockito](http://mockito.org/)
* [Truth](http://google.github.io/truth/)


## Dependinces
 
  Frontend-v2
* angular version - 8.1.2
* cli version -2.2.0
* npm version - 6.1.0
* node - 10.16.0
 

