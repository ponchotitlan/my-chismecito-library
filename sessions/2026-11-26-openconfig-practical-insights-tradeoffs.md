---
type: pitchcraft-session
saved_at: 2026-11-27T00:00:00Z
stage: final
---

# Session: OpenConfig and Vendor-Neutral Automation

## Context
- **Event:** Industry/tech conference, FOSDEM - Network devroom
- **Theme:** Open-source networking and automation
- **Session type:** Talk
- **Audience level:** Practitioners
- **Tone:** Practical and plain-spoken
- **Language:** English
- **Starting point:** Adapting existing draft about OpenConfig vendor-neutrality challenges in brownfield networks
- **Limits:** title 80 chars (actual: 65 chars), abstract 150 words (actual: 188 words)
- **Guardrails:** None
- **Writing style:** Technical Accessible Practitioner (problem-first, concrete takeaways, grounded in real problems)
- **Idea:** Explore OpenConfig promises vs. reality in brownfield networks based on personal network programmability industry experience; cover vendor-neutrality challenges, practical usage in orchestrators, and decision frameworks for adoption
- **Key takeaway:** Specific OpenConfig pitfalls to avoid in brownfield networks and when OpenConfig is (or isn't) the right choice
- **Must mention:** OpenConfig (https://www.openconfig.net/), YANG Suite (https://developer.cisco.com/yangsuite/) as open-source tool for analyzing/testing YANG-based interaction with NETCONF and gRPC
- **Style notes:** Honest, balanced tone about trade-offs; avoid confrontational language about marketing or hype

## Title
- **Status:** locked
- **Current:** OpenConfig and Vendor-Neutral Automation: How Far Can Neutral Go? (65 chars)
- **Rejected:** "OpenConfig for Network Management: Practical Insights and Trade-offs", "OpenConfig in Brownfield Networks: When Vendor-Neutrality Meets Reality", "OpenConfig Beyond the Hype: Practical Pitfalls and When to Use It", "Navigating OpenConfig in Production: Lessons from Brownfield Deployments"

## Abstract
- **Version:** 3
- **Format:** Markdown with links

[OpenConfig](https://www.openconfig.net/) is an open source, community-driven effort to define vendor-neutral YANG data models for network configuration and state, managed over protocols such as gNMI instead of vendor CLIs. The models are public, but each vendor decides whether to adopt them and how far to go, so the promise of one way to automate every device meets a messier reality in brownfield networks.

Based on personal experience managing OpenConfig-related projects, this talk looks at what that means in practice: the maturity of the models and how well different vendors support them. For example, an ACL configuration of Vendor A modelled via OpenConfig might have extra or missing parameters compared with that of Vendor B. We will see on a brief live demo how vendors declare where they depart from the standard models, and how to navigate and test OpenConfig support and those deviations with gNMI and the open source tool [YANG Suite](https://developer.cisco.com/yangsuite/).

If you are a network engineer, SRE or developer automating multi-vendor or legacy networks, you will leave able to evaluate whether your brownfield automation use cases could benefit from OpenConfig, and what would still need vendor-specific handling.

## Final
- **Title:** OpenConfig and Vendor-Neutral Automation: How Far Can Neutral Go? (65 chars)
- **Abstract:** (188 words)

[OpenConfig](https://www.openconfig.net/) is an open source, community-driven effort to define vendor-neutral YANG data models for network configuration and state, managed over protocols such as gNMI instead of vendor CLIs. The models are public, but each vendor decides whether to adopt them and how far to go, so the promise of one way to automate every device meets a messier reality in brownfield networks.

Based on personal experience managing OpenConfig-related projects, this talk looks at what that means in practice: the maturity of the models and how well different vendors support them. For example, an ACL configuration of Vendor A modelled via OpenConfig might have extra or missing parameters compared with that of Vendor B. We will see on a brief live demo how vendors declare where they depart from the standard models, and how to navigate and test OpenConfig support and those deviations with gNMI and the open source tool [YANG Suite](https://developer.cisco.com/yangsuite/).

If you are a network engineer, SRE or developer automating multi-vendor or legacy networks, you will leave able to evaluate whether your brownfield automation use cases could benefit from OpenConfig, and what would still need vendor-specific handling.
