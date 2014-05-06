## appengine-googleanalytics-java

Integrating App Engine with Google Analytics

## Project setup, installation, and configuration

- Register for [Google Analytics](http://www.google.com/analytics/), create
an application, and get a tracking id.
- Use that tracking id when you are Instantiating a `GoogleAnalyticsTracking` object.

## Running the demo

Requires [Apache Maven](http://maven.apache.org) 3.0 or greater, and JDK 7+ in order to run.

- Modify the *tracking.jsp* to use your own tracking id if you wish to test
tracking events to your own account. 

To build, run

    mvn package

Building will run the tests, but to explicitly run tests you can use the test target

    mvn test

To start the app, use the [App Engine Maven Plugin](http://code.google.com/p/appengine-maven-plugin/) that is already included in this demo.  Just run the command.

    mvn appengine:devserver

For further information, consult the [Java App Engine](https://developers.google.com/appengine/docs/java/overview) documentation.

To see all the available goals for the App Engine plugin, run

    mvn help:describe -Dplugin=appengine

## Contributing changes

* See [CONTRIB.md](CONTRIB.md)

## Licensing

* See [LICENSE](LICENSE)
