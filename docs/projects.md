# Featured Projects

## ClinicChat
**Healthcare Chatbot SaaS Platform**

Spun out of my work at Colorado School of Public Health with support from CU Innovations and the tech transfer office. Multi-tenant platform for healthcare organizations to deploy, manage, and analyze chatbot interactions at scale.

**Features:**
- Chronic condition management workflows
- Eligibility checking and form completion assistance
- Activity monitor (wearable) integrations
- Central CMS for multi-organization content management
- Analytics dashboards for engagement tracking

**Architecture:**
- AWS Control Tower with multi-OU account structure
- CDK infrastructure with cdk-nag compliance scanning
- HIPAA and SOC 2 Type II controls
- Django backend with PostgreSQL

**Role:** Co-founder & CTO

---

## Chat4Heart
**HIPAA-Compliant Health Chatbot**

Text message intervention for cardiovascular health. Scheduled messaging, goal-setting, feedback loops—all through SMS with full HIPAA compliance.

**Stack:** Django • PostgreSQL RDS • AWS EC2/KMS • Vonage API • Apache Airflow  
**Infrastructure:** Linux VM deployment, systemd services, KMS encryption at rest

---

## SCHRA Data Collection Platform
**Clinical Resource Tracking**

Web application for School of Medicine—client intake, resource tracking (syringe kits, referrals), automated reporting on program outcomes.

**Stack:** Django • PostgreSQL • Celery/Redis • JavaScript  
**Deployment:** Dedicated physical server, full Linux administration, IP-based access controls

---

## COVID-19 Vaccination Chatbot
**Multi-Channel Public Health Intervention**

Deployed across multiple FQHCs. Web interface via IBM Watson, SMS via Flask/Twilio. Custom ML classification for response accuracy.

**Stack:** Flask • IBM Watson • Twilio • TensorFlow/Keras • Plotly Dash  
**ML Pipeline:** SVM, Multinomial Naive Bayes, LSTM — model selection via precision/recall/F1 analysis

---

## AWS Infrastructure Portfolio
**Enterprise Cloud Architecture**

Production AWS environments for healthcare applications:

- **Control Tower** setup with organizational units and SCPs
- **CDK deployments** with cdk-nag security scanning
- **ECS services** with ALB, networking, KMS encryption
- **Networking:** VPC design, NACL troubleshooting, Auth0 connectivity
- **Security:** IAM policies, security groups, audit logging