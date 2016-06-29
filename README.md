To build:

```docker build -t java8 .```

To test:

```docker run java bash java -version```

To use:

```docker run -v ~/workspace/java-project:/java-project java bash javac /java-project/MyClass.java```

```docker run -v ~/workspace/java-project:/java-project java bash java -cp /java-project MyClass```
