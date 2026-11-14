# Montez Guido

**Cloud & Network Engineer | AWS • Terraform • Python • Linux • Network Automation**

Cloud and network engineering professional with experience supporting enterprise networks, AWS data-center infrastructure, Linux systems, and incident troubleshooting. I build practical, testable projects that demonstrate infrastructure design, automation, secure operations, and reliability engineering.

**Focus:** Cloud Engineer • Cloud Operations • Site Reliability Engineering • Platform Engineering

## Featured engineering work

### [Network Reliability Lab](https://github.com/montezguido/network-reliability-lab) — Executable Python project
[![Verify Python code](https://github.com/montezguido/network-reliability-lab/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/montezguido/network-reliability-lab/actions/workflows/test.yml)

A runnable Python service monitor with HTTP/TCP checks, stateful **OPENED/RECOVERED** incident transitions, safe local-only probing, JSON persistence, and an end-to-end outage/recovery walkthrough. **Five Linux/Windows CI jobs passed** on the initial publication.

**Evidence:** [source](https://github.com/montezguido/network-reliability-lab/tree/main/src/network_reliability) · [tests](https://github.com/montezguido/network-reliability-lab/tree/main/tests) · [verification](https://github.com/montezguido/network-reliability-lab/blob/main/docs/verification-report.md)

### [AWS IaaS & Linux Infrastructure](https://github.com/montezguido/aws-iaas-linux-infrastructure) — WGU case study + independently verified Terraform
Documented EC2/Ubuntu administration, Apache, SSH, TLS, and CloudWatch lab work. A separate, independently developed [Terraform reference](https://github.com/montezguido/aws-iaas-linux-infrastructure/tree/main/reference) defines VPC networking and an opt-in Ubuntu EC2 web demo with no inbound SSH, EBS encryption, IMDSv2, and [successful offline CI tests](https://github.com/montezguido/aws-iaas-linux-infrastructure/actions/runs/43628187303). No AWS deployment is claimed for the new code.

### [Hybrid Cloud Network Engineering Capstone](https://github.com/montezguido/hybrid-cloud-network-engineering-capstone) — Hybrid design + runnable verification
Documented GNS3-to-AWS hybrid connectivity, VLAN segmentation, private VPN routing, and source-aware security. Includes separate Python exercises for synthetic VPC/subnet design and default-deny access-policy checks, with automated Linux/Windows CI. [View evidence matrix](https://github.com/montezguido/hybrid-cloud-network-engineering-capstone/blob/main/docs/requirements-evidence.md).

### [Python Network Automation & Incident Response](https://github.com/montezguido/network-automation-incident-response) — WGU case study + independently tested code
Documented DNS incident recovery, device troubleshooting, and automation from WGU coursework. A separate [offline Python demo](https://github.com/montezguido/network-automation-incident-response/tree/main/portfolio_demo) classifies DNS service failures and unauthorized resolvers, models incident and ticket lifecycles, and includes [31 regression tests with passing Linux/Windows CI](https://github.com/montezguido/network-automation-incident-response/actions/runs/43629035915). Live network remediation and ticketing are not claimed.

> Repositories contain different types of evidence: runnable source, infrastructure definitions, and documented engineering case studies. Documentation-only repositories are not presented as executable software.

## Technical toolkit

- **Cloud and IaC:** AWS, EC2, VPC, IAM, CloudWatch, Terraform, hybrid networking
- **Network engineering:** TCP/IP, DNS, DHCP, VLANs, routing, switching, VPNs, Wireshark
- **Development and operations:** Python, Linux, Git, GitHub Actions, automation, incident response
- **Security:** Least privilege, network segmentation, security groups, monitoring, cloud security fundamentals

## Certifications and education

AWS Certified Solutions Architect – Associate • AWS Certified CloudOps Engineer • AWS Certified Cloud Practitioner • CompTIA Security+ • Network+ • A+ • Project+ • ITIL Foundation • Linux Foundations

**Western Governors University:** B.S. Cloud and Network Engineering — AWS track; capstone passed, degree conferral pending (2026).

## Currently developing

More rigorous Python automation; Terraform validation and reusable infrastructure modules; Docker/Kubernetes, GitOps, and observability; SEIR/AI operations engineering. These are **learning and development priorities**, not claims of completed deployments.

**Engineering approach:** Build → test → verify failure and recovery → secure → document → improve.
