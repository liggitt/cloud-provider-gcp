load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "consistencydetector",
    srcs = [
        "data_consistency_detector.go",
        "list_data_consistency_detector.go",
        "watch_list_data_consistency_detector.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/util/consistencydetector",
    importpath = "k8s.io/client-go/util/consistencydetector",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/google/go-cmp/cmp",
        "//vendor/k8s.io/apimachinery/pkg/api/meta",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/runtime",
        "//vendor/k8s.io/apimachinery/pkg/util/wait",
        "//vendor/k8s.io/klog/v2:klog",
    ],
)
