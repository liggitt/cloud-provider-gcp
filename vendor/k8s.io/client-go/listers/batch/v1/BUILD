load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "batch",
    srcs = [
        "cronjob.go",
        "expansion_generated.go",
        "job.go",
        "job_expansion.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/listers/batch/v1",
    importpath = "k8s.io/client-go/listers/batch/v1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/batch/v1:batch",
        "//vendor/k8s.io/api/core/v1:core",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/labels",
        "//vendor/k8s.io/client-go/listers",
        "//vendor/k8s.io/client-go/tools/cache",
    ],
)
