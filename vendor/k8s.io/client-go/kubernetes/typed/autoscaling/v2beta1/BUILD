load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "v2beta1",
    srcs = [
        "autoscaling_client.go",
        "doc.go",
        "generated_expansion.go",
        "horizontalpodautoscaler.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/kubernetes/typed/autoscaling/v2beta1",
    importpath = "k8s.io/client-go/kubernetes/typed/autoscaling/v2beta1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/autoscaling/v2beta1",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/types",
        "//vendor/k8s.io/apimachinery/pkg/watch",
        "//vendor/k8s.io/client-go/applyconfigurations/autoscaling/v2beta1",
        "//vendor/k8s.io/client-go/gentype",
        "//vendor/k8s.io/client-go/kubernetes/scheme",
        "//vendor/k8s.io/client-go/rest",
    ],
)
