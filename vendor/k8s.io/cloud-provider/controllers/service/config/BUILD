load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "config",
    srcs = [
        "doc.go",
        "types.go",
        "zz_generated.deepcopy.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/cloud-provider/controllers/service/config",
    importpath = "k8s.io/cloud-provider/controllers/service/config",
    visibility = ["//visibility:public"],
)
