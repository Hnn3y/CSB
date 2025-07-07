# Cybersecurity: Threat Identification and Risk Modeling

## Identifying Threats

When developing a new application, security considerations must begin at the design phase. Threat modeling is a critical technique used to decompose an application into smaller parts (e.g., features or modules) to identify potential threats and vulnerabilities. Without this process, serious flaws might go unnoticed or security resources may be misapplied.

Threats can be discovered by:

- **Ordinary users** who stumble upon flaws accidentally.
- **Script kiddies** using automated tools.
- **Skilled attackers** conducting detailed manual analysis.

### Examples of Threat Impacts

- Unauthorized access due to authorization failure.
- Malicious data poisoning browser cache.
- Sensitive information being intercepted via eavesdropping.

---

## Threat Modeling Frameworks

### STRIDE Threat Model

STRIDE is a framework used to classify different types of cybersecurity threats. The acronym stands for:

| Threat Type              | Description |
|--------------------------|-------------|
| **S – Spoofing**         | Illegally accessing a system using another user’s credentials. |
| **T – Tampering**        | Unauthorized modification of data in storage or transit. |
| **R – Repudiation**      | Users denying their actions due to a lack of audit trails. |
| **I – Information Disclosure** | Exposure of information to unauthorized individuals. |
| **D – Denial of Service**| Making a system or service unavailable temporarily. |
| **E – Elevation of Privilege** | Gaining unauthorized system privileges. |

### DREAD Risk Assessment Model

DREAD is a threat prioritization model used to assess the risk posed by vulnerabilities. It evaluates five dimensions:

| Metric           | Description |
|------------------|-------------|
| **D – Damage Potential**      | How bad would an attack be? |
| **R – Reproducibility**       | How easy is it to reproduce the attack? |
| **E – Exploitability**        | How easy is it to launch the attack? |
| **A – Affected Users**        | How many users would be impacted? |
| **D – Discoverability**       | How easy is it to discover the threat? *(Often set to 10, as all threats are eventually discovered)* |

Each metric is typically scored on a scale of 0–10 to calculate an overall risk score.

---

## Beyond Technology: Multidisciplinary Nature of Cybersecurity

Cybersecurity is not solely a technical challenge. Breaches often result from:

- **Physical threats** – theft, fire, exposed cabling, or environmental damage.
- **Human error** – mistaken emails, lost devices, unsafe password practices.
- **Social engineering** – phishing, malicious attachments, drive-by downloads.
- **Behavioral risks** – insecure social media usage, publishing sensitive workplace content.

### Real-World Human Factor Examples

- A bank employee sends confidential data to the wrong recipient.
- A company laptop with sensitive information is forgotten at an airport.
- Employees use personal email for official communications.
- A disgruntled employee intentionally leaks company secrets.

Strong technical defenses are ineffective without user compliance. **Training and awareness are critical.** Encrypted devices, secure password policies, and user education significantly reduce risk.

---

## Cybersecurity is Everyone’s Responsibility

- **Designers & Developers** must build software with security in mind.
- **Operations & IT Staff** must manage secure networks and systems.
- **Administrators** must ensure systems are updated and properly configured.
- **Users** must follow secure practices and avoid risky behavior.
- **Executives** must champion and fund cybersecurity from the outset.

**In conclusion:** security is a shared responsibility. A robust security culture, combined with technical safeguards, is essential for defending against today’s complex threat landscape.

--- 

## Quiz: Dealing with the human factor

Read the article on avoiding security flaws. Users are often considered to be the weakest link in cyber security. Find, describe, and cite 3 cyber security attacks (that is, actual attacks that have happened, and not attack categories) where a human factor played (describe how) a significant role. Speculate what could have been done to minimize human error in such cases.

--- 