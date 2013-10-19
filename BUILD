[
{ "cc_library": {
    "name": "smhasher",
    "cc_sources": [ "AvalancheTest.cpp",
                    "Bitslice.cpp",
                    "Bitvec.cpp",
                    "CityTest.cpp",
                    "City.cpp",
                    "crc.cpp",
                    "DifferentialTest.cpp",
                    "Hashes.cpp",
                    "KeysetTest.cpp",
                    "lookup3.cpp",
                    "md5.cpp",
                    "MurmurHash1.cpp",
                    "MurmurHash2.cpp",
                    "MurmurHash3.cpp",
                    "Platform.cpp",
                    "Random.cpp",
                    "sha1.cpp",
                    "SpeedTest.cpp",
                    "Spooky.cpp",
                    "SpookyTest.cpp",
                    "Stats.cpp",
                    "SuperFastHash.cpp",
                    "Types.cpp",
                    "PMurHash.c"
    ],
    "cc_headers": [ "Bitvec.h",
                    "City.h",
                    "Hashes.h",
                    "MurmurHash1.h",
                    "MurmurHash2.h",
                    "MurmurHash3.h",
                    "PMurHash.h",
                    "Platform.h",
                    "Random.h",
                    "Spooky.h",
                    "Stats.h",
                    "Types.h",
                    "pstdint.h",
                    "sha1.h"
    ],
    "gcc" : {
      "cc_compile_args": [ "-Wno-error=unused-but-set-variable" ],
      "header_compile_args": [ "-Wno-error=strict-aliasing" ]
    },
    "licenses": [ "http://opensource.org/licenses/mit-license.php" ]
} },
{ "cc_binary": {
    "name": "benchmark",
    "cc_sources": [ "main.cpp" ],
    "dependencies": [ ":smhasher" ]
} }
]