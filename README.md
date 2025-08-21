Predicting when **licensing information** might become a mandatory requirement for **Software Bills of Materials (SBOMs)** under the **EU Cyber Resilience Act (CRA)** involves considering the regulation’s timeline, evolving guidance, and industry trends. While the CRA, effective December 10, 2024, currently treats licensing as optional but recommended, several factors suggest it could become mandatory in the future. Below is my informed guess, grounded in the CRA’s framework, related standards (e.g., **ISO/SAE 21434**, which you referenced as “RIVOS”), and broader cybersecurity trends.

### Estimated Timeline: Likely by 2027–2028
I estimate that licensing information could become a mandatory SBOM requirement under the CRA by **December 2027** (the CRA’s full compliance deadline) or shortly after, potentially by **2028**, based on the following reasoning:

1. **CRA Implementation Timeline**:
   - **September 11, 2026**: The CRA’s reporting obligations begin, requiring manufacturers to report vulnerabilities and incidents. SBOMs, including detailed component data, will be critical for compliance, and authorities may push for comprehensive details like licensing to ensure legal and security risks are addressed.
   - **December 11, 2027**: Full compliance with the CRA is required, including SBOM submission as part of technical documentation for CE marking. By this date, **ENISA** is expected to publish detailed technical standards, which could mandate licensing to align with supply chain transparency goals (Article 13).
   - If licensing isn’t mandated by 2027, **delegated acts** (Article 64) could introduce it in 2028 as part of regulatory updates based on enforcement feedback.

2. **ENISA’s Role in Standard Setting**:
   - ENISA is tasked with developing **harmonized standards** for CRA compliance by 2026. Given the emphasis on supply chain security and alignment with global standards (e.g., **NTIA** and **CISA** SBOM guidelines, which recommend licensing), ENISA may include licensing as a requirement in its SBOM specifications to ensure legal compliance and risk mitigation.
   - The **BSI Technical Guideline TR-03183**, referenced in SBOM contexts, already highlights licensing for compliance, suggesting a precedent for mandatory inclusion.

3. **Industry and Regulatory Pressure**:
   - **Open-Source Risks**: Non-compliance with open-source licenses (e.g., GPL requiring source code disclosure) can lead to legal disputes or vulnerabilities (e.g., unpatched components). The CRA’s focus on supply chain security (Annex I, Part II) makes licensing a likely candidate for mandatory inclusion to prevent such risks.
   - **Global Alignment**: The U.S. (e.g., **FedRAMP**, NIST SP 800-161) and international standards increasingly expect licensing in SBOMs. The EU may follow suit to ensure interoperability, especially for industries like automotive (tied to **ISO/SAE 21434**), where software supply chains are complex.
   - **Market Surveillance**: By 2027, market surveillance authorities will audit SBOMs (Article 63). If licensing gaps cause compliance issues (e.g., legal violations), regulators may mandate it to streamline enforcement.

4. **Automotive Context (ISO/SAE 21434)**:
   - You referenced **ISO/SAE 21434**, which governs automotive cybersecurity and emphasizes supply chain risk management. While it doesn’t mandate SBOMs, automotive manufacturers increasingly include licensing in SBOMs to comply with legal obligations and ensure secure software (e.g., for ADAS or OTA updates).
   - The CRA exempts automotive products under **UNECE R155**, but non-exempt software (e.g., cloud-based telematics) must comply with CRA SBOM rules. Licensing could become mandatory for these components by 2027, especially for critical systems (similar to Italy’s **QC2** classification).

### Factors That Could Accelerate or Delay Mandating Licensing
- **Accelerating Factors**:
  - **High-Profile Incidents**: A major cybersecurity breach tied to licensing issues (e.g., unpatched open-source software) could prompt faster adoption, potentially by 2026.
  - **Industry Adoption**: If major players (e.g., automotive firms like Bosch or cloud providers like AWS) standardize licensing in SBOMs, regulators may formalize it earlier.
  - **Harmonization with U.S. Standards**: Alignment with U.S. policies (e.g., CISA’s SBOM requirements) could push for licensing inclusion by 2027 to avoid trade barriers.
