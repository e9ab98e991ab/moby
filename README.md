# Build Docker with Gradle 

This is an experimental project for building docker by gradle, whose goal is to verify [`Gogradle`](https://github.com/gogradle/gogradle)'s capability, thus there are some notices:

- This is not a production-ready project.
- To satisfy `Gogradle`, a JDK 8+ should be pre-installed.
- `$GOPATH` is not necessary on your machine.
- Remove `vendor` and `vendor.conf`. Personally, I don't like vendor.
- Rewrite most logic code of `Makefile` into `build.gradle`. My goal is to replace `make` with `gradle`. You can run `./gradlew xxx` instead of `make xxx`. For example, run `./gradlew binary` to replace `make binary`.

