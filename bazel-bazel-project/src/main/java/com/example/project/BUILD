java_binary(
    name = "hello-world",
    srcs = ["HelloWorld.java"],
    main_class = "main.java.com.example.project.HelloWorld",
    deps = [":util-lib"],
)

java_library(
    name = "util-lib",
    srcs = ["custom/MyUtil.java"],
    visibility = ["//visibility:public"],
)
