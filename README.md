# Hi, I'm Nikhila 👋

## About Me

Cloud and Data Professional with a background in enterprise IT infrastructure (storage administration, VMware, Linux/Unix) and hands-on experience building cloud, data analytics and AI-powered applications.

- About 3 years of prior IT infrastructure experience: EMC SAN/NAS (VNX, VMAX, XtremIO, VPLEX), VMware vSphere, Nutanix, Linux/Unix.
- 30+ hands-on projects across AWS, SQL, Python, Git, cloud analytics, databases, APIs, serverless architectures and CI/CD. Many were NextWork guided projects; the analytics pipeline was self-directed.
- Built three AI applications: a serverless Study Buddy API on AWS (Claude), and two Gemini-based apps in Google AI Studio (MinuteFlow, Dayframe) with prompt-injection testing and human-review safeguards.
- Interested in cloud support and operations, systems administration, application/API support, and AI-enabled workflows.

## Featured Projects

### AWS & Cloud
- **[Serverless Cloud Resume on AWS](https://github.com/USERNAME/serverless-cloud-resume-aws)**: static site on S3 behind CloudFront (Origin Access Control), visitor counter with Lambda, DynamoDB and API Gateway, deployed through GitHub Actions with OIDC federation (no long-term AWS keys).
- **[AWS Three-Tier Web App](https://github.com/USERNAME/aws-three-tier-web-app)**: S3, CloudFront, API Gateway, Lambda and DynamoDB; included CORS troubleshooting across the layers.
- **[Serverless AI Study Buddy API](https://github.com/USERNAME/serverless-ai-study-buddy-api)** (NextWork guided project): Lambda, API Gateway, DynamoDB and Anthropic Claude with summary, quiz and 5-day study-plan modes, input validation, a `/history` endpoint and a Lambda Layer for the SDK.

### Data Analytics
- **[E-Commerce Analytics Pipeline](https://github.com/USERNAME/ecommerce-analytics-pipeline)**
  - *Sprint 1 (local):* SQLite, pandas and Matplotlib. Profiled and cleaned a synthetic 465-row orders dataset (13 duplicates removed, 452 clean rows), with CTEs, window functions and three charts.
  - *Sprint 2 (AWS):* rebuilt on S3, Athena, a Glue crawler, boto3, Lambda and Amazon QuickSight (now Amazon Quick). Automated Athena queries with polling and error handling, using IAM roles instead of stored credentials.
- **[Serverless E-Commerce Analytics Dashboard](https://github.com/USERNAME/serverless-ecommerce-analytics-dashboard)**: Lambda writes order data to DynamoDB and S3; Glue and Athena provide SQL analytics; QuickSight dashboard with KPI cards and date filters.

### AI Applications (Google AI Studio, Gemini; guided projects)
- **[MinuteFlow: AI Meeting Actions](https://github.com/USERNAME/minuteflow-ai-meeting-actions)**: turns meeting notes into summaries, decisions, action items and follow-up emails. Tested with clear, incomplete and adversarial notes; Copy is locked until the user confirms a source review.
- **[Dayframe: AI Day Planner](https://github.com/USERNAME/dayframe-ai-day-planner)**: builds time-blocked schedules around working hours and fixed commitments. Asks clarifying questions for vague tasks, treats embedded instructions as plain text, and has a "Low energy today" mode regression-tested against the original constraints.

### Git & Other Labs
- **[Git & GitHub Workflows](https://github.com/USERNAME/git-github-workflows)**: branching, rebasing, pull requests, merge-conflict resolution, recovery and debugging.
- **[Aurora Web App Integration](https://github.com/USERNAME/aurora-webapp-integration)**: EC2-hosted app connected to Amazon Aurora.
- **[APIs with Lambda + API Gateway](https://github.com/USERNAME/api-gateway-lambda-project)**: serverless REST API.
- Other guided AWS labs (no repos): VPC networking and peering with VPC Flow Logs, IAM least-privilege policies, RDS with QuickSight over a private VPC connection, DynamoDB via the AWS CLI, Docker with Elastic Beanstalk, and an EC2 cloud dev environment.

## Technologies

| Area | Tools |
|---|---|
| Cloud & Infrastructure | AWS (EC2, VPC, S3, CloudFront, Lambda, API Gateway, DynamoDB, RDS/Aurora, Athena, Glue, IAM, CloudWatch, Elastic Beanstalk), VMware, Linux/Unix |
| Programming & Data | Python (pandas, Matplotlib, boto3), SQL (CTEs, window functions), SQLite |
| Analytics & BI | Amazon QuickSight; Power BI (training) |
| DevOps & Tools | Git, GitHub, GitHub Actions, Docker, AWS CLI, CloudShell |
| AI | Google AI Studio (Gemini), Anthropic Claude API, prompt engineering, prompt-injection testing |

## Certifications & Learning

- AWS re/Start Graduate; AWS Cloud Quest: Cloud Practitioner (learning credential, not the AWS Certified Cloud Practitioner exam); AWS Knowledge: Cloud Essentials; AWS Builders Online Series
- Google Data Analytics Certificate; Google Project Management Certificate; IBM Project Management Fundamentals
- Power BI Desktop Bootcamp; AI For Everyone (DeepLearning.AI)
- She Loves Data: Graduate Certificate with Distinction (SLDxDigital), Data Analyst Foundation, Data Engineering Foundation, Excel for Professionals, Introduction to GenAI
- She Loves Data: AI Advantage for Professionals, Fundamentals Masterclass and Boost Camp for Building AI Agents (both with Distinction); 3rd Edition AI Builder Badge

## Currently Exploring

- Connecting AI applications to cloud services and APIs with Python
- Serverless application development and cloud operations
