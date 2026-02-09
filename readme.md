While Azure Static Web Apps (SWA) is a fantastic tool for "getting it done fast," the S3 + CloudFront + OAC architecture is the industry standard for professional-scale applications. 

This is the technical architecture of companies like Netflix, Airbnb, or Slack, they use this exact pattern (S3 origins behind CloudFront distributions) for their static assets and frontend apps.

By doing this, I am no longer just a "Web Developer"—I am acting as a Cloud Engineer.

Azure SWA says: "Give me your code, I'll figure it out."

AWS S3 + CloudFront says: "I have designed a globally distributed, secure, and automated delivery pipeline."


This project can be divided to few phases below.
1. Create IAM user.
2. Set up S3 bucket.
3. Set up CloudFront (CDN)
4. Set up Domain & SSL (Cloudflare + AWS)
5. Automation (CI/CD)
6. Infrastructure-as-Code (IaC)
