COMPILE_DEPS = CORE_DEPS + CLI + [
    "//apps/openstacknetworking/api:onos-apps-openstacknetworking-api",
]

TEST_DEPS = TEST_ADAPTERS + [
    "//core/api:onos-api-tests",
    "//core/common:onos-core-common-tests",
]

osgi_jar_with_tests(
    test_deps = TEST_DEPS,
    deps = COMPILE_DEPS,
)
