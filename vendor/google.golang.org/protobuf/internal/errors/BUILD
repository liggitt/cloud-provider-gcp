load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "errors",
    srcs = ["errors.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/protobuf/internal/errors",
    importpath = "google.golang.org/protobuf/internal/errors",
    visibility = ["//vendor/google.golang.org/protobuf:__subpackages__"],
    deps = ["//vendor/google.golang.org/protobuf/internal/detrand"],
)
