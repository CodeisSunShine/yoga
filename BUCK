load("//ReactNative:DEFS.bzl", "rn_xplat_cxx_library")

rn_xplat_cxx_library(
    name = "yoga",
    srcs = glob(["yoga/*.cpp"]),
    header_namespace = "",
    exported_headers = glob(["yoga/*.h"]),
    compiler_flags = [
        "-fno-omit-frame-pointer",
        "-fexceptions",
        "-Wall",
        "-Werror",
        "-std=c++1y",
        "-O3",
    ],
    force_static = True,
    visibility = ["PUBLIC"],
    deps = [
    ],
)
