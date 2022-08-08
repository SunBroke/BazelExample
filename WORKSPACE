load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
#old
# http_archive(
#     name = "gtest",
#     url = "https://github.com/google/googletest/archive/release-1.10.0.zip",
#     sha256 = "94c634d499558a76fa649edb13721dce6e98fb1e7018dfaeba3cd7a083945e91",
#     # 指定BUILD文件
#     build_file = "@//thirdparty:gtest.BUILD",
#     # 去除BUILD中指定前缀
#     strip_prefix = "googletest-release-1.10.0",
# )

#new
http_archive(
  name = "com_google_googletest",
  urls = ["https://github.com/google/googletest/archive/609281088cfefc76f9d0ce82e1ff6c30cc3591e5.zip"],
  strip_prefix = "googletest-609281088cfefc76f9d0ce82e1ff6c30cc3591e5",
)