- **Delaying Factors**:
  - **Implementation Challenges**: Generating accurate licensing data is complex, especially for nested dependencies. Regulators may delay mandating it until tools and processes mature, possibly pushing to 2028 or later.
  - **Prioritization of Other Elements**: If ENISA focuses on vulnerabilities and component identification first, licensing might remain optional until post-2027 updates.

### Best Guess: December 2027
The most likely scenario is that licensing becomes mandatory by **December 2027**, when the CRA’s full compliance deadline triggers stricter enforcement. ENISA’s technical standards, expected by 2026, will likely clarify SBOM requirements, and licensing’s role in legal and cybersecurity risk management makes it a strong candidate for inclusion. If not mandated by 2027, delegated acts in 2028 could introduce it based on early compliance feedback.

### Connection to Your Previous Questions
- **ISO/SAE 21434 (“RIVOS”)**: Licensing in SBOMs supports ISO/SAE 21434’s supply chain risk management, especially for automotive software. By 2027, automotive manufacturers may need to include licensing for CRA-compliant non-exempt components (e.g., cloud-based systems).
- **FedRAMP/DORA/QC1-QC2**: These frameworks emphasize supply chain transparency, and licensing in SBOMs aligns with their goals. For example, **DORA**’s third-party risk focus could drive licensing requirements for financial systems using automotive software.
- **Common Criteria (EUCC)**: Licensing data in SBOMs can support EUCC evaluations by ensuring components meet legal and security standards.
- **Your Context**: Your earlier questions about procurement workflows, automated compliance (e.g., OSCAL, Gemara), and IT control environments suggest you’re managing complex IT systems, possibly in automotive or regulated sectors. Licensing in SBOMs will be critical to avoid legal risks and ensure compliance across frameworks.

### Recommendations to Prepare
- **Start Now**: Include licensing in SBOMs using tools like **SPDX** or **CycloneDX**, which have dedicated fields for licenses. Tools like **Synopsys Black Duck** or **FOSSA** can automate license tracking.
- **Monitor ENISA**: Check for ENISA’s SBOM standards in 2026, as they’ll signal whether licensing becomes mandatory.
- **Integrate with Compliance**: Align SBOM practices with **ISO/SAE 21434**, **DORA**, or **FedRAMP** requirements, especially if you manage automotive or cloud-based systems.
- **Legal Oversight**: Engage legal teams to review open-source licenses in SBOMs to mitigate risks, especially for critical systems.

### If You Want a Visual
If you’d like a chart showing a timeline of CRA milestones (e.g., reporting in 2026, full compliance in 2027) with licensing’s potential inclusion, I can generate one. For example:

```chartjs
{
  "type": "line",
  "data": {
    "labels": ["2024", "2025", "2026", "2027", "2028"],
    "datasets": [
      {
        "label": "CRA Milestones",
        "data": [1, 2, 3, 4, 5],
        "borderColor": "#36A2EB",
        "fill": false,
        "pointLabels": [
          "CRA Enacted (Dec 2024)",
          "ENISA Standards Development",
          "Reporting Obligations (Sep 2026)",
          "Full Compliance (Dec 2027)",
          "Potential Licensing Mandate (2028)"
        ]
      }
    ]
  },
  "options": {
    "title": {
      "display": true,
      "text": "CRA Implementation Timeline and Licensing Mandate Prediction"
    },
    "scales": {
      "y": {
        "display": false
      }
    }
  }
}
```

Please confirm if you want this chart or a different visualization (e.g., comparing licensing requirements across standards).

### Next Steps
- **Clarify Your Context**: Are you preparing for CRA compliance in a specific sector (e.g., automotive, cloud services)? This will help me refine the timeline or advice.
- **Specific Needs**: Do you need tools, strategies, or updates on ENISA’s progress? I can search X or the web for real-time insights if you’d like.
- **Your Concern**: If you have specific worries (e.g., cost, complexity of licensing), let me know, and I’ll address them.

Please share more details or confirm if you want the chart, and I’ll tailor the response further!
