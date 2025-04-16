# high-perf-systems-roadmap-

# 🧠 High Performance & Scalable Systems Engineering Roadmap

Welcome to my journey of becoming a high-performance systems engineer.  
I’m focusing on building fast, scalable, and well-designed systems using C++, Rust, and Go.

---

## 🎯 Goal

To learn and apply systems programming, distributed system design, and build real-world projects that are performance-critical and production-grade.

---

## 🗂️ Structure

| Folder | Contents |
|--------|----------|
| `/01_foundations` | Language deep dives + core building blocks (C++, Rust, Go) |
| `/02_projects` | Real projects like loggers, kv stores, task queues |
| `/03_system_design` | System design docs, distributed systems challenges |
| `/notes` | My personal learnings, language comparisons, tips, perf tuning |

---

## 📆 Weekly Progress Tracker

### ✅ Level 1: Foundations (4–6 weeks)

#### Week 1: C++ Basics & Memory Management
- [ ] Write a memory pool allocator
- [ ] Implement a fast logger with file output
- [ ] Read: “C++ Crash Course” (Ch 1–5)

#### Week 2: Rust Ownership & Concurrency
- [ ] Build a multi-threaded logger
- [ ] Learn Rust’s ownership & lifetimes
- [ ] Read: Rust Book – Ch 1–10

#### Week 3: Go Concurrency & HTTP
- [ ] Create a KV store with basic HTTP API
- [ ] Use goroutines & channels
- [ ] Complete [https://go.dev/tour](https://go.dev/tour)

#### Week 4–5: Tools & Tuning
- [ ] Learn `perf`, `valgrind`, `gdb`
- [ ] Benchmark a small project (use `wrk` or `ab`)
- [ ] Write a note: "C++ vs Rust vs Go – Performance Impressions"

---

### ✅ Level 2: System Design & Scalability (6–8 weeks)

#### Topics
- [ ] Threads vs Event Loops vs Async
- [ ] CAP Theorem, Sharding, Partitioning
- [ ] Caching Strategies (write-through, write-back, TTL)
- [ ] Message Queues & Pub/Sub
- [ ] Distributed Consensus (Raft basics)

#### Mini Systems (pick 3–4)
- [ ] 📨 Build a Pub-Sub system (Go or Rust)
- [ ] ⏱️ Design a Distributed Rate Limiter (C++)
- [ ] 💬 Chat Server with multiple clients (Go)
- [ ] 🗃️ Distributed Key-Value Store (Rust)

---

### ✅ Level 3: Real Projects (Ongoing)

| Project | Status | Language | Notes |
|--------|--------|----------|-------|
| High-Throughput Task Queue | [ ] | Rust or Go | Worker pool, retries, metrics |
| Time-Series DB | [ ] | C++ | Query engine, range scans |
| Real-Time Chat | [ ] | Go | Pub-sub with user rooms |
| Log Aggregator | [ ] | Rust | Stream logs from multiple sources |

---

## 📘 Reading List

- [ ] *Designing Data-Intensive Applications* – Martin Kleppmann
- [ ] *Systems Performance* – Brendan Gregg
- [ ] *C++ Crash Course* – Josh Lospinoso
- [ ] *Rust Book* – https://doc.rust-lang.org/book/
- [ ] Gaurav Sen’s YouTube – [Link](https://www.youtube.com/c/GauravSen)

---

## 🧠 Notes To Myself

| Note | Summary |
|------|---------|
| `rust-memory-notes.md` | Ownership, Box, Rc, lifetimes |
| `perf-benchmarking.md` | Using `perf`, `wrk`, `valgrind`, etc |
| `gdb-crash-debug.md` | Basic crash dump debugging |
| `system-design-cheatsheet.md` | Concepts and use-cases |

---

## 💬 Contact

If you’re on a similar journey, open an issue, connect with me, or share ideas!

---
