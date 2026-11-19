# Learn System Design

A curated learning resource for practicing and mastering **system design**, from fundamentals to real-world architectures.

## Goal

Build a clear, structured path to learn system design by understanding trade-offs and documenting design decisions.

## How to Use This Repo

1. Start with **Fundamentals** to learn core concepts.
2. Go deeper into **Technologies** (Redis, Databases, etc.) when you need tool-level detail.
3. Use **Decision Guides** when choosing between tools in interviews.
4. Use **Case Study** to learn from real-life System Design Case Studies.
5. Capture your own learnings as you go.

## Learning Path

### 1. Fundamentals

| Topic |
|-------|
| [Scalability & Load Balancing](fundamentals/01-scalability-and-load-balancing.md) |
| [Caching](fundamentals/02-caching.md) |
| [Databases (SQL vs NoSQL)](fundamentals/03-databases-sql-vs-nosql.md) |
| [CAP Theorem & Consistency](fundamentals/04-cap-theorem-and-consistency.md) |
| [Message Queues](fundamentals/05-message-queues.md) |

### 2. Technologies

| Technology |
|------------|
| [Redis](technologies/01-redis.md) |
| [PostgreSQL](technologies/02-postgresql.md) |
| [MongoDB](technologies/03-mongodb.md) |

### 3. Decision Guides

| Guide |
|-------|
| [How to Choose a Database](decision-guides/01-how-to-choose-a-database.md) |

### 4. Case Studies

| Case Study |
|------------|
| [GTA VI Distribution & Preload Platform](case%20study/01-gta-vi-distribution.md) |

## Folder Structure

```text
Learn System Design/
├── README.md
├── fundamentals/          # Core concept notes
├── technologies/          # Deep dives on tools
├── decision-guides/       # How to choose between tools
└── case study/            # End-to-end system design case studies
```

## Contributing Notes

- Keep write-ups focused on **why** a decision was made, not only what was built.
- Prefer diagrams for data flow and component interactions.
- Call out assumptions, bottlenecks, and failure modes explicitly.

## Support & Contribute

If you find this resource useful, please **star** the repo.

Have a System Design problem to suggest, or want to contribute? Open an [issue](../../issues). Feedback and contributions are welcome.

Happy designing.
