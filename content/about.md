---
title: "About"
url: "/about/"
summary: "Who I am and what I work on."
ShowToc: false
ShowBreadCrumbs: false
---

I'm Arnob Kumar Saha — platform engineer and team lead at
[AppsCode](https://appscode.com), based in Dhaka, Bangladesh. I build
Kubernetes operators in Go and keep stateful workloads, mostly databases,
alive in production. The interesting part of that job is never the happy path;
it's what the controller does when the database is half-provisioned, the node
is gone, or someone edited the resource by hand.

## What I work on

**Operators for stateful workloads.** CRDs and reconcile loops in Go, with
MongoDB as the main target: provisioning, backup, restore. Backup code is only
as good as the last restore you actually tested.

**Helm packaging and GitOps.** Chart tooling and multi-tenant server-side Helm
— [`lib-helm`](https://github.com/ArnobKumarSaha/lib-helm),
[`kubepack`](https://github.com/ArnobKumarSaha/kubepack) — delivered through
Flux. Plus release automation: tagging, building and shipping across dozens of
repos without it becoming a full-time job.

**Observability and cost.** Grafana tooling and cluster cost management — the
two questions every platform team eventually gets asked: *is it healthy?* and
*why is it so expensive?*

Go and Bash hold the rest together. Before infrastructure I spent a few years
on competitive programming as
[`DarkFloyd`](https://codeforces.com/profile/DarkFloyd), peaking at expert on
Codeforces; it still shows in how I debug — shrink the failing case until it
fits in your head.

## What I write here

Field notes rather than tutorials: what broke, why it broke, and what the fix
actually was, wrong turns included. If a post saves one person an afternoon of
debugging, it earned its place.

## Elsewhere

- GitHub — [@ArnobKumarSaha](https://github.com/ArnobKumarSaha)
- LinkedIn — [arnob-kumar-saha](https://www.linkedin.com/in/arnob-kumar-saha/)
- X — [@ArnobKumarSaha](https://twitter.com/ArnobKumarSaha)
- Codeforces — [DarkFloyd](https://codeforces.com/profile/DarkFloyd)
- Email — [arnobkumarsaha00@gmail.com](mailto:arnobkumarsaha00@gmail.com),
  or [arnob@appscode.com](mailto:arnob@appscode.com) for work
