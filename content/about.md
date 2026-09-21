---
title: "About"
url: "/about/"
summary: "Who I am and what I work on."
ShowToc: false
ShowBreadCrumbs: false
---

I'm Arnob Kumar Saha — a platform and DevOps engineer, and a team lead at
[AppsCode](https://appscode.com), working out of Dhaka, Bangladesh. Most of my
work lives at the layer where Kubernetes stops being a tutorial and starts
being an on-call rotation: operators that run stateful workloads, backup and
restore paths that have to hold under real data, and delivery pipelines a team
can trust at 2am.

## What I work on

**Kubernetes operators and controllers.** Writing CRDs and the reconcile loops
behind them, in Go. The interesting part is never the happy path — it's what
the controller does when the underlying database is half-provisioned, the node
is gone, or someone edited the resource by hand.

**Databases on Kubernetes.** MongoDB especially: provisioning, backup and
restore, and the failure modes that only surface in production. Backup code is
only as good as the last restore you actually tested.

**Packaging and GitOps delivery.** Helm charts and chart tooling, multi-tenant
server-side Helm, and Flux-driven GitOps. Day-to-day this looks like
[`lib-helm`](https://github.com/ArnobKumarSaha/lib-helm),
[`kubepack`](https://github.com/ArnobKumarSaha/kubepack) and a lot of
`HelmRelease` YAML.

**Release engineering.** Tagging, building and shipping across dozens of
repositories without it becoming a full-time job. Automation here pays for
itself in the first month.

**Observability and cost.** Grafana tooling and cluster cost management — the
two questions every platform team eventually gets asked: *is it healthy?* and
*why is it so expensive?*

The glue for all of this is Go and Bash, and a strong preference for tools that
fail loudly rather than quietly.

## Background

I studied at Shahjalal University of Science and Technology, and came to
infrastructure through competitive programming — a few years on
[Codeforces](https://codeforces.com/profile/DarkFloyd) as `DarkFloyd`, peaking
at expert. That habit still shows up in how I debug: reduce the problem until
the failing case is small enough to hold in your head.

## What I write here

Field notes rather than tutorials. What broke, why it broke, and what the fix
actually was — including the wrong turns, because those are usually the useful
part. If a post saves one person an afternoon of debugging, it earned its
place.

## Elsewhere

- GitHub — [@ArnobKumarSaha](https://github.com/ArnobKumarSaha)
- LinkedIn — [arnob-kumar-saha](https://www.linkedin.com/in/arnob-kumar-saha/)
- X/Twitter — [@ArnobKumarSaha](https://twitter.com/ArnobKumarSaha)
- Codeforces — [DarkFloyd](https://codeforces.com/profile/DarkFloyd)
- Email — [arnob@appscode.com](mailto:arnob@appscode.com)
