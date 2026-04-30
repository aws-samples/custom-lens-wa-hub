
# SaaS Anywhere Custom Lens

Many SaaS providers are motivated to deploy their solutions in remote customer environments, but they often struggle to manage the operational, security, and cost complexities that arise when the application or data plane resides in accounts they don't directly control. The mindset required for operating a SaaS solution across account boundaries differs significantly from managing a traditional centralized SaaS deployment, particularly in terms of shared responsibility, cross-plane communication, incident response coordination, and cost attribution.

This custom lens is designed to help you assess your SaaS Anywhere architecture and examine all moving parts of managing a distributed SaaS solution across control and remote planes. After careful consideration, it enables you to make informed decisions among various trade-offs when deploying and operating in customer-owned environments.

By using this lens, you'll be better equipped to consider all angles thoroughly, allowing for a more holistic approach to your SaaS Anywhere operations. This custom lens can help you:

* Establishing clear operational boundaries and shared responsibility models between SaaS providers and consumers.
* Making informed decisions about cross-plane communication, security, and access patterns.
* Rethinking trade-offs around data residency, connectivity, and cost optimization in remote deployments.
* Deepening collaboration between SaaS provider and consumer teams for incident response and daily operations.


## Getting started

This is a custom lens for [AWS Well-Architected Tool](https://aws.amazon.com/well-architected-tool/) to assess your SaaS Anywhere architecture — where your SaaS solution's application or data plane is deployed in remote accounts owned by your customers. This lens addresses the unique challenges of the SaaS Anywhere deployment model, including cross-account operations, shared security responsibilities, and distributed cost management, and guides you to implement best practices that scale across multiple remote environments.

Key references:
- [Patterns for Deploying SaaS in Remote Environments](https://aws.amazon.com/blogs/apn/patterns-for-deploying-saas-in-remote-environments/)
- [SaaS Anywhere: When Traditional SaaS Deployment Models Hit Their Limits](https://builder.aws.com/content/31VefASWb7CXdTHUpNB43K8cW5Z/saas-anywhere-when-traditional-saas-deployment-models-hit-their-limits)
- [SaaS Tenant Isolation Strategies](https://docs.aws.amazon.com/whitepapers/latest/saas-tenant-isolation-strategies/implementing-silo-isolation.html)


## Upload the JSON file

- Sign in to the AWS Management Console and open the [AWS Well-Architected Tool console](https://console.aws.amazon.com/wellarchitected)
- Choose **Custom lenses**
- Choose **Create custom lens**
- Upload the [SaaS-Anywhere-Custom-Lens-v0.1.json](./SaaS-Anywhere-Custom-Lens-v0.1.json) from this repo
- Choose **Submit & Preview** to preview the custom lens, or **Submit** to submit the custom lens without previewing.


## Collaborate with your team

Walk through the questions with different functional roles across the six pillars:

- **Operational Excellence** (OPS1–OPS5): Cloud operations teams, SREs, and account managers from both SaaS provider and consumer sides. Focus on remote account management, incident response coordination, monitoring, onboarding automation, and daily operations.
- **Security** (SEC1–SEC5): Security architects, compliance teams, and identity/access management specialists. Focus on shared responsibility models, data encryption, incident investigation, cross-plane communication security, and access governance.
- **Reliability** (REL1–REL2): Platform engineers and reliability teams. Focus on disaster recovery planning for control plane failures and ensuring resilient cross-plane communication.
- **Performance Efficiency** (PERF1–PERF2): Infrastructure and platform engineers. Focus on compute resource selection for remote workloads and scaling mechanisms across account boundaries.
- **Cost Optimization** (COST1–COST3): FinOps teams, finance, and product managers. Focus on cost monitoring across remote accounts, right-sizing opportunities, and data transfer cost optimization.
- **Sustainability** (SUS1): Operations and sustainability teams. Focus on region selection for low-emission deployments and carbon footprint tracking.

The framework is a dynamic working process. While working on security controls, for example, you might revisit your operational model and update it. Some activities across pillars will take place simultaneously, particularly where cross-plane communication patterns affect multiple pillars.


## License

This library is licensed under the MIT-0 License. For more details, please take a look at the [LICENSE](./LICENSE) file.


## Contributing
- Hoi Wing Chan, Senior Technical Account Manager, AWS
- Ronnie Nyaruwabvu, Technical Account Manager, AWS

