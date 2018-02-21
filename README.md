apollo-sample
===
Portable Apollo GraphQL Android example.

It is a fork of [apollographql/apollo-android/apollo-sample](https://github.com/apollographql/apollo-android/tree/master/apollo-sample),
but fully decoupled from the huge Gradle project, apollo-android.
Instead of building all the Apollo stuffs, it just downloads them.

Usage
---
It uses Github.com's GraphQL server, so all you need to do is just compile and run this Android application.

```sh
echo "sdk.dir=/your/Android/SDK/home" > local.properties
gradle installDebug
```
