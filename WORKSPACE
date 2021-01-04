workspace(
    name = "hyperboria",
    managed_directories = {"@npm": ["rules/nodejs/node_modules"]},
)

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "bazel_skylib",
    sha256 = "11b0e65ec07113b2ea81be554c7471bb80fc5766aba6239c91d071602c46d50f",
    strip_prefix = "bazel-skylib-dc080e95161964a1ff841bfd0b871a1123c027a8",
    urls = [
        "https://github.com/bazelbuild/bazel-skylib/archive/dc080e95161964a1ff841bfd0b871a1123c027a8.tar.gz",
    ],
)

http_archive(
    name = "build_bazel_rules_nodejs",
    sha256 = "6a67a8a1bf6fddc9113f73471029b819eef4575c3a936a4a01d57e411894d692",
    urls = [
        "https://github.com/bazelbuild/rules_nodejs/releases/download/2.0.2/rules_nodejs-2.0.2.tar.gz",
    ],
)

http_archive(
    name = "com_github_grpc_grpc",
    sha256 = "f046d4cb4d60d4f2a2087e9d46c7ec0c523cd54ebf68eda6272de4ce65e20ac7",
    strip_prefix = "grpc-ae7f520358d7145a7484db693376fdebbd72662d",
    urls = [
        "https://github.com/grpc/grpc/archive/ae7f520358d7145a7484db693376fdebbd72662d.tar.gz",
    ],
)

http_archive(
    name = "com_google_protobuf",
    sha256 = "7d663c8dc81d282dc92e884b38e9c179671e31ccacce311154420e65f7d142c6",
    strip_prefix = "protobuf-3.13.0.1",
    urls = [
        "https://github.com/protocolbuffers/protobuf/archive/v3.13.0.1.tar.gz",
    ],
)

http_archive(
    name = "io_bazel_rules_docker",
    sha256 = "ba415feb61f7dd08051c7096df9feeb2109bc918878ef924ad9262fe0fcdf6f9",
    strip_prefix = "rules_docker-9bfcd7dbf0294ed9d11a99da6363fc28df904502",
    urls = [
        "https://github.com/bazelbuild/rules_docker/archive/9bfcd7dbf0294ed9d11a99da6363fc28df904502.zip",
    ],
)

http_archive(
    name = "io_bazel_rules_k8s",
    sha256 = "95addfd2b7b07b5a4e75663d15aa57dc271f7b831ec404109322288e1b6bf126",
    strip_prefix = "rules_k8s-9f9886c7252d66bb2e2206842b149a6ceebe6fe5",
    urls = [
        "https://github.com/bazelbuild/rules_k8s/archive/9f9886c7252d66bb2e2206842b149a6ceebe6fe5.zip",
    ],
)

http_archive(
    name = "io_bazel_rules_rust",
    sha256 = "50a772198877e21a61823fa292d28539f8bc99d72463e55b5b09942394ec370e",
    strip_prefix = "rules_rust-9a8ef691b8e8f682d767189c38339cbee16d0a16",
    urls = [
        # Master branch as of 2020-10-16
        "https://github.com/bazelbuild/rules_rust/archive/9a8ef691b8e8f682d767189c38339cbee16d0a16.tar.gz",
    ],
)

http_archive(
    name = "rules_jvm_external",
    sha256 = "d85951a92c0908c80bd8551002d66cb23c3434409c814179c0ff026b53544dab",
    strip_prefix = "rules_jvm_external-3.3",
    urls = [
        "https://github.com/bazelbuild/rules_jvm_external/archive/3.3.zip",
    ],
)

http_archive(
    name = "rules_pkg",
    sha256 = "0a33148c4957e666a29443f75b2c0db1fe3e0baf7256742fc47a35731f7a1d2e",
    strip_prefix = "rules_pkg-4b0b9f4679484f107f750a60190ff5ec6b164a5f/pkg",
    urls = [
        "https://github.com/bazelbuild/rules_pkg/archive/4b0b9f4679484f107f750a60190ff5ec6b164a5f.zip",
    ],
)

http_archive(
    name = "rules_proto",
    sha256 = "aa1ee19226f707d44bee44c720915199c20c84a23318bb0597ed4e5c873ccbd5",
    strip_prefix = "rules_proto-40298556293ae502c66579620a7ce867d5f57311",
    urls = [
        "https://github.com/bazelbuild/rules_proto/archive/40298556293ae502c66579620a7ce867d5f57311.tar.gz",
    ],
)

http_archive(
    name = "rules_python",
    sha256 = "ae3c1380c3c19d47fb474f201862dde7c14601130be2befa73bb02211267e960",
    strip_prefix = "rules_python-e3df8bcf0f675d20aaf752c8ba32a0259dd79996",
    urls = [
        "https://github.com/bazelbuild/rules_python/archive/e3df8bcf0f675d20aaf752c8ba32a0259dd79996.tar.gz",
    ],
)

