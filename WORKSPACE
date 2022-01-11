workspace(name = "p8n")

# solution 1, use git_repository in bazel, need to do bazel sync
load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")

git_repository(
    name = "third_party",
    branch = "main",
    remote = "ssh://git@github.com/cyrilhuang/third_party.git",
)

# solution 2, use git submodule and local_repository in bazel, need to do git submodule update
#local_repository(
#    name = "third_party",
#    path = "third_party",
#)

