<pre>
┌────────────────────────┐  ┌────────────────────────┐  ┌────────────────────────┐
│▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓│  │▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒│  │░░░░░░░░░░░░░░░░░░░░░░░░│
│▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓│  │▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒│  │░░░░░░░░░░░░░░░░░░░░░░░░│
│                        │  │                        │  │                        │
│   <a href="./pms/">S U A V E</a>            │  │   <a href="./concierge/">S U A V E</a>            │  │   <a href="./xema/">X E M A</a>              │
│   <a href="./pms/">P M S</a>                │  │   <a href="./concierge/">C O N C I E R G E</a>    │  │   <a href="./xema/">A G E N T   L A B</a>    │
│                        │  │                        │  │                        │
└────────────────────────┘  └────────────────────────┘  └────────────────────────┘

══════════════════════════════════════════════════════════════════════════════════
  B R U N O   D I   S A N T O
  founder and engineer  ·  hotel operating systems  ·  paris
  <a href="https://www.linkedin.com/in/disantobruno/">linkedin.com/in/disantobruno</a>
══════════════════════════════════════════════════════════════════════════════════
</pre>

I build the software boutique hotels run their day on — reservations, front desk,
folios, payments, guest messaging — plus the tooling I use to build it safely.

## Building

- [**SUAVE PMS**](./pms/) — hotel operating system for 8 to 25 room properties.
  Reservations, front desk, housekeeping, folios, payments, rates, night audit.
- [**SUAVE Concierge**](./concierge/) — WhatsApp-first concierge. Guests text the
  property, the system answers in their language, staff take over on demand.
- [**XEMA**](./xema/) — local agent lab. Bounded execution, repository guards,
  audit trails, explicit human approval gates.

Production code is private. I don't publish customer data, credentials, provider
configuration, or internal architecture to make a profile look busier.

## Engineering

```
frontend    React · TypeScript · dense operational UI · desktop-first
backend     Postgres · row-level security · RPC boundaries · typed service layers
security    fail-closed auth · least privilege · per-tenant isolation
payments    Stripe · folios · reservation ledgers · refunds and voids
agents      local-first orchestration · bounded subprocesses · approval gates
quality     Vitest · Playwright · CI gates · adversarial review
```

Software that survives real operations, not demo screenshots.

## How I work

Five questions, always in this order, before anything ships:

1. What should the user be able to do?
2. What must be true in the data after the action?
3. What can fail, and how does it fail safely?
4. What belongs in the UI, the service layer, the database, the audit log?
5. What evidence proves it works on the real path?

The last one is the one people skip. A green test suite proves the repository's
gates pass. It does not prove deployment, delivery, or that a receptionist can
close a folio at 2am without losing money.

<pre>
──────────────────────────────────────────────────────────────────────────────────
  <a href="https://www.linkedin.com/in/disantobruno/">linkedin</a>  ·  <a href="./pms/">suave pms</a>  ·  <a href="./concierge/">suave concierge</a>  ·  <a href="./xema/">xema</a>
──────────────────────────────────────────────────────────────────────────────────
</pre>
