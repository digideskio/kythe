load("//tools:build_rules/go.bzl", "go_package")

package(default_visibility = ["//kythe:default_visibility"])

go_package(
    test_deps = ["//kythe/go/test/testutil"],
    deps = [
        "//kythe/go/util/disksort",
        "//kythe/proto:internal_proto_go",
        "@go_protobuf//:proto",
        "@go_x_net//:context",
    ],
)
