load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["http.go"],
    importmap = "io_k8s_cloud_provider_gcp/vendor/github.com/prometheus/client_golang/prometheus/promhttp",
    importpath = "github.com/prometheus/client_golang/prometheus/promhttp",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/prometheus/client_golang/prometheus:go_default_library",
        "//vendor/github.com/prometheus/common/expfmt:go_default_library",
    ],
)
