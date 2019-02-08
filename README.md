apollo-sample
===
Portable version of the official apollo-android example, [apollographql/apollo-android/apollo-sample](https://github.com/apollographql/apollo-android/tree/master/apollo-sample).

It is a fork of the official example but huge apollo-android Gradle project.
Instead of compiling all the Apollo stuffs from the scratch, it just uses the releases.

Usage
---
The official example uses Github.com's GraphQL server, so you don't need to care about the server. Just compile, run this Android application, and see how Apollo works.

```sh
echo "sdk.dir=/your/Android/SDK/home" > local.properties
gradle installDebug
```

Caveat
---
Github limits the query rate. See [rate-limit](https://developer.github.com/v4/guides/resource-limitations/#rate-limit).
