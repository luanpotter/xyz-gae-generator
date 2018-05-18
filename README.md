# xyz-gae-generator

A maven generator for quickly bootstraping a GAE project using the [Spark](http://sparkjava.com) framework.

Are you looking for [xyz-generator](https://github.com/luanpotter/xyz-generator)? If you'd like to create a simple Java project, check it out.

For interactive mode, just run:

```java
    mvn archetype:generate -DarchetypeGroupId=xyz.luan.generator -DarchetypeArtifactId=xyz-gae-generator -DarchetypeVersion=0.2.0
```

And fill the information.

If you want batch mode, use this instead, but fill in the gaps:

```java
    mvn archetype:generate -DarchetypeGroupId=xyz.luan.generator -DarchetypeArtifactId=xyz-gae-generator -DarchetypeVersion=0.2.0 -DgroupId=<your.group.id> -DartifactId=<your-atifact-id> -Dversion=<your.version> -DinteractiveMode=false
```

## What does it do?

It creates a base project for Google App Engine (GAE) standard using Java 8 and Maven; it follows [this](https://cloud.google.com/appengine/docs/standard/java/quickstart) guide but does the hard work for you.

It also adds Spark and a sample api route, sample static files, sample integration test.
