load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")



# ----------------------------------------------pybind---------------------------------------------------

pybind_version = "2.10.4"

http_archive(
    name = "pybind11",
    build_file = "@pybind11_bazel//:pybind11.BUILD",
    strip_prefix = "pybind11-%s" % pybind_version,
    urls = ["https://github.com/pybind/pybind11/archive/v%s.tar.gz" % pybind_version],
)

