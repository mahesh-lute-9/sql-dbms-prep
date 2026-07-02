# Java Backend Developer Prep — A Complete Journey

Daily/weekly log of preparation for Java backend developer roles at top tech 
companies. Covers all CS fundamentals essential for FAANG/product company 
interviews — tracked from day one as I build toward interview-ready depth.

This repo is also meant to double as a revision guide later (for myself, and 
for anyone else following a similar Java backend roadmap) — not just a diary 
of what I did, but a reference for *why* things work the way they do.

## 🎯 Goal
Land a Java backend developer role at a top product-based company as a fresher, 
with strong fundamentals across all CS subjects, querying, problem-solving, 
and backend system design.

## 📖 How to use this repo
- **New here and want the roadmap?** Start with the section below — it lists 
  resources in the order I'm following them.
- **Want subject-wise notes and patterns?** Each subject has its own folder 
  with concept notes and solved problems, with reasoning on *why* each 
  approach works.
- **Want to see active progress?** [`progress.md`](./progress.md) has the 
  daily/weekly log.
- **Once a topic phase wraps up**, a short cheat-sheet summary will be added 
  per subject — common patterns, gotchas, and quick-reference notes.

## 🗺️ Roadmap

### ✅ Month 1 — SQL & DBMS (Active · 8-10 hrs/week)

#### SQL
| Purpose | Resource |
|---|---|
| 🎥 Video / Concept | [Apna College — SQL Playlist](https://www.youtube.com/@ApnaCollegeOfficial) |
| 📖 Theory Reference | [GeeksforGeeks — SQL](https://www.geeksforgeeks.org/sql-tutorial/) |
| 💻 Applied Practice | [DataLemur](https://datalemur.com/) |
| 🔥 Interview Drilling | [LeetCode SQL — Top 50](https://leetcode.com/studyplan/top-sql-50/) |

#### DBMS
| Purpose | Resource |
|---|---|
| 🎥 Video / Concept | [Apna College — DBMS Playlist](https://www.youtube.com/@ApnaCollegeOfficial) |
| 📋 Interview Topic Checklist | [TakeUforward — DBMS Sheet](https://takeuforward.org/) |
| 📖 Deep Dive Reference | [GeeksforGeeks — DBMS](https://www.geeksforgeeks.org/dbms/) |

> 💡 Go topic by topic on TakeUforward's DBMS sheet. Watch Apna College for 
> the concept, use GFG to go deeper, then practice explaining each topic out 
> loud in 2-3 sentences — that's the actual interview skill.

### 🔜 Month 2 — DSA + OS + Computer Networks (Parallel tracks)

#### DSA
| Purpose | Resource |
|---|---|
| 📋 Problem Sheet | [Striver's A2Z DSA Sheet](https://takeuforward.org/) |
| 🔥 Interview Drilling | [LeetCode](https://leetcode.com/) |

> 💡 Order: Arrays → Strings → Two Pointers → Sliding Window → Linked Lists 
> → Stacks/Queues → Binary Search → Trees → Graphs → DP. 
> Target: 100+ solid problems before moving to rare topics.

#### Operating Systems
| Purpose | Resource |
|---|---|
| 🎥 Video / Concept | [Apna College — OS Playlist](https://www.youtube.com/@ApnaCollegeOfficial) |
| 📋 Interview Topic Checklist | [TakeUforward — OS Sheet](https://takeuforward.org/) |
| 📖 Deep Dive Reference | [GeeksforGeeks — OS](https://www.geeksforgeeks.org/operating-systems/) |

> 💡 Key topics: Processes vs Threads, Scheduling algorithms, Deadlocks, 
> Memory management, Paging, Virtual memory, Synchronization primitives.

#### Computer Networks
| Purpose | Resource |
|---|---|
| 🎥 Video / Concept | [Apna College — CN Playlist](https://www.youtube.com/@ApnaCollegeOfficial) |
| 📋 Interview Topic Checklist | [TakeUforward — CN Sheet](https://takeuforward.org/) |
| 📖 Deep Dive Reference | [GeeksforGeeks — CN](https://www.geeksforgeeks.org/computer-network-tutorials/) |

> 💡 Key topics: OSI vs TCP/IP model, HTTP/HTTPS, DNS, TCP vs UDP, 
> Sockets, Load balancing basics, REST principles.

### 🔜 Month 3 — Java + Spring Boot + System Design

#### Java + Spring Boot
- **Foundation already in progress →** [java-learning-journey](https://github.com/mahesh-lute-9/java-learning-journey)
  *(Core Java basics to JVM internals — active repo)*
- [Telusko](https://www.youtube.com/@Telusko) — Spring Boot fundamentals
- [in28Minutes](https://www.youtube.com/@in28minutes) — REST APIs practical
- [Baeldung](https://www.baeldung.com/) — reference while building
- **Goal:** 2 portfolio projects (REST API + JWT auth, DB-backed CRUD app)

#### OOPs
> Already covered in depth via [java-learning-journey](https://github.com/mahesh-lute-9/java-learning-journey) — 
> no separate track needed.

#### System Design Basics
| Purpose | Resource |
|---|---|
| 🎥 HLD Concepts | [Gaurav Sen — YouTube](https://www.youtube.com/@GauravSensei) |
| 📖 Reference | [System Design Primer — GitHub](https://github.com/donnemartin/system-design-primer) |

> 💡 For freshers: focus on LLD (Low Level Design) first — class diagrams, 
> design patterns, OOP-based system design problems like Parking Lot, 
> Library Management. HLD (caching, load balancing, sharding) comes second.

## 📈 Progress
See [`progress.md`](./progress.md) for the daily/weekly log — what's been 
covered, problems solved, and notes on weak areas.

## 🗂️ Repo Structure
```
backend-dev-prep/
├── README.md                    # overview + roadmap + how to use
├── progress.md                  # daily/weekly log
├── sql/
│   ├── joins/
│   ├── aggregations/
│   ├── window-functions/
│   └── subqueries/
├── dbms/
│   └── notes.md
├── os/
│   └── notes.md
├── cn/
│   └── notes.md
├── dsa/
│   ├── arrays/
│   ├── linked-lists/
│   ├── trees/
│   └── dp/
└── projects.md
```

## 📌 Notes
- SQL solutions named for what they solve (e.g. `second-highest-salary.sql`) 
  with a comment on the reasoning — not just the query.
- OS and CN folders contain concept notes structured around interview topics, 
  not textbook chapters.
- DSA solutions include approach notes — the pattern used, not just the code.
- Standalone Spring Boot projects live in their own repos, linked from 
  `projects.md`.

---
*Following along? Feel free to fork this approach or reach out.*
