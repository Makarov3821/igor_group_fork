# REST Container Downloads

[← Back to Homepage](./index.md)

**Workshop Edition — November 2025**

---

## About REST

**REST** (Rust-based Electronic Structure Theory) is the first electronic structure package built entirely in Rust.

**Source code & docs:** [gitee.com/restgroup](https://gitee.com/restgroup)

---

## Current Version: v2025.01

| Item | Detail |
|------|--------|
| **Version** | 2025.01 (Workshop Edition) |
| **Release Date** | Nov 28, 2025 |
| **Storage** | Alibaba Cloud OSS |

---

## Downloads

### Docker Container Image
- **File:** `rest_2025.01.tar.gz` (~1.6 GB)
- **Download:** [rest_2025.01.tar.gz](https://rest-package-image.oss-cn-hangzhou.aliyuncs.com/docker/rest_2025.01.tar.gz)

### Apptainer/Singularity Image
- **File:** `rest_2025.01.sif` (~1.6 GB)
- **Download:** [rest_2025.01.sif](https://rest-package-image.oss-cn-hangzhou.aliyuncs.com/apptainer/rest_2025.01.sif)

### Conda
[![Conda](https://anaconda.org/restgroup/rest/badges/latest_release_date.svg)](https://anaconda.org/restgroup/rest)

---

## Quick Install

### Conda
```bash
conda create -n rest python=3.11 -c conda-forge
conda activate rest
conda install rest -c restgroup -c mokit -c conda-forge
```

### Docker
```bash
wget -O rest_2025.01.tar.gz "https://rest-package-image.oss-cn-hangzhou.aliyuncs.com/docker/rest_2025.01.tar.gz"
docker load < rest_2025.01.tar.gz
```

### Apptainer/Singularity
```bash
wget -O rest_2025.01.sif "https://rest-package-image.oss-cn-hangzhou.aliyuncs.com/apptainer/rest_2025.01.sif"
singularity exec rest_2025.01.sif rest --version
```

---

## Citation

> Li, Z.; Gao, T.; Wang, S.; et al. REST: Embracing the Rust Programming Language for Modern Electronic Structure Theory. *Chin. J. Chem. Phys.* **2025**. DOI: [10.1063/1674-0068/cjcp2510156](https://doi.org/10.1063/1674-0068/cjcp2510156)

[← Back to Homepage](./index.md)
