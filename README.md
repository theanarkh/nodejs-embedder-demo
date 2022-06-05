# nodejs-embedder-demo

src/node_code_cache_stub.cc src/node_snapshot_stub.cc is from Node.js source

g++ Node.cc src/node_code_cache_stub.cc src/node_snapshot_stub.cc -Ixxx/include/node -std=c++14 -L xxx/out/Release -l v8_base_without_compiler -l v8_compiler -l v8_init -l v8_initializers -l v8_libbase -l v8_libplatform -l v8_snapshot -l brotli -l cares -l gtest -l gtest_main -l histogram -l icudata -l icui18n -l icutools -l icuucx -l llhttp -l nghttp2 -l nghttp3 -l ngtcp2  -l openssl -l torque_base -l uv -l uvwasi -l v8_zlib -l zlib -l pthread -l node
