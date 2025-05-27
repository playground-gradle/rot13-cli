# `rot13-cli`
> jung lbh jbhyq rkcrpg, cebonoyl
[yrnea zber](https://en.wikipedia.org/wiki/ROT13).

## Usage

```shell
# Prints hello world :)
./gradlew run --args="uryyb jbeyq :)"
```

## Helpful commands

### Get the dep graph via Gradle

```shell
./gradlew :app:dependencies --configuration runtimeClasspath
```

### Test the dep graph for critical severity security issues

```shell
snyk test --all-projects --severity-threshold=critical
```
