cc_test(
    name = "hello-test",
    srcs = ["hello-test.cc"],
    copts = ["-Iexternal/gtest/googletest/include"],
    deps = [
        #old
        #"@gtest//:main",

        #new
        "@com_google_googletest//:gtest_main",
        
        "//main:hello-greet",
    ],
)