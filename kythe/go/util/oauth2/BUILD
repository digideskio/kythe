load("//tools:build_rules/go.bzl", "go_package")

package(default_visibility = ["//kythe:default_visibility"])

go_package(
    deps = [
        "//kythe/go/platform/vfs",
        "@go_gcloud//:cloud",
        "@go_x_net//:context",
        "@go_x_oauth2//:google",
        "@go_x_oauth2//:oauth2",
    ],
)
