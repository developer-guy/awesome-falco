# awesome-falco [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<img src="https://cncf-branding.netlify.app/img/projects/falco/horizontal/color/falco-horizontal-color.svg" width="300"><br/><br/>

A curated list of Falco related tools, frameworks and articles

## Contents

- 💼 [Official Projects](#official-projects)
    - 📂 [Repositories](#repositories)
    - 🗒️ [Docs](#docs)
    - 📰 [Blogs](#blogs-and-articles)
- 🐾 [Community Repositories](#community-repositories)
- 🗃️ [Blogs and Articles](#blogs-and-articles)
- 📹 [Videos](#videos)
- 📑 [Slides](#slides)
- 🎤 [Podcasts](#podcasts)
- 🧪 [Interactive Learning](#interactive-learning)
- 🧰 [IDE and Editor Integrations](#ide-and-editor-integrations)
- 📡 [Support and Community](#support-and-community)
     - 💊 [Develop and Contribute](#develop-and-contribute)
     - 📆 [Learn and Connect](#learn-and-connect)


## Official projects

### Repositories

- [Falco](https://github.com/falcosecurity/falco) - Cloud Native Runtime Security
- [Falco Libs](https://github.com/falcosecurity/libs) - libsinsp, libscap, the kernel module driver, and the eBPF driver sources
- [Falcosidekick](https://github.com/falcosecurity/falcosidekick) - A simple daemon to help you with falco's outputs
- [Falcosidekick UI](https://github.com/falcosecurity/falcosidekick-ui) - A simple WebUI with latest events from Falco
- [falcoctl](https://github.com/falcosecurity/falcoctl) - Administrative tooling for Falco.
- [Falcosecurity Evolution](https://github.com/falcosecurity/evolution) - Evolution process of The Falco Project
- [Falco Event Generator](https://github.com/falcosecurity/event-generator) - Generate a variety of suspect actions that are detected by Falco rulesets

### Docs

- [Falco](https://falco.org/docs/) - Official Falco documentation

### Blogs

- [Falco](https://falco.org/blog/) - Official blog for the Falco project
- [Sysdig Blog](https://sysdig.com/blog/?s=&sd-tax-sysdig-open-source%5B%5D=sysdig-falco) - Explore Sysdig resources for whitepapers, videos, webinars, case studies, and more. Embed security, compliance and monitoring into DevOps workflows. 

## Community Repositories

- [Extending Falco outputs with Falcosidekick by developer-guy](https://github.com/developer-guy/extending-falco-outputs-with-falcosidekick)
- [Falco workshop by vicenteherrera](https://github.com/vicenteherrera/falco-workshop)
- [Container Runtime Security with Falco by developer-guy](https://github.com/developer-guy/container-runtime-security-with-falco)
- [falco-filebeat-daemonset by Popsiclestick](https://github.com/Popsiclestick/falco-filebeat-daemonset) - Easily deployable daemonset which moves logs from falco with filebeat

## Blogs and Articles

- [Using Falco to monitor outbound traffic for Pods in Kubernetes](https://www.rkatz.xyz/post/2021-04-16-falco-network-monitoring/)
- [Installing and using sysdig falco by Spencer Krum](https://developer.ibm.com/tutorials/installing-and-using-sysdig-falco/)
- [Falco Container Native Security by cloudpirate](https://www.cloudpirate.io/blog/falco-container-native-runtime-security-40608.html)
- [Kubernetes Security monitoring at scale with Sysdig Falco by Skyscanner Engineering](https://medium.com/@SkyscannerEng/kubernetes-security-monitoring-at-scale-with-sysdig-falco-a60cfdb0f67a)
- [Container Host Security Demo - Falco for GitLab 13.2 by GitLab Unfiltered](https://www.youtube.com/watch?v=WxBzBz76FxU)
- [Kubernetes Security With Falco by Gaurav Agarwal](https://medium.com/better-programming/kubernetes-security-with-falco-2eb060d3ae7d)
- [Hunting for Malware with Falco by dlorenc](https://dlorenc.medium.com/hunting-for-malware-with-falco-834b19b398c9)
- [Container runtime security in Kubernetes with Falco by gatesch](https://medium.com/@gatesch/container-runtime-security-in-kubernetes-with-falco-904cd713054a)
- [Getting Started with Falco Runtime Security and Cloud Native Distributed SQL on Google Kubernetes Engine by yugabyte](https://medium.com/yugabyte/getting-started-with-falco-runtime-security-and-cloud-native-distributed-sql-on-google-kubernetes-477b2471535c)
- [Integrating Falco and Your CI/CD Pipeline by ravilach](https://ravilach.medium.com/integrating-falco-and-your-ci-cd-pipeline-870152795282)
- [Deploying Falco to Kubernetes by glentomkowiak](https://medium.com/@glentomkowiak/deploying-falco-to-kubernetes-4d950cf46119)
- [Play by Play Security with Sysdig and Falco by avinash_vjti](https://medium.com/@avinash_vjti/play-by-play-security-with-sysdig-and-falco-22ce397271ed)
- [What is Falco, and how it work with Kubernetes by jihadbenabra](https://jihadbenabra.medium.com/what-is-falco-and-how-it-work-with-kubernetes-44f5dbb985cb)
- [Security Sprint: Falco by terceranexus6](https://dev.to/terceranexus6/security-sprint-falco-e0o)
- [Runtime Security with Falco by Pawan Shankar](https://rancher.com/blog/2020/runtime-security-with-falco)
- [Implementing Runtime Security in Amazon EKS using CNCF Falco by Anand Krishna](https://aws.amazon.com/blogs/containers/implementing-runtime-security-in-amazon-eks-using-cncf-falco/)
- [Security with Falco by Radhika Rajesh](https://dzone.com/articles/security-with-falco)
- [Falco is the First Runtime Security Project to be Accepted into CNCF Incubator by Matt Campbell](https://www.infoq.com/news/2020/01/falco-security-cncf/)
- [An Introduction to Kubernetes Security using Falco by Frederick Fernando](https://www.infracloud.io/blogs/introduction-kubernetes-security-falco/)
- [Kubernetes Audit Log Falco by Pawan Shankar](https://sysdig.com/blog/kubernetes-audit-log-falco/)
- [K3s Sysdig Falco by Dan Papandrea](https://sysdig.com/blog/k3s-sysdig-falco/)
- [Falco Security and Monitoring on RKE Bare Metal Cluster with Rancher by Frank Jogeleit](https://blog.webdev-jogeleit.de/blog/falco-security-and-monitoring-on-rke-bare-metal-cluster-with-rancher)
- [Falco at the edge arm64 by Alex Ellis](https://blog.alexellis.io/falco-at-the-edge-arm64/)
- [Analyze AWS EKS Audit logs with Falco by Ismail Yenigul](https://medium.com/faun/analyze-aws-eks-audit-logs-with-falco-95202167f2e)
- [Sysdig contributes Falco's kernel module, eBPF probe, and libraries to the CNCF by Loris Degioanni](https://sysdig.com/blog/sysdig-contributes-falco-kernel-ebpf-cncf/)
- [Contribution of the drivers and the libraries By Leonardo Di Donato, Leonardo Grasso](https://falco.org/blog/contribution-drivers-kmod-ebpf-libraries/)
- [Runtime security in Azure Kubernetes Service by Eric Carter](https://sysdig.com/blog/runtime-security-in-azure-kubernetes-service/)
- [A story about touching Falco by RyuSA](https://translate.google.com/translate?hl=fr&sl=ja&u=https://zenn.dev/ryusa/scraps/f2807017e0b58c&prev=search&pto=aue)
- [AWS S3 security with CloudTrail and Falco By Alba Ferri](https://sysdig.com/blog/aws-s3-security-cloudtrail-falco/)
- [Detecting MITRE ATT&CK: Privilege escalation with Falco By Stefano Chierici](https://sysdig.com/blog/mitre-privilege-escalation-falco)
- [Exploiting and detecting CVE-2021-25735: Kubernetes validating admission webhook bypass By Stefano Chierici](https://sysdig.com/blog/cve-2021-25735-kubernetes-admission-bypass/)

## Videos

- [Container Runtime Security with Falco by Kubernetes Meetup Tokyo](https://www.youtube.com/watch?v=t-7sq1_wYP4)
- [Sysdig Falco - Open Source Docker Security - WTF my container just spawned a shell by Sysdig](https://www.youtube.com/watch?v=eCC_RFlyxkg)
- [Intro to Falco: Intrusion Detection for Containers - Shane Lawrence, Shopify by Shane Lawrence](https://www.youtube.com/watch?v=rBqBrYESryY)
- [Webinar: Getting started with container runtime security using Falco by Loris Degioanni](https://www.youtube.com/watch?v=eqZxd7VJzek)
- [Kubernetes Master Class - 2020-04-20 - Detecting Anomalous Kubernetes Activity with Falco by Rancher Labs](https://www.youtube.com/watch?v=M3f6-ioY9rs)
- [Unveil hidden malicious processes with Falco in cloud-native environments by Kaizhe Huang](https://securitysandman.com/2021/04/12/falco-ioc-detection-on-k8-wip/)

## Slides

- [Kubernetes Runtime Security with Falco and Sysdig by Jorge Salamero](https://www.cncf.io/wp-content/uploads/2020/08/Kubernetes-Runtime-Security-with-Falco-and-Sysdig.pdf)
- [Getting Started with Runtime Security using Falco by Loris Degioanni](https://www.cncf.io/wp-content/uploads/2020/07/CNCF_-Getting-Started-with-Runtime-Security-using-Falco_2020.09.02.pptx)

## Podcasts

- [Falco by Thomas Labarussias](https://electro-monkeys.fr/?tag=falco)
- [Kubelist Podcast on Falco with @danpopsd](https://www.heavybit.com/library/podcasts/the-kubelist-podcast/ep-9-falco-with-dan-pop-papandrea-of-sysdig/) 

## Interactive Learning

- [Container Runtime Security with Falco by falco](https://katacoda.com/falco/courses/falco/falco)
- [Sysdig Falco: Container security monitoring by mateobur](https://www.katacoda.com/mateobur/scenarios/falco)
- [Blocking security threats with Falco Response Engine by Falco](https://katacoda.com/falco/courses/falco/falco-response-engine)

## IDE and Editor Integrations

- [VS Code plugin](https://github.com/sysdiglabs/vscode-falco) - Falco Rules helpers for VSCode

## Support and Community

### Develop and Contribute

- [Slack](https://kubernetes.slack.com/messages/falco) - Chat with other project developers
- [Developer mailing list](https://lists.cncf.io/g/cncf-falco-dev) - Discuss development issues around the project
- [Contributor of the Month](https://falco.org/docs/contribute/contributor-of-the-month/) - View the contributors of the month

### Learn and Connect

- [Twitter](https://twitter.com/falco_org) - Follow us on Twitter to get the latest news!
- [User mailing list](https://lists.cncf.io/g/cncf-falco-dev/) - Discussion and help from your fellow users
- [StackOverflow](https://stackoverflow.com/questions/tagged/falco) - Practical questions and curated answers
- [Calendar](https://lists.cncf.io/g/cncf-falco-dev/calendar) - Subscribe to the Falco calendar, through this ics feed
