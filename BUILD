[
 { "autoconf": {
    "name": "cppunit_conf",
    "configure_env": [ "USER_LDFLAGS=\"-ldl\"" ],
    "outs": [ "$GEN_DIR/lib/libcppunit.a" ]
 } },
 { "cc_library": {
    "name": "cppunit",
    "cc_objects": [ "$GEN_DIR/lib/libcppunit.a" ],
    "cc_headers": [ "include/cppunit/*.h",
                    "include/cppunit/*/*.h",
                    "include/cppunit/*/*/*.h" ],
    "include_dirs": [ "include" ],
    "dependencies": [ ":cppunit_conf" ]
 } }
]