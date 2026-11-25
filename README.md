# Cloud Journey: Hands-On AWS and Linux Engineering

![AWS](https://img.shields.io/badge/AWS-Hands--on-FF9900?logo=amazonaws&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-Ubuntu-FCC624?logo=linux&logoColor=black)
![Status](https://img.shields.io/badge/Status-Actively%20Building-2EA44F)

I'm building my career as a cloud engineer. This repo documents my hands-on work with AWS and Linux, from my first self-directed projects through a full cloud bootcamp.

Before cloud, I worked in B2B technology sales and project management at Fortune 500 telecom companies. That background shapes how I build: I think about cost, risk, and the people who depend on the infrastructure, not just whether it runs.

Every project here was built by me, verified, and written up with the commands, screenshots, and lessons learned.

**Live class portfolio site:** [daizah.com.s3-website.us-east-2.amazonaws.com](http://daizah.com.s3-website.us-east-2.amazonaws.com), hosted on Amazon S3.

---

## Projects at a Glance

### Phase 1: AWS Foundations (self-directed, before bootcamp)

| # | Project | Services | What it proves |
|---|---|---|---|
| 1 | [Host a Website on Amazon S3](s3-static-website/) | S3 | Serverless static hosting, bucket policies, public vs private access |
| 2 | [Build a Custom VPC](vpc-networking/) | VPC, Subnets, Route Tables | Network isolation, CIDR planning, routing |
| 3 | [Cloud Security with IAM](iam-security/) | IAM, EC2 | Least privilege, tag-based access control, environment separation |

### Phase 2: Cloud Bootcamp (Linux, systems administration, and AWS)

| # | Project | Tools | What it proves |
|---|---|---|---|
| 4 | [Multi-User Web Server](linux-multi-user-web-server/) | nginx, Ubuntu, users, groups, permissions | Least-privilege file access for a shared server |
| 5 | [Name-Based Virtual Hosts](linux-virtual-hosts/) | nginx server blocks, curl, /etc/hosts | Hosting many sites on one server |
| 6 | [Firewall and SSH Hardening](linux-firewall-hardening/) | ufw, OpenSSH | Default-deny firewall, root login disabled |
| 7 | [Automated Backups](linux-backup-automation/) | Bash, tar, cron, systemd timers | Scripting, scheduling, retention policy |
| 8 | [Portfolio Site on S3 with a Contact Form](s3-portfolio-website/) | S3, bucket policy, Formspree | Static website hosting, custom error page, public read access, live contact form |
| 9 | [Adding Persistent Storage with Amazon EBS](ebs-volume-storage/) | EC2, EBS, parted, ext4, /etc/fstab | Attaching, partitioning, formatting, and persistently mounting cloud storage |

### Completed in Bootcamp (write-ups coming)

| Project | Services |
|---|---|
| 2-Tier Website on AWS | EC2, Apache/Nginx, RDS MySQL |
| Elastic Load Balancer + Auto Scaling | ELB, Auto Scaling, CloudWatch |
| Domain Registration + DNS Integration | Route 53, ELB |
| Securing the Website with SSL/TLS | ACM, ELB |

### In Progress: Cloud Bootcamp

| Project | Services |
|---|---|
| Containerizing Apps with Docker | Docker, Docker Hub, ECR |
| Version Control with Git & GitHub | Git, GitHub |
| Infrastructure as Code | Terraform, CloudFormation |
| Provisioning & Managing AWS RDS | RDS MySQL, SQL Workbench |

---

## Skills Demonstrated

| Area | Skills |
|---|---|
| **AWS** | S3 static website hosting with custom error pages, VPC design (CIDR, subnets, route tables), IAM users, groups, and JSON policies, EC2 launch and tagging, EBS volumes |
| **Security** | Least privilege, tag-based access conditions, explicit deny, firewall default-deny, disabling root SSH, Linux file permissions (setgid, 2750/640) |
| **Linux** | Ubuntu, Amazon Linux, apt, systemd services and timers, users and groups, file permissions, `/etc/hosts`, disk partitioning, ext4, mounting and `/etc/fstab` |
| **Web servers** | nginx server blocks, config testing and reloads, testing with curl |
| **Automation** | Bash scripting, cron, systemd timers, log and retention management |
| **Networking** | CIDR blocks, subnets, routing, ports and services, host-header routing |
| **Delivery** | Scoping, documentation, verification steps, risk management, Agile (PMP, PSM) |

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

## Engineer First, With Delivery Skills

My focus is the build: designing, deploying, securing, and automating infrastructure. What I add on top is a project management background. I scope work before I start, document as I go, plan for what can fail, and can explain technical tradeoffs to the people paying for them. Over time, that combination is what turns an engineer into the person who leads migrations and technical teams.

| Cloud concept | How my delivery background helps |
|---|---|
| Shared responsibility model | Clear ownership and accountability (RACI) |
| High availability design | Risk planning and redundancy |
| Least privilege (IAM) | Stakeholder access and permissions planning |
| Auto scaling | Capacity and resource planning |
| Cost optimization | Budget management and vendor negotiation |
| Monitoring and alerts | KPI dashboards and project health tracking |
| Backups and retention | Business continuity and disaster recovery planning |

**Where this leads:** Cloud Engineer first. From there, leading cloud migrations, growing into a Cloud Solutions Architect role, and consulting through my firm, Patterson Strategic Solutions.

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

- **Cloud portfolio site:** [daizah.com.s3-website.us-east-2.amazonaws.com](http://daizah.com.s3-website.us-east-2.amazonaws.com)
- **Portfolio:** [github.com/Daizah/pm-portfolio](https://github.com/Daizah/pm-portfolio)
- **Business:** [Patterson Strategic Solutions](https://pattersonstrategicsolutions.com)
