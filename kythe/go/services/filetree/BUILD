load("//tools:build_rules/go.bzl", "go_package")

package(default_visibility = ["//kythe:default_visibility"])

go_package(
    deps = [
        "//kythe/go/services/graphstore",
        "//kythe/go/services/web",
        "//kythe/go/util/kytheuri",
        "//kythe/go/util/schema",
        "//kythe/proto:filetree_proto_go",
        "//kythe/proto:storage_proto_go",
        "@go_x_net//:context",
    ],
)
