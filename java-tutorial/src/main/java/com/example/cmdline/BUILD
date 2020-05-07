load("@rules_java//java:defs.bzl", "java_binary")
load("@io_bazel_rules_kotlin//kotlin:kotlin.bzl", "kt_jvm_library")

java_library(
    name = "runner",
    srcs = ["Runner.java"],
    deps = [":greeter"],
)


kt_jvm_library(
    name = "kt_runner",
    srcs = ["KotlinRunner.kt"],
    deps = [":greeter"],
)

java_library(
    name = "greeter",
    srcs = ["Greeting.java"],
)
