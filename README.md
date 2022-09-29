# Hi there 👋

<!--
**adsanz/adsanz** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

### `whoami`

I'm Adrian! A 24y old IT professional with +3 years of experience in DevOps. I've also worked as a developer and I love developing tools to make my life and others people life easier. 

- 🔭 I’m currently working on MrMilu
- 🌱 I’m currently learning about packer & wireguard
- 👯 I’m looking to collaborate on python projects
- 💬 Ask me about Ansible!
- 😄 Pronouns: He/Him
- ⚡ Fun fact: I have lots of tattos & I'm a gym rat

### `curl -I https://where.tofindme.com/`

```
HTTP/2 301 
date: Thu, 29 Sep 2022 11:40:18 GMT
content-type: text/html
location: https://www.linkedin.com/in/adrian-sanz-melchor/
report-to: ad.sanz@hotmail.com
city: Madrid
c-code: ES
```

### `history | grep "Work exp: "`

####  **1. Work exp: Nokia**

Developed a *platform for students to get access to a virtual machine*. Acting as a **"middleware"** they request the lab from the moodle platform, which would trigger the lab env creation and access on a openstack cloud via the django platform (webhook). This platform will also allow the student the access via "apache guacamole".

There was an admin platform which allowed the teachers to give, revoke or list accesses. All this was backed with AD authentication. It was my first time working with Django, and even thought the platform worked, it was messy and required lots of fixes, this was done in 4 months (hackaton vibe tbh) Now I would opt for a REST API + Admin/student access front on another language. 

####  **2. Work exp: MrMilu**

Started of as a DevOps, managing the full lifecycle of a product, from the local development env, to staging, to production, covering backups, monitoring & security maintenance. Lately I've been working on a start-up project and I've worked on:
- **Cloud Arquitech**: Set-up with terraform (and previously pulumi to test both tools) a full and functional environment. We left out some elements like RDS since that was managed by Ansible playbooks on pipelines. Also I've created different cloud proposals for different clients 
- **Security testing**: Using burpsuite, guided with sonarqube, tried to perform different attacks to test out some SSO features which aid security on JWT tokens
- **SRE**: Monitoring with Prometheus suit (grafana, prom, exporters, loki, prom-executor, karma, alert-manager) the platform and get useful insights on about critical services like RDS, ElastiCache, EC2 instances, celery services. 
- **DevOps & SysOps**: Managed backups on 2 different regions with AWS backups, made a pipeline to execute datasync to get backups moved to Azure for disaster recovery. Configure & provision all envs with Ansible via pipelines on a custom gitlab runner set. 

### `cat goals`

I'm aiming to be an expert on CiberSec someday, that has been my dream since I was 15 and I discovered Chema Alonso, but turns out I'm good as a DevOps, so I aim to be a "SecDevOps"
