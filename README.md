# Onboarding Guide for Bioinformatics & Genomics Rotation Students
## This repository provides onboarding information for rotation students in the Girirajan Lab, including lab access, cluster setup, and computational resources.

## 1. Lab Access

* To begin, you will need access to the lab.
* Please fill out the attached document and send it to Ms. Jenn, who will arrange access for the rotation period.
* The required file is provided in this repository.

## 2. Getting Access to the Cluster

* Most genomics-related work in the Girirajan Lab is performed on a High-Performance Computing (HPC) cluster dedicated to research.
* Access is provided through your local terminal (PC/Laptop).
* A request must be sent to the Computer Division team. Alternatively, a current PhD student (Deepro Banerjee) may submit the request on behalf of the rotation student.
Once approved, you will receive credentials to connect to the cluster.

## 3. About the Cluster (HPC Basics)

* For those unfamiliar with HPC systems: A cluster is essentially a large-scale computer system with hundreds to thousands of cores (CPUs), GPUs, and terabytes of memory and storage.
* Each cluster node is a powerful computer with multiple CPUs and large RAM, used for computation.
* The Girirajan Lab has a dedicated cluster with five computation nodes:

| Node Name | Cores | Special Features |
|-----------|-------|------------------|
| RAMONA    | 40    | General computation |
| DURGA     | 128   | High-memory tasks |
| QINGYU    | 160   | Large-scale jobs |
| SARAH     | 192   | High-throughput tasks |
| LAILA     | 112   | Includes GPU support for deep learning |

Additionally, the cluster also includes eight storage nodes: data, data1, …... data7.

* Note: : Penn State provides a separate HPC resource called ROAR (Routinely Available Online Resources), which can be rented for larger jobs.

## 4. User Profile & Storage

* Each user receives 1–2 TB of personal storage space (home directory).
* Shared datasets are stored on the common storage nodes (data to data7).

## 5. Connecting to the Cluster

* Access the cluster via SSH:
  
```
ssh <psuid>@<computational_node_name>.bx.psu.edu
```


* PSUID: Your Penn State login (e.g., three letters + four digits).
* Computational Node Name: One of the five listed nodes (Ramona, Durga, Qingyu, Sarah, Laila).
* Authentication: Requires your PSU email password and 2FA code from the authenticator app.

## 6. Installing VS Code

* It is recommended to use Visual Studio Code (VS Code) for development because it supports:
* Multiple programming languages (Python, R, etc.)
* Jupyter notebooks

## GitHub Copilot integration and Remote cluster development

## ➡️ Download VS Code from the Microsoft Store or official site.

## 7. Linking VS Code to SSH

* To use VS Code with the cluster:
## Install the following extensions:
* Remote Development
* Remote - Tunnels
* Remote - SSH
(Optional: Python, Jupyter Notebook Keymap, etc.)

## Configure settings:
✅ Enable required checkboxes as prompted.
# YET TO BE WRITTEN
❌ Disable unnecessary options (based on your preference).
# YET TO BE WRITTEN
* This setup will allow you to code locally while executing jobs on the cluster.

  
# Summary

This guide helps rotation students:
* Gain lab access
* Request and configure cluster access
* Understand the Girirajan Lab HPC cluster and storage system

***THE SETTINGS NEED TO BE CONFIGURED IN THE VS CODE HAVE TO BE UPDATED IN THE README FILE***
