# GitHub Actions Spack configurations

The Spack configuration files are for GitHub Actions, and include
support for pushing to the `ukri-bench` Spack binary cache.

<!-- GitHub Actions jobs should create environments using one of the files in
this repository. For GPU environments, the Spack configurations are
compatible with the GPU compiler install scripts in this repository.
The GPU compiler scripts can be used as 'actions', e.g.:
```bash
- name: Install ROCm
  uses: ukri-bench/spack-configs/actions/rocm@main
```

```bash
- name: Install CUDA
  uses: ukri-bench/spack-configs/actions/cuda@main
```

- `spack.yml`: For CPU builds, using the default compilers.
- `spack-cuda.yml`: For CUDA builds, compatible with
  `ukri-bench/spack-configs/actions/cuda@main`.
- `spack-rocm.yml`: For ROCm builds, compatible with
  `ukri-bench/spack-configs/actions/rocm@main`.

  See
  https://github.com/ukri-bench/benchmark-dolfinx/blob/main/.github/workflows/spack-ci.yml
  for examples of use. -->