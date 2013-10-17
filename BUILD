[
 { "autoconf": {
    "name": "cppunit_conf",
    "configure_env": [ "USER_LDFLAGS=\"-ldl\"" ],
    "outs": [ "$GEN_DIR/lib/libcppunit.a" ]
 } },
 { "cc_library": {
    "name": "cppunit",
    "strict_file_mode": false,
    "cc_objects": [ "$GEN_DIR/lib/libcppunit.a" ],
    "cc_headers": [ "include/cppunit/*.h",
                    "include/cppunit/*/*.h",
                    "include/cppunit/*/*/*.h" ],
    "cc_include_dirs": [ "include" ],
    "dependencies": [ ":cppunit_conf" ]
 } }
]