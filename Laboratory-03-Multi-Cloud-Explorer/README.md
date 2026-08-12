# Laboratory 03 – Multi-Cloud Explorer

This laboratory activity focuses on exploring and comparing Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP).

It includes cloud platform research, service comparisons, business recommendations, Linux cloud hosting, and a reflection on the role of a Cloud Solutions Consultant.

## Checkpoint 7 – Continue Your Linux Investigation

### Linux Server Information

A Linux server was launched using the KillerCoda Playground. Linux commands were used to identify the operating system, CPU information, memory, and disk space.

If this Linux server were migrated to the cloud, which AWS, Azure, and GCP services could host it?

Answer:

If this Linux server were migrated to the cloud, it could be hosted using Amazon EC2 in AWS, Azure Virtual Machines in Microsoft Azure, or Google Compute Engine in Google Cloud. These services provide virtual machines that can run Linux operating systems such as Ubuntu. They can provide the computing resources needed to run the server and its applications.


| Category | Information |
|---|---|
| Operating System | Ubuntu 24.04.4 LTS (Noble Numbat) |
| Architecture | x86_64 |
| CPU | Intel Xeon E312xx (Sandy Bridge, IBRS update) |
| CPU Speed | 2.0 GHz |
| Number of CPUs | 1 |
| Total Memory | 1.9 GiB |
| Memory Used | 424 MiB |
| Memory Available | 1.4 GiB |
| Disk Size | 19 GB |
| Disk Used | 5.4 GB |
| Disk Available | 13 GB |
| Disk Usage | 30% |

### Linux Commands Used

#### 1. Operating System

```bash
cat /etc/os-release
