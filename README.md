# Cloud Journey: AWS, Linux, and Cloud Project Leadership

![AWS](https://img.shields.io/badge/AWS-Hands--on-FF9900?logo=amazonaws&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-Ubuntu-FCC624?logo=linux&logoColor=black)
![PMP](https://img.shields.io/badge/PMP-Certified-0A66C2)
![Status](https://img.shields.io/badge/Status-Actively%20Building-2EA44F)

I'm a PMP-certified project manager with an MBA and a background in B2B technology sales (Verizon/Frontier, T-Mobile for Business, AT&T). This repo documents my hands-on path into cloud engineering and architecture, with the goal of leading cloud migrations and infrastructure projects as someone who understands both the business case and the build.

Every project here was built by me, verified, and written up with the commands, screenshots, and lessons learned.

---

## Projects at a Glance

### Phase 1: AWS Foundations (self-directed, before bootcamp)

| # | Project | Services | What it proves |
|---|---|---|---|
| 1 | [Host a Website on Amazon S3](s3-static-website/) | S3 | Serverless static hosting, bucket policies, public vs private access |
| 2 | [Build a Custom VPC](vpc-networking/) | VPC, Subnets, Route Tables | Network isolation, CIDR planning, routing |
| 3 | [Cloud Security with IAM](iam-security/) | IAM, EC2 | Least privilege, tag-based access control, environment separation |

### Phase 2: Cloud Bootcamp (Linux and systems administration)

| # | Project | Tools | What it proves |
|---|---|---|---|
| 4 | [Multi-User Web Server](linux-multi-user-web-server/) | nginx, Ubuntu, users, groups, permissions | Least-privilege file access for a shared server |
| 5 | [Name-Based Virtual Hosts](linux-virtual-hosts/) | nginx server blocks, curl, /etc/hosts | Hosting many sites on one server |
| 6 | [Firewall and SSH Hardening](linux-firewall-hardening/) | ufw, OpenSSH | Default-deny firewall, root login disabled |
| 7 | [Automated Backups](linux-backup-automation/) | Bash, tar, cron, systemd timers | Scripting, scheduling, retention policy |

---

## Skills Demonstrated

| Area | Skills |
|---|---|
| **AWS** | S3 static hosting, VPC design (CIDR, subnets, route tables), IAM users, groups, and JSON policies, EC2 launch and tagging |
| **Security** | Least privilege, tag-based access conditions, explicit deny, firewall default-deny, disabling root SSH, Linux file permissions (setgid, 2750/640) |
| **Linux** | Ubuntu, apt, systemd services and timers, users and groups, file permissions, `/etc/hosts` |
| **Web servers** | nginx server blocks, config testing and reloads, testing with curl |
| **Automation** | Bash scripting, cron, systemd timers, log and retention management |
| **Networking** | CIDR blocks, subnets, routing, ports and services, host-header routing |
| **Project leadership** | Scoping, documentation, verification steps, risk thinking (PMP, PSM) |

---

## Certification Roadmap

| Certification | Level | Status |
|---|---|---|
| PMP (Project Management Professional) | Professional | ✅ Certified |
| PSM (Professional Scrum Master) | Professional | ✅ Certified |
| AWS Certified Cloud Practitioner (CLF-C02) | Foundational | In progress |
| AWS Solutions Architect Associate (SAA-C03) | Associate | Next |
| AWS Solutions Architect Professional (SAP-C02) | Professional | Long-term goal |

---

## Why Cloud + Project Management

Most project managers can run a timeline. Far fewer can sit with engineers, understand the tradeoffs between services, and translate technical decisions into cost, risk, and business outcomes. That's the gap I'm closing.

| Cloud concept | How I apply it as a PM |
|---|---|
| Shared responsibility model | Clear ownership and accountability (RACI) |
| High availability design | Risk planning and redundancy |
| Least privilege (IAM) | Stakeholder access and permissions planning |
| Auto scaling | Capacity and resource planning |
| Cost optimization | Budget management and vendor negotiation |
| Monitoring and alerts | KPI dashboards and project health tracking |
| Backups and retention | Business continuity and disaster recovery planning |

**Where this leads:** Cloud Project Manager, Technical Program Manager, Cloud Solutions Architect, and consulting on cloud migrations through my firm, Patterson Strategic Solutions.

---

## What's Next

- [ ] Pass AWS Cloud Practitioner
- [ ] Deploy a web server on EC2 inside my custom VPC (public and private subnets, NAT gateway)
- [ ] Add HTTPS to the S3 site with CloudFront
- [ ] Ship backups to S3 instead of local disk
- [ ] Rebuild one project with Terraform (infrastructure as code)

---

## Learning Resources

- [Nextwork](https://learn.nextwork.org): hands-on AWS projects
- [AWS Skill Builder](https://skillbuilder.aws/): official AWS training
- [AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/)
- Stephane Maarek (Udemy) and Adrian Cantrill for exam prep

---

## Connect

- **Portfolio:** [github.com/Daizah/pm-portfolio](https://github.com/Daizah/pm-portfolio)
- **Business:** [Patterson Strategic Solutions](https://pattersonstrategicsolutions.com)

To add a new project, copy [PROJECT_TEMPLATE.md](PROJECT_TEMPLATE.md) into a new folder.
