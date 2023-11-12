load("@rules_java//java:defs.bzl", "java_binary")

package(default_visibility = ["//visibility:public"])

java_binary(
    name = "ProjectRunner",
    srcs = glob(["src/main/java/com/example/*.java"]),
    deps = [":Greeting"]
)

java_binary(
    name = "Greeting",
    srcs = glob(["src/main/java/com/example/Greeting.java"])
)
