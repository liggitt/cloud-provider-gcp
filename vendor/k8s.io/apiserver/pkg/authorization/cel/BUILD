load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "cel",
    srcs = [
        "compile.go",
        "interface.go",
        "matcher.go",
        "metrics.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/apiserver/pkg/authorization/cel",
    importpath = "k8s.io/apiserver/pkg/authorization/cel",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/google/cel-go/cel",
        "//vendor/github.com/google/cel-go/common/ast",
        "//vendor/github.com/google/cel-go/common/operators",
        "//vendor/github.com/google/cel-go/common/types/ref",
        "//vendor/k8s.io/api/authorization/v1:authorization",
        "//vendor/k8s.io/apimachinery/pkg/util/errors",
        "//vendor/k8s.io/apimachinery/pkg/util/version",
        "//vendor/k8s.io/apiserver/pkg/cel",
        "//vendor/k8s.io/apiserver/pkg/cel/environment",
        "//vendor/k8s.io/apiserver/pkg/features",
        "//vendor/k8s.io/apiserver/pkg/util/feature",
        "//vendor/k8s.io/component-base/metrics",
        "//vendor/k8s.io/component-base/metrics/legacyregistry",
    ],
)
