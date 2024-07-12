# Bazel Emscripten toolchain

This is a fork of the Bazel support from the Emscripten SDK with the following goals.
- Modern Bzlmod approach (no support for WORKSPACE)
- Sane defaults that align with running emcc etc. on the command line
- Cross compilation support for all build systems supported by `rules_foreign_cc`.
- Semantic versioning independent of the Emscripten compiler
