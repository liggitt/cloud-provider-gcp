load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "OpenAPIv2.go",
        "OpenAPIv2.pb.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/googleapis/gnostic/openapiv2",
    importpath = "github.com/googleapis/gnostic/openapiv2",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/golang/protobuf/proto:go_default_library",
        "//vendor/github.com/golang/protobuf/ptypes/any:go_default_library",
        "//vendor/github.com/googleapis/gnostic/compiler:go_default_library",
        "//vendor/gopkg.in/yaml.v2:go_default_library",
    ],
)
