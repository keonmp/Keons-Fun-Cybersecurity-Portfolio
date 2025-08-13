# Controls and Compliance Assessment 

## Case Study

This is based on a fictional company:

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist.
## Scenario
## Controls Assessment Checklist

Does Botium Toys currenly have this control in place? 

| Yes / No / ? | Control | Explanation |
| :-------        |    :---:   | :---     |
| No | Least Privilige | The employees have access to customer data. This has to be changed to reduce the risk of breach. |
| No | Disaster Recovery Plan | At the moment, there is no plan for handling disaster. Implementing this ensures the business continuity. |
| Yes | Firewall | The organization has a firewall to block traffic based on an appropriately defined set of security rules. |
| ? | Password policies | Password policy exists, yet the requirements are considered weak and put the identity management access at risk. |
| Yes | Antivirus | The antivirus software is active and regulary monitored by IT team. |
| No | Backups | This is as same as disaster recovery plan. They are not prepared in the case of breach. They have to implement the backup plan, such as incremental, full, or partial. |
| No | Encryption | This would protect confidentiality of data. |
| No | IDS | This would help IT team to identiy possible intrusions by the threat actors. | 
| Yes | Storefront| Although IT team is not responsible for the management at the storefront, however the organization should have sufficient locks.|
| Yes | CCTV | It is working and functioning. |
| Yes | Fire detection | The organization has these. However, the team should maintain it and establish a plan on how to use it. |

## Compliance Checklist
Does Botium Toys currenly adhrere to this compliance best practice? 

* Payment Card Industry Data Security Standard (PCI DSS)

| Yes/ No / ? | Best Practice | Explanation |
| :---        |    :---:   | :---     |
| No | Authorized users can access to customer's credit card. | At the moment, all employees have access to it which is a bad practice in the business.  |
| No | Credit card is stored in a secure environment. | It is not encrypted and violates the law and regulations. |
| No | Encryption is secured. | No, the encryption has not taken place yet. | 

* GDPR
  
| Yes/ No / ? | Best Practice | Explanation |
| :---        |    :---:   | :---     |
| No | EU customers are kept secured. | The organization does not apply GDPR practice. Thus, it puts them at risk of being fined by the EU government. |
| Yes | Privacy policies are maintained properly.| According to the scenario, it has been enforced by the IT Team members and other staff. |

* System and Organizations Controls 

| Yes/ No / ? | Best Practice | Explanation |
| :---        |    :---:   | :---     |
| No | User access policies are established | Employees have access to internally stored data which means the access policy has not been applied. |
| Yes | Data integrity is consistent, complete, accurate | Data integrity is in place. | 
| No | Data is available to authorized users | Currently, all the employees can access all the data. |

## Recommendations (optional)

After researching Botium Toys's security posture, the analysts agreed that the security practice is far from the expectation. It lacks of protection of confidentialiy of sensitive information. The following are:
1. Least privilege
2. Disaster recovery plan
3. Password policies
4. Encryption
5. Password management system

To address gaps in compliance, Botium needs to implement and establish the policies that can address the following above. Botium also needs to update its assets so the additional control can be identified as soon as possible to improve their security practice.
