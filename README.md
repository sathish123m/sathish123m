### Sathish Kumar Madhavaram

Backend developer — Node.js, Express, MongoDB/PostgreSQL. Payments, webhooks, and debugging other people's code.

Most of what I know came from things failing in front of me: six months tracing call-record inconsistencies
through JavaScript logs and SQL queries, and a lending platform where a retried payment webhook could credit
a loan twice if the handler got it wrong.

---

**Projects**

**[UniFi](https://github.com/sathish123m/UniFi)** — campus peer-to-peer lending platform
Borrower / provider / admin workflows, JWT + OTP onboarding over university email, role-based access control,
Razorpay test-mode payments with webhook signature verification, Docker Compose for local setup.
`Node · Express · MongoDB · React`

**[VALMONEY](https://github.com/sathish123m/VALMONEY)** — debt payoff planner &nbsp;·&nbsp; [live](https://valmoney.vercel.app)
Snowball and avalanche repayment strategies, amortisation schedules, Prisma migrations with a seeded demo,
49 passing tests.
`Node · Express · Prisma · PostgreSQL · React`

---

**Open source**

- [nodejs/undici #6068](https://github.com/nodejs/undici/pull/6068) — `fetch` could not follow redirects with a
  `MockAgent`. The abort guard in the redirect path was unreachable because the mock controller never exposed
  `aborted`, so the follow-up request was terminated. Fixed the controller and added a regression test.
- [NationalSecurityAgency/ghidra #9984](https://github.com/NationalSecurityAgency/ghidra/pull/9984) — the NE
  loader treated `EntryTableBundle.CONSTANT` (16-bit constants) as segment offsets, producing bogus symbols and
  entry points. They are now recorded separately and exposed as typed enums under `/NE/defines`.

---

📫 sathish085580@gmail.com &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/m-sathish-kumar-66b6b1326/)
