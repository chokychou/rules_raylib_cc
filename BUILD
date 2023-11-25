load("@rules_foreign_cc//foreign_cc:defs.bzl", "cmake")

cmake(
    name = "raylib",
    cache_entries = {
        "CMAKE_C_FLAGS": "-fPIC",
    },
    out_headers_only = True,
    lib_source = "@raylib//:all_srcs",
    out_static_libs = ["raylib.a"],
    visibility = ["//visibility:public"],
)