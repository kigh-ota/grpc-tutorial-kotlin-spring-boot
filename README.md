# grpc-tutorial-kotlin-spring-boot

Do https://github.com/ymmt2005/grpc-tutorial using Kotlin and Spring Boot.

- Generating codes
  - `./gradlew generateProto` -> under `build/generated/source/proto/main/`:
    - messages in `java/`
    - RPCs in `grpc/` and `grpckt/`
- Implementation
  - TODO: extend `ComputeGrpcKt.ComputeCoroutineImplBase`
    - (cf. extend `ComputeGrpc.ComputeImplBase` for Java)
