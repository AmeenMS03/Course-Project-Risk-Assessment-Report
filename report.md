# Risk Assessment for Instagram: Social Networking Service
---
### Done By: 
- Ameen Murtaza Siddiqui
- Khalifa Khaled Almansoori
---

Final Project CSE 210 | Abu Dhabi University 

---

## Table of Contents
- Introduction
- Purpose and choice of selection
- Objectives of the company
- Strategies of the company
- Security Policies of the company
- Information Classification
- Asset Identification
- Risk Assessment: Vulnerabilities, Threats, Risks
- IT Security Plan
- Implementation Plan
- Training and Security Awareness Plan
- Maintenance and Configuration
- Lessons Learned

---

## Introduction

Instagram is an American photo and video sharing, social media company which was founded in 2010. Many users are teens and adults, who use the platform for texting, sharing stories, posting photographs, and recording videos.

It is a large company in terms of infrastructure. Due to continuous growth, Instagram expanded its operations across the ocean, building data centers in Europe to keep latency low for a better user experience.

---

## Purpose and Choice of Selection

We chose Instagram because it is one of the most widely used social media apps and has extensive security plans to protect against cyberattacks. Instagram aims to ensure users' security when they trust the platform with their credentials and personal data.

---

## Objectives of the Company

Instagram is trusted by people to store personal data, which is confidential. Many people use Instagram for business purposes, such as advertising, marketing, and growing their business. Instagram also allows for social use, like sharing photos, videos, and updates. This bridges the gap between celebrities, businesses, and their audiences.

---

## Strategies of the Company

Instagram has worked hard to reach its goals, which is why it has grown faster than Facebook and other media companies. Some of the key strategies include:

1. Providing bug-free software for iOS and Android users.
2. Offering customizable settings for businesses on Instagram.
3. Allowing users to share high-definition photos and videos.
4. Developing a direct messaging feature.
5. Enforcing audience-appropriate content.
6. Enabling feedback and error/scam reporting.
7. Releasing software and security updates regularly.

---

## Security Policies of the Company

Security is a top priority for Instagram, as users trust the platform with their personal data and credentials. Key security policies include:

1. Requiring two-factor authentication.
2. Sending email verifications before major actions.
3. Account verification.
4. Friend request and direct message filtering to prevent scams.
5. Providing logs of recent logins for intrusion awareness.
6. Recommending security controls.
7. Reporting accounts or content for moderation.

---

## Information Classification

| Information Type             | Classification Level  |
| ---------------------------- | --------------------- |
| User security activity        | Confidential          |
| Application information       | Confidential          |
| User information              | Restricted            |
| User login logs               | Internal              |
| Credit card details           | Confidential          |
| User activity                 | Public                |
| Active status                 | Restricted            |
| Business information and bio  | Public                |
| History of purchases          | Restricted            |
| User handle and profile pic   | Public                |

---

## Asset Classification

- Authentication database information
- User’s media database
- Server audit logs
- Security firewall
- Asymmetric encryption for direct messaging
- Backups
- Availability of information
- Intrusion detection systems
- Biometric scans for entry

---

## Risk Assessment

| Threat                        | Vulnerability                              | Asset             | Impact                     | Likelihood | Risk                  |
| ----------------------------- | ------------------------------------------ | ----------------- | -------------------------- | ---------- | --------------------- |
| SQL Injection Attack (HIGH)    | User data and passwords can be revealed    | User data         | Loss of confidentiality    | Medium     | Critical              |
| System Overheating (HIGH)      | Improper cooling systems                   | User media database | Database unavailability   | Medium     | High                  |
| DDoS Attack (MEDIUM)           | Availability of Instagram services         | User services      | Instagram unavailability  | High       | Critical              |
| Cameras getting hacked (HIGH)  | Online cameras or unencrypted cameras      | Security systems   | Physical security leaked   | High       | High                  |
| Database firewall bypass (HIGH)| Outdated firewall                          | Firewalls          | Intrusions into database   | Medium     | High                  |
| Human interference (HIGH)      | Low level of security scans                | Biometric scans    | Unauthorized access        | Low        | High                  |

---

## IT Security Plan

### Action Planning

- **System Logs**: Keep logs of users who had access to security controls and track changes made to security settings.
- **Backups**: Regularly back up system files, settings, and confidential data to restore in case of breaches.
- **Access Controls**: Restrict data access based on roles to prevent unauthorized viewing.
- **Risk Assessment**: Perform monthly risk assessments to resolve emerging risks.
- **Training**: Train employees to respond to new threats.
- **Security Patches**: Keep security patches updated to guard against new threats.

---

## Implementation Plan

| Risk               | Implementation                                  |
| ------------------ | ------------------------------------------------|
| SQL Injection       | Input validation, parameterized queries, web-application firewall |
| DDoS Attack         | Security policies, firewall installation, software updates |
| Phishing Emails     | Use spam filters, raise awareness, restrict outside emails |

---

## Training and Security Awareness

1. **Campaigns**: Raise awareness of security risks.
2. **Posters**: Inform employees about recent threats.
3. **Presentations**: Train employees on risk mitigation.
4. **Leaflets**: Distribute information on security advice.
5. **Emails**: Alert users about data breaches.
6. **Meetings**: Discuss security infrastructure.
7. **Quizzes**: Reinforce knowledge with quizzes and competitions.

---

## Security Configuration

- Check for software updates and security patches.
- Remove unnecessary files and settings.
- Enable security controls like auditing and internal firewalls.
- Close unnecessary ports.
- Approve and apply changes with management consent.
- Perform re-assessments to identify new vulnerabilities.

---

## Lessons Learned

We learned that as companies grow, their infrastructure becomes more vulnerable to attacks. Regular security updates and maintenance are critical to prevent data breaches. Understanding security measures helps reduce risks and minimize the impact of future incidents.
