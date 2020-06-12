load(
    "//bazel:envoy_build_system.bzl",
    "envoy_cc_binary",
    "envoy_cc_library",
)

envoy_cc_binary(
    name = "httpserver-static",
    deps = ["httpserver_main_entry_lib"],
)

envoy_cc_library(
    name = "httpserver_main_entry_lib",
    srcs = ["main.cc"],
)

