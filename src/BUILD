java_proto_library(
    name = "onos-cfg",
    deps = [
       
        ":ConfigProperty_proto",
    ],
)

######### cfg ###########
proto_library(
    name = "ConfigPropertyEnums_proto",
    srcs = ["ConfigPropertyEnumsProto.proto"],
)

proto_library(
    name = "ConfigProperty_proto",
    srcs = ["ConfigPropertyProto.proto"],
    deps = [":ConfigPropertyEnums_proto"],
)
