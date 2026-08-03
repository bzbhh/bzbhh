<pre>
┌────────────────────────────────────────────────────────────────────────────────┐
│▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒│
│▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒│
│                                                                                │
│   S U A V E   C O N C I E R G E                                                │
│   whatsapp-first concierge for boutique hotels                                 │
│                                                                                │
└────────────────────────────────────────────────────────────────────────────────┘
  <a href="../README.md">back to profile</a>  ·  <a href="https://www.linkedin.com/in/disantobruno/">linkedin</a>
</pre>

Guests text the property on WhatsApp. The bot understands the request in the
guest's language, replies from the hotel's own knowledge base, and hands off to
the on-property team when a human is needed.

## What it does

- **Two-way WhatsApp conversation** — guests reach the property on the channel they already use, no app to install.
- **Multilingual understanding** — language detection per message, typo-tolerant intent matching.
- **Per-hotel knowledge** — each property has its own facts: hours, services, policies, recommendations, FAQ. Not a generic dataset.
- **Request capture** — transport, dining, spa, excursions, housekeeping, information — routed to the right team.
- **Controlled multi-turn dialogue** — when the bot needs more information from the guest, it asks and collects.
- **Staff handoff** — escalation to a human is one decision, with full conversation context attached.
- **Staff cockpit** — supervision, escalation queue, conversation log, kill-switch per hotel.
- **Daily briefing** — automatic summary of the day's activity for the front-desk team.

## Who it's for

Boutique hotels that want a fast, multilingual, on-brand front line on
WhatsApp — without putting a black-box language model between the guest
and the property, and without losing the ability for staff to take over
the conversation at any moment.

## How it's built

- **Bot core** — deterministic intent detection, language detection, risk policy, decision engine, response catalog.
- **Channel** — official WhatsApp Cloud API integration, signed webhook delivery, durable outbound queue.
- **Backend** — Postgres-backed, per-hotel isolation, full audit log on every inbound and outbound message.
- **Privacy** — age-based retention controls on guest data, targeted right-to-erasure tooling.

## What makes it different

- **Deterministic in the live path.** No language model in the conversation runtime — intent matching, decision engine, response catalog. Predictable, debuggable, fast.
- **Durable outbound.** Every outgoing message goes through a queue with provider-side confirmation. No double-sends, no silent drops on retry.
- **Kill switch per hotel.** Staff can stop automatic replies at any moment without taking the system down.
- **Privacy is a feature, not a setting.** Retention windows and right-to-erasure tooling are part of the product, not a legal afterthought.

<pre>
──────────────────────────────────────────────────────────────────────────────────
  <a href="../README.md">back to profile</a>  ·  <a href="../pms/">suave pms</a>  ·  <a href="../xema/">xema</a>  ·  <a href="https://www.linkedin.com/in/disantobruno/">linkedin</a>
──────────────────────────────────────────────────────────────────────────────────
</pre>
