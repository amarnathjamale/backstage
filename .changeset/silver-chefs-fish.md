---
'@backstage/plugin-kubernetes-backend': minor
'@backstage/plugin-kubernetes-common': minor
'@backstage/plugin-kubernetes-node': minor
---

Added `namespaced` field to custom resources configuration to support cluster-scoped CRDs. Set `namespaced: false` to fetch resources at cluster scope without the namespace path segment.
