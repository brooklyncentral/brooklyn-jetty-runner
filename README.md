# Jetty Runner

[Jetty Runner](http://www.eclipse.org/jetty/documentation/current/runner.html) is a simple, lightweight method of running a Java webapp. This repository contains the Apache Brooklyn
YAML blueprint for deployment and in-life management of a Java webapp with Jetty Runner.

## Basic Config

| Config Key                    | Default         | Description                                           |
|-------------------------------|-----------------|-------------------------------------------------------|
| war.url                       |                 | The URL of the war to download and run                | 
| jetty.port                    | 8080            | The port to run Jetty on                              | 
| jetty.version                 | 8.1.9.v20130131 | The version of Jetty to use or LATEST for the latest  | 
| additional.java.params        |                 | Additional parameters to pass to java*                | 

\* Additional java params are passed in to the command line and can be options such as `-DsomeVal=whatever`.
