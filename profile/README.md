<p align="center">
  <img src="../nerula-icon.jpg" alt="Nerula icon" width="112">
</p>

<h1 align="center">
  <img src="../nerula-wordmark.svg" alt="Nerula" width="340">
</h1>

<p align="center"><strong>Many nodes. One steady orbit.</strong></p>

<p align="center">We’re building Nerula for apps that have outgrown one machine—and for the messy moments that come with running a cluster.</p>

---

> [!NOTE]
> **Early build:** We’re still designing the storage engine, query language, and recovery model. Nerula isn’t ready for production.

## What we care about

- **Plan for the rough days** — Nodes will fail. Recovery belongs in the design from day one.
- **Explain the trade-offs** — Make consistency, availability, and latency clear before they surprise anyone.
- **Be kind to whoever’s on call** — Backups, repair, and useful monitoring matter from the start.
- **Make the query language fit** — Shape it around how Nerula stores and distributes data.

## What we’re working on

- Deciding how data gets split and placed across nodes
- Shaping the query language and the protocol apps will use
- Making confirmed writes survive crashes
- Keeping replicas in sync and helping nodes rejoin safely
- Testing node failures, network hiccups, and heavy loads
- Building drivers, admin tools, and docs people can actually use

## Roadmap

1. **Foundation** — Settle the data model, storage format, query language, and protocol. Prove that writes survive crashes.
2. **Cluster** — Bring nodes together with replication, data placement, and safe recovery after failures.
3. **Day-to-day operations** — Build monitoring, repair, backup, and restore tools. Test how the cluster behaves under pressure.
4. **Developer preview** — Add drivers, examples, and docs; share a preview when the core reliability work is ready.

No dates yet. The order may change as we build and test Nerula.

## Where things stand

Still early. We’re working through the architecture, APIs, and reliability guarantees now. Tests and real code will help decide what sticks.

## Follow along

We’ll share what we’re building, what breaks, and the decisions that shape Nerula as we go.
