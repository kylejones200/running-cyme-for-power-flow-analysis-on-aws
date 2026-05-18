# Running CYME for Power Flow Analysis on AWS

Published: 2025-02-19
Medium: [https://medium.com/@kyle-t-jones/running-cyme-for-power-flow-analysis-on-aws-4839bb66b038](https://medium.com/@kyle-t-jones/running-cyme-for-power-flow-analysis-on-aws-4839bb66b038)

## Business context

Power utilities use tools like CYME for power flow analysis, short-circuit studies, and grid optimization. CYME, developed by Eaton, is a widely used power system analysis software capable of modeling distribution and transmission networks. However, running CYME on local workstations can be resource-intensive, limiting scalability and flexibility.

Utilities and consultants can run CYME efficiently on AWS. This lets them scale computational resources as needed while integrating cloud-based storage, automation, and analytics. This post explores how to deploy CYME on AWS for power flow analysis, covering architecture, EC2 configurations, storage options, automation, and cost optimization strategies.

Unable to execute JavaScript.<figcaption>Song Zhang, PhD, from AWS describing how this process works.</figcaption>

## About

Place the code for this article in this repository.
The original article export is saved as `article.md`.

## Files

Add your `.ipynb`, `.py`, `.yaml`, `.js`, `.ts`, or other project files here.

## Disclaimer

Educational/demo code only. Not financial, safety, or engineering advice. Use at your own risk. Verify results independently before any production or operational use.

## License

MIT — see [LICENSE](LICENSE).