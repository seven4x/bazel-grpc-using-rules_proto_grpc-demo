load("@rules_proto//proto:defs.bzl", "proto_library")


proto_library(
    name = "thing_proto",
    srcs = ["thing.proto"],
    visibility = ["//visibility:public"],
    deps = ["@com_google_protobuf//:any_proto"],
)

proto_library(
    name = "greeter_grpc",
    srcs = ["greeter.proto"],
    visibility = ["//visibility:public"],
    deps = ["@com_google_protobuf//:any_proto",":thing_proto"],
)