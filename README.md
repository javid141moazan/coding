# Mutation Testing with PIT

This project contains a simple maven project that demonstrates some of the capabilities of the PIT mutation testing system.

Assuming you have Java and Maven installed you can just run:

```
mvn clean install
```

This will build the project, run the tests and the PIT analysis. The PIT results can be found in ./target/pit-reports each PIT run will generate its output in a new time stamped folder. The index.html file within this folder can be opened in a browser to view the results. Each class is named to indicate what it demonstrates and has a brief Javadoc description that adds a bit more detail.


[![<javid141moazan>](https://circleci.com/<GH>/<javid141moazan>/<coding>.svg?style=shield)](<https://app.circleci.com/pipelines/github/javid141moazan/coding/1/workflows/c6463c99-469f-4614-9596-f747c4ff4e6a/jobs/1>)
