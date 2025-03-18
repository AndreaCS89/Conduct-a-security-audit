**Overview**

An internal audit was conducted on Botium Toys, a small U.S. business specializing in the development and sale of toys. The primary goal of this audit was to assess the company's security posture, identify vulnerabilities, and evaluate compliance with industry regulations and best practices. The audit focused on existing security controls, potential risks, and adherence to compliance frameworks such as PCI DSS, GDPR, and SOC. Based on the findings, recommendations were provided to improve security measures and reduce risks.

**Scope and Goals:**

During this internal audit we covered the entire security program at Botium Toys, focusing on:

1. Evaluating existing security controls.
2. Assessing compliance with PCI DSS, GDPR, and SOC standards.
3. Identifying risks associated with asset management, access controls, and data protection.
4. Providing recommendations to mitigate vulnerabilities and improve security measures.

**Findings**

The audit revealed several critical security gaps that pose a risk to Botium Toys’ operations. One of the most significant issues is the lack of access control mechanisms, as all employees currently have unrestricted access to internally stored data, including customer and payment information. Additionally, the company does not have an Intrusion Detection System (IDS) in place, making it difficult to detect and respond to security threats in real-time.

Another major concern is the weak password policy, which does not enforce sufficient complexity requirements. Without stronger authentication measures, including multi-factor authentication (MFA), accounts remain vulnerable to unauthorized access. Furthermore, Botium Toys does not have a disaster recovery plan or a structured backup system, meaning that in the event of a system failure or cyberattack, critical business data could be lost.

The audit also found that customer credit card data is not encrypted, leaving sensitive financial information exposed to potential breaches. Additionally, while legacy systems are monitored and maintained, there is no scheduled maintenance plan, which increases the risk of system vulnerabilities over time. Addressing these security gaps is essential to strengthening the company's overall cybersecurity posture.

**Compliance Issues**

The audit determined that Botium Toys is not fully compliant with PCI DSS requirements, which govern the secure handling of credit card transactions. Currently, customer payment data is neither encrypted nor stored in a secure environment, increasing the risk of data breaches. Additionally, the company has no formal access control measures to restrict unauthorized users from viewing or processing credit card information. These gaps could lead to non-compliance penalties and reputational damage if a breach were to occur.

For businesses that handle customer data from the European Union, GDPR compliance is essential. The audit found that Botium Toys does not have a formal data classification and inventory system to manage E.U. customers' personal data effectively. While the company has implemented privacy policies and breach notification procedures, enforcement remains inconsistent. Strengthening GDPR compliance will require better data classification, improved access controls, and enhanced privacy policies to ensure that personal information is properly secured and managed.

The audit also identified compliance issues related to System and Organization Controls (SOC) standards. Currently, there are no defined user access policies, leaving sensitive Personally Identifiable Information (PII) and financial data vulnerable to unauthorized access. While the IT department ensures data integrity and availability, the absence of formal access control policies creates a security risk that could compromise confidentiality. Implementing stronger SOC compliance measures will help reduce these vulnerabilities and ensure better data governance.

**Recommendations**

For PCI DSS compliance, Botium Toys must secure payment data by encrypting transactions and restricting access to payment systems. Compliance can be further improved by segregating payment environments from the rest of the internal network to reduce the risk of data leaks. To enhance GDPR compliance, the company should establish a formal data classification and inventory process to manage personal data effectively. Privacy policies should be updated and enforced through regular employee training to ensure proper data handling practices. Finally, to meet SOC standards, user access policies must be defined and enforced. Employees should be granted access only to the data necessary for their roles, and periodic security audits should be conducted to ensure compliance with best practices.

