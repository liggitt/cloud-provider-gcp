load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "doc.go",
        "types.go",
        "zz_generated.deepcopy.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/kubernetes/pkg/controller/garbagecollector/config",
    importpath = "k8s.io/kubernetes/pkg/controller/garbagecollector/config",
    visibility = ["//visibility:public"],
)
