git_repository(
    name = "fejta_autogo",
    remote = "https://github.com/kubernetes/test-infra.git",
    commit = "400d4c78044a87f5b1a1247d313fffd443c298bf",
)
load("@fejta_autogo//autogo:deps.bzl", "autogo_dependencies")
autogo_dependencies()
load("@fejta_autogo//autogo:def.bzl", "autogo_generate")
autogo_generate(
    name = "autogo",
    prefix = "github.com/golang/dep",
)
