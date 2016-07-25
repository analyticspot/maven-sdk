This is a git repository that functions as a Maven repo. If you add:

```
repositories {
    maven { url "https://raw.github.com/analyticspot/maven-sdk" }
}
```

to a gradle project you'll be able to then include the artifacts here just like any other maven artifacts.
