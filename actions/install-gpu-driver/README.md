# Actions for installing GPU compilers/runtimes

This action execute scripts that install GPU compilers in GitHub
Actions for use in testing. The scripts install versions that are
compatible with the Spack configurations in
https://github.com/ukri-bench/spack-configs/tree/main/configs/gh-actions.

For CUDA:

```
uses: ukri-bench/spack-configs/actions/install-gpu-driver@main
with:
  runtime: cuda
```

For HIP/ROCm:
```
uses: ukri-bench/spack-configs/actions/install-gpu-driver@main
with:
  runtime: rocm
```