load("@build_bazel_rules_nodejs//:defs.bzl", "jasmine_node_test")

jasmine_node_test(
    name = "tests",
    bootstrap = ["test_workspace/bootstrap.js"],
    data = glob([
        "*.js",
    ]),
	node_modules = "@runtime_deps//:node_modules",
)
