load("//tools:cpplint.bzl", "cpplint")

package(default_visibility = ["//visibility:public"])

cc_library(
    name = "reference_line_matcher",
    hdrs = [
        "reference_line_matcher.h",
    ],
    srcs = [
        "reference_line_matcher.cc",
    ],
    deps = [
        "//modules/common:common",
        "//modules/planning/common:planning_gflags",
        "//modules/planning/math:hermite_spline",
        "//modules/common/proto:pnc_point_proto",
        "//modules/planning/common:planning_common",
        "@glog//:glog",
    ],
)

cc_library(
    name = "lattice_trajectory1d",
    hdrs = [
        "lattice_trajectory1d.h",
    ],
    srcs = [
        "lattice_trajectory1d.cc",
    ],
    deps = [
        "//modules/planning/math/curve1d:curve1d",
    ],
)

cpplint()
