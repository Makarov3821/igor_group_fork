# REST 容器下载

[← 返回首页](./index.md)

**2025 年 workshop 版**

---

## 关于 REST

**REST**（Rust-based Electronic Structure Theory）是全球首个完全基于 Rust 语言的电子结构软件包。

**源代码与文档：** [gitee.com/restgroup](https://gitee.com/restgroup)

---

## 当前版本：v2025.01

| 项目 | 详情 |
|------|------|
| **版本** | 2025.01（Workshop 版） |
| **发布日期** | 2025 年 11 月 28 日 |
| **存储** | 阿里云 OSS |

---

## 下载

### Docker 容器镜像
- **文件：** `rest_2025.01.tar.gz`（约 1.6 GB）
- **下载：** [rest_2025.01.tar.gz](https://rest-package-image.oss-cn-hangzhou.aliyuncs.com/docker/rest_2025.01.tar.gz)

### Apptainer/Singularity 镜像
- **文件：** `rest_2025.01.sif`（约 1.6 GB）
- **下载：** [rest_2025.01.sif](https://rest-package-image.oss-cn-hangzhou.aliyuncs.com/apptainer/rest_2025.01.sif)

### Conda
[![Conda](https://anaconda.org/restgroup/rest/badges/latest_release_date.svg)](https://anaconda.org/restgroup/rest)

---

## 快速安装

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

## 引用

> Li, Z.; Gao, T.; Wang, S.; et al. REST: Embracing the Rust Programming Language for Modern Electronic Structure Theory. *Chin. J. Chem. Phys.* **2025**. DOI: [10.1063/1674-0068/cjcp2510156](https://doi.org/10.1063/1674-0068/cjcp2510156)

[← 返回首页](./index.md)
