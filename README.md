## NMAE: MADHUMITHA R
## REG NO:212224240082
# EX - 5 Asset-Oriented Risk Assessment Of Storage Assets In AWS And Azure

---

## Aim

To assess the risks associated with storage assets in AWS and Azure using an asset-oriented approach by identifying vulnerabilities, threats, and implementing appropriate mitigation strategies.

---

## Algorithm

1. Identify storage assets in AWS (e.g., S3, EBS) and Azure (e.g., Blob Storage, Disk Storage).
2. Classify assets based on criticality and sensitivity.
3. Identify potential threats (data breach, unauthorized access, etc.).
4. Identify vulnerabilities (e.g., misconfigured permissions, weak encryption).
5. Assess the risk by calculating likelihood and impact.
6. Prioritize risks based on their severity.
7. Apply appropriate security controls and mitigation strategies.
8. Document and review the risk assessment report.

---

## Procedure

### 1. Identify Storage Assets

- *AWS*: Amazon S3 buckets, EBS volumes, RDS snapshots.
- *Azure*: Azure Blob Storage, Azure Files, Disk Storage.

### 2. Classify Assets

- Label assets as public, private, or confidential based on sensitivity.
- Determine business impact if the asset is compromised.

### 3. Identify Threats

- Examples include:
  - Data breaches
  - Insider threats
  - Ransomware
  - Misconfigured permissions

### 4. Identify Vulnerabilities

- Publicly exposed storage buckets
- Lack of encryption
- Weak IAM policies
- No backup or versioning

### 5. Risk Assessment

- Use a risk matrix to evaluate each asset:
  - *Likelihood*: Low, Medium, High
  - *Impact*: Low, Medium, High
  - *Risk = Likelihood × Impact*

### 6. Prioritize Risks

- Assign risk levels: Critical, High, Medium, Low.
- Focus on high-risk and critical items first.

### 7. Apply Controls

- Enable encryption (at rest and in transit).
- Apply least privilege access.
- Enable logging and monitoring (CloudTrail, Azure Monitor).
- Regularly audit permissions and configurations.

### 8. Document and Review

- Maintain a record of assets, risks, controls applied.
- Schedule periodic reviews and updates.

---

## Outcome

- Identified storage assets in AWS and Azure.
- Evaluated threats, vulnerabilities, and risks associated with each asset.
- Applied appropriate risk mitigation strategies.

---

## Result

Successfully performed asset-oriented risk assessment of storage assets in AWS and Azure and implemented suitable security controls.
