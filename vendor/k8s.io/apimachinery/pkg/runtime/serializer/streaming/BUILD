load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "streaming",
    srcs = ["streaming.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/apimachinery/pkg/runtime/serializer/streaming",
    importpath = "k8s.io/apimachinery/pkg/runtime/serializer/streaming",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/apimachinery/pkg/runtime",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema",
    ],
)
