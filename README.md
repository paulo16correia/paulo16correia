# Paulo Correia

Software developer based in Portugal.

> I build software for problems that don't fit inside a template.

Software · AI · Systems · Mobile · Architecture

---

## Currently

**Building** — [Aurora OS](https://github.com/paulo16correia/AuroraOS), a cognitive
kernel reached over MCP · operational software for a construction company ·
a mobile platform for field teams.

**Reading about** — cognitive architectures, distributed systems, and the parts of
iOS and Android that most apps never touch.

**Currently breaking** — Aurora. Deliberately, most of the time.

---

## Selected work

### Aurora OS · `ACTIVE`

**A cognitive operating system.** Not an LLM wrapper: the language model is the
interface and the reasoning layer, reached through MCP. Aurora is the part that
stays when the conversation ends.

```text
User → LLM Client → MCP → Aurora Kernel → MCP result → LLM Client → User
```

The Kernel owns identity, memory, the world model, planning, decisions, policy,
approvals, execution, scheduling, audit and persistence. Swap the model and the
entity remains — that is the whole argument, and it is why the interesting design
work happens below the chat window rather than inside it.

Specification-first, and honest about it: the architecture is frozen at v1.0 across
131 documents — RFCs, architectural laws, ADRs, execution traces and a review gate.
The spec is deliberately a separate repository from the Kernel, so an implementation
cannot quietly redefine the architecture it is meant to follow.

→ **[github.com/paulo16correia/AuroraOS](https://github.com/paulo16correia/AuroraOS)**

### IMAS · `PRIVATE`

**AI-powered operational infrastructure for a construction company.** A progressive
web app carrying quotes, sites, people, documents and decisions. Most of it looks
like ordinary software, which is the point.

The part worth talking about is underneath: every surface reads from one shared
domain core, and the model acts through the same contracts a person does. It cannot
invent a rule the business does not already have.

`Next.js` `TypeScript` `ASP.NET Core` `PostgreSQL` `SignalR` `MCP`

### Vissiona · `PRIVATE`

**Mobile software for people who work on their feet.** Twenty-seven screens for vans,
sites, warehouses and night shifts, for a field operations company.

Tasks and hours record whether or not there is signal and reconcile quietly later.
A shift timer keeps running on the lock screen — a Live Activity on iOS, a persistent
notification on Android — because asking someone in gloves to reopen an app is a
design failure.

`React Native` `Expo` `Supabase` `WebRTC` `Realtime` `Live Activities`

Client software, so the repositories stay closed. The architecture is described on
[pcorreia.pt](https://pcorreia.pt).

---

## How I think about software

> Architecture is a set of decisions.

> If two systems need the same truth, they should not implement it twice.

> Complexity should live somewhere. I prefer knowing exactly where.

> Offline is not an edge case when people work underground.

---

## Contact

[pcorreia.pt](https://pcorreia.pt) · [LinkedIn](https://www.linkedin.com/in/paulofscorreia/) · [paulo@pcorreia.pt](mailto:paulo@pcorreia.pt)
