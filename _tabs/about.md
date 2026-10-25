---
# the default layout is 'page'
icon: fas fa-info-circle
order: 4
---

I'm a cloud security engineer focused on identity. My work centers on
Microsoft Entra ID, Defender and Sentinel: designing access controls,
investigating sign-in activity, and building the log pipelines that make
attacks visible.

This site documents that work as hands-on writeups. Each one covers how an
attack or misconfiguration works, how it shows up in the logs, and how to
close it.

## Focus areas

- **Identity security**: Conditional Access, PIM, least privilege, token and session security
- **Federation and app access**: SAML SSO, OAuth 2.0, OpenID Connect, PKCE
- **Detection and response**: Microsoft Sentinel data connectors, KQL, Defender
- **Azure infrastructure security**: network segmentation, managed identities, Key Vault
- **AI security**: securing AI systems and testing LLM tools against prompt injection

## Selected projects

### Palo Alto VM-Series → Microsoft Sentinel
Deployed a three-interface NGFW in Azure with UDR-forced inspection, source
NAT and least-privilege NSGs. Forwarded native and CEF logs through a
private rsyslog/AMA collector, and traced a single client session from
firewall policy to a parsed Sentinel record.

### Conditional Access modernization in a multi-brand tenant
Led a Conditional Access cleanup and redesign in a production tenant that
serves several brands: retiring overlapping legacy policies, building new
policies on a least-privilege model, and tightening session controls such as
restricting file downloads from unmanaged devices.

### Token theft and Continuous Access Evaluation
Reproduced a token theft attack chain, then built Conditional Access defenses
and confirmed that Continuous Access Evaluation rejected the stolen token in
near real time, with the resource returning a CAE challenge
(`TokenIssuedBeforeRevocationTimestamp`).

### SAML SSO investigations
Resolved federation failures for ServiceNow and Atlassian. Traced one of them to
a platform-level multi-provider SSO setting rather than the provider
configuration, and found that allowing third-party login on the application
side bypasses both SAML and Conditional Access enforcement.

### OAuth 2.0 / OIDC with PKCE
Built authorization code flows with PKCE against Entra ID, then tested the
protections behind them: code verifier mismatch, authorization code replay and
redirect URI mismatch, documenting the AADSTS error each one returns.

### Managed identity and zero standing secrets
Replaced an application's stored secrets with managed identity access to Key
Vault, disabled shared-key access on Storage, and automated user provisioning
with SCIM, working through DNS, Graph API and UPN validation issues on the way.

## Contact

- GitHub: [nuraavazova](https://github.com/nuraavazova)
- LinkedIn: [Nura Avazova](https://www.linkedin.com/in/nura-avazova/)
