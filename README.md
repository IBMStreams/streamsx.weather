# streamsx.weather

Toolkit for accessing data from the [Insights for Weather Bluemix Service](https://console.ng.bluemix.net/catalog/services/insights-for-weather).  

To learn more about how this toolkit can be used:

* [Apache Quarks, Watson, and Streaming Analytics: Saving the world, one smart sprinkler at a time](https://developer.ibm.com/bluemix/2016/06/01/better-analytics-with-apache-quarks/)

To watch this toolkit in action:

* [Water Conservation Application Demo](https://www.youtube.com/watch?v=Rvc1CqNJkOA)

To learn more about Streams:

* [IBM Streams on Github](http://ibmstreams.github.io)
* [Introduction to Streams Quick Start Edition](http://ibmstreams.github.io/streamsx.documentation/docs/4.1/qse-intro/)
* [Streams Getting Started Guide](http://ibmstreams.github.io/streamsx.documentation/docs/4.1/qse-getting-started/)
* [StreamsDev](https://developer.ibm.com/streamsdev/)


# Building toolkit for development

To build this toolkit, you need to:

1.  Install IBM Streams 4.1 and up
2.  Set MAVEN environment variable:  `export M2_HOME=<maven install location>`
3.  cd com.ibm.streamsx.weather
4.  Download required build dependencies:  `ant maven-deps`
5.  Import project into Streams Studio to build

# Building toolkit
To build this toolkit, you need to:

1.  Install IBM Streams 4.1 and up
2.  Set MAVEN environment variable:  `export M2_HOME=<maven install location>`
3.  cd com.ibm.streamsx.weather
4.  To build toolkit:  `ant`
