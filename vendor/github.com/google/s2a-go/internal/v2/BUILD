load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "internal",
    srcs = ["s2av2.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/google/s2a-go/internal/v2",
    importpath = "github.com/google/s2a-go/internal/v2",
    visibility = ["//vendor/github.com/google/s2a-go:__subpackages__"],
    deps = [
        "//vendor/github.com/google/s2a-go/fallback",
        "//vendor/github.com/google/s2a-go/internal/handshaker/service",
        "//vendor/github.com/google/s2a-go/internal/proto/v2/common_go_proto",
        "//vendor/github.com/google/s2a-go/internal/proto/v2/s2a_go_proto",
        "//vendor/github.com/google/s2a-go/internal/tokenmanager",
        "//vendor/github.com/google/s2a-go/internal/v2/tlsconfigstore",
        "//vendor/github.com/google/s2a-go/retry",
        "//vendor/github.com/google/s2a-go/stream",
        "//vendor/google.golang.org/grpc",
        "//vendor/google.golang.org/grpc/credentials",
        "//vendor/google.golang.org/grpc/grpclog",
        "//vendor/google.golang.org/protobuf/proto",
    ],
)
