package(default_visibility = ["//visibility:public"])

load("//tools:build_rules/go.bzl", "go_library")

go_library(
    name = "email",
    srcs = [
        "client.go",
        "constants.go",
        "email.pb.go",
    ],
    deps = [
        "@go_gogo_protobuf//:gogoproto",
        "@go_gogo_protobuf//:proto",
        "@go_grpc//:grpc",
        "@go_grpc//:codes",
        "@go_grpc//:status",
        "@go_protobuf//:proto",
        "@go_protobuf//:ptypes/empty",
        "@go_x_net//:context",
    ],
)
