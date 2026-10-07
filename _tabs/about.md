---
# the default layout is 'page'
icon: fas fa-info-circle
order: 4
---

## Hi, I'm Nura 👋

I'm a cloud security professional who reads sign-in logs like mystery
novels.

Someone signs in from home at 9:02. Eleven minutes later, the same
account shows up on the other side of the world. Often there's a
simple explanation. Sometimes the details don't add up. This blog is
about tracing those clues and finding out what happened.

I work across the Microsoft security stack, with Entra ID and
Defender at the core, alongside Intune, Purview, and AI security.

## How I work

Every post follows three steps.

### Break it

![An attacker forging a JWT while you watch](/assets/img/break-it.jpg){: width="280" .right }

I reproduce attacks in a lab to understand how they work, step by
step. That means testing token behavior, authentication flows, and
security controls in a safe environment. Bug bounty work and web
security research keep my instincts sharp.

### Detect it

![You following an attacker's trail through the logs](/assets/img/detect-it.jpg){: width="280" .left }

Every attack leaves clues: an unusual sign-in, an unexpected consent
grant, or an alert in Defender. I follow the trail through the logs
until the activity makes sense.

### Secure it

![You stopping an attacker's forged token at the door](/assets/img/secure-it.jpg){: width="280" .right }

Finding a weakness is only half the work. I look for practical ways
to close it, using controls such as Conditional Access, least
privilege, and correct token validation.

I also help secure AI systems, because AI tools are quickly becoming
part of the attack surface. Securing AI is part of cloud security, too.

## Why I write

Cybersecurity can sound intimidating, and the technical details can
get dense. I explain them in clear, practical language so you can
follow how an attack works, even if you're not a security expert.

Writing also helps me check whether I really understand what I've
found. Every post follows the same path: **break it, detect it,
secure it.**

If you're learning, defending a tenant, or curious about how logins
go wrong, pull up a chair.

First writeup coming soon: **JWT algorithm confusion**, when a server
accepts a token signed with an algorithm it never should have trusted.
