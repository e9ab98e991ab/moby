# Build Docker with Gradle 

This is an experimental project for building docker by gradle. It's designed to verify [`Gogradle`](https://github.com/gogradle/gogradle)'s capability, thus there are some notices:

- This is not a production-ready project.
- To satisfy `Gogradle`, a JDK 8+ should be pre-installed on your machine.
- `$GOPATH` is not necessary.
- `vendor` and `vendor.conf` are removed. Personally, I don't like vendor.
- Most logic code of `Makefile` has been rewrited in `build.gradle`. My goal is to replace `make` with `gradle`. You can run `./gradlew xxx` instead of `make xxx`. For example, run `./gradlew binary` to replace `make binary`.

