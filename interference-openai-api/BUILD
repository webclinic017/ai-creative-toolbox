load("@pip//:requirements.bzl", "requirement")
load("@rules_python//python:defs.bzl", "py_binary", "py_test")

py_binary(
    name = "server",
    srcs = ["__main__.py"],
    imports = ["."],
    main = "__main__.py",
    deps = [
        requirement("flask_cors"),
        requirement("g4f"),
        requirement("watchdog"),
        requirement("httpx"),
    ],
)