http_archive(
    name = "rules_python_external",
    sha256 = "30987e33c0b00ef75d11dec756db6a5d57ccd4085525f8888d5237ef798f8d16",
    strip_prefix = "rules_python_external-2c78da5b5beb78c4a96b8b4d84e9c34de8178efb",
    urls = [
        "https://github.com/dillon-giacoppo/rules_python_external/archive/2c78da5b5beb78c4a96b8b4d84e9c34de8178efb.zip",
    ],
)

http_archive(
    name = "subpar",
    sha256 = "e6e4332bf9af36c4165ad6cc7b2c76288e9f156eba35dc95b739e58c46f30a50",
    strip_prefix = "subpar-9fae6b63cfeace2e0fb93c9c1ebdc28d3991b16f",
    urls = [
        "https://github.com/google/subpar/archive/9fae6b63cfeace2e0fb93c9c1ebdc28d3991b16f.zip",
    ],
)

http_archive(
    name = "cython",
    build_file = "@com_github_grpc_grpc//third_party:cython.BUILD",
    sha256 = "e2e38e1f0572ca54d6085df3dec8b607d20e81515fb80215aed19c81e8fe2079",
    strip_prefix = "cython-0.29.21",
    urls = [
        "https://github.com/cython/cython/archive/0.29.21.tar.gz",
    ],
)

# Java

load("//rules/java:artifacts.bzl", "maven_fetch_remote_artifacts")

maven_fetch_remote_artifacts()

# Rust

load("@io_bazel_rules_rust//rust:repositories.bzl", "rust_repository_set")

rust_version = "1.48.0"

rustfmt_version = "1.4.20"

rust_repository_set(
    name = "rust_linux_x86_64",
    edition = "2018",
    exec_triple = "x86_64-unknown-linux-gnu",
    extra_target_triples = ["wasm32-unknown-unknown"],
    rustfmt_version = rustfmt_version,
    version = rust_version,
)

rust_repository_set(
    name = "rust_darwin_x86_64",
    edition = "2018",
    exec_triple = "x86_64-apple-darwin",
    extra_target_triples = ["wasm32-unknown-unknown"],
    rustfmt_version = rustfmt_version,
    version = rust_version,
)

load("@io_bazel_rules_rust//:workspace.bzl", "bazel_version")

bazel_version(name = "bazel_version")

load("//rules/rust:crates.bzl", "raze_fetch_remote_crates")

raze_fetch_remote_crates()

register_toolchains("//:proto-toolchain")

# NodeJS
load("@build_bazel_rules_nodejs//:index.bzl", "yarn_install")

yarn_install(
    name = "npm",
    package_json = "//rules/nodejs:package.json",
    symlink_node_modules = True,
    use_global_yarn_cache = True,
    yarn_lock = "//rules/nodejs:yarn.lock",
)

# Packaging

load("@rules_pkg//:deps.bzl", "rules_pkg_dependencies")

rules_pkg_dependencies()

# Docker Setup

load(
    "@io_bazel_rules_docker//toolchains/docker:toolchain.bzl",
    docker_toolchain_configure = "toolchain_configure",
)

docker_toolchain_configure(
    name = "docker_config",
    client_config = "/docker",
)

load("@io_bazel_rules_docker//repositories:repositories.bzl", container_repositories = "repositories")

container_repositories()

load("@io_bazel_rules_docker//repositories:deps.bzl", container_deps = "deps")

container_deps()

load("@io_bazel_rules_docker//repositories:pip_repositories.bzl", "pip_deps")

pip_deps()

load("@io_bazel_rules_docker//java:image.bzl", java_image_repos = "repositories")
load("@io_bazel_rules_docker//python3:image.bzl", py3_image_repos = "repositories")
load("@io_bazel_rules_docker//nodejs:image.bzl", nodejs_image_repos = "repositories")
load("@io_bazel_rules_docker//rust:image.bzl", rust_image_repos = "repositories")

java_image_repos()

nodejs_image_repos()

py3_image_repos()

rust_image_repos()

# Python
register_toolchains("//rules/python:py_toolchain")

load("@rules_python_external//:defs.bzl", "pip_install")

pip_install(
    name = "pip_modules_external",
    requirements = "//rules/python:requirements.txt",
)

load("@rules_python_external//:repositories.bzl", "rules_python_external_dependencies")

rules_python_external_dependencies()

# K8s

load("@io_bazel_rules_k8s//k8s:k8s.bzl", "k8s_repositories")

k8s_repositories()

load("@io_bazel_rules_k8s//k8s:k8s_go_deps.bzl", k8s_go_deps = "deps")

k8s_go_deps()

# Miscellaneous

load("//rules/misc:setup.bzl", "rules_misc_setup_internal")

rules_misc_setup_internal()

load("//rules/misc:install.bzl", "rules_misc_install_internal")

rules_misc_install_internal()

# Images Install

load("//images:install.bzl", "images_install")

images_install()

# Proto / gRPC

load("@rules_proto//proto:repositories.bzl", "rules_proto_dependencies", "rules_proto_toolchains")

rules_proto_dependencies()

rules_proto_toolchains()

load("@com_github_grpc_grpc//bazel:grpc_deps.bzl", "grpc_deps")

grpc_deps()

load("@com_github_grpc_grpc//bazel:grpc_extra_deps.bzl", "grpc_extra_deps")

grpc_extra_deps()
