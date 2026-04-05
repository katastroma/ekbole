# Ekbole

Pruner interface for [katastroma](https://github.com/katastroma). Defines the
client-facing API for pruner implementations.

A pruner receives provisioned manifests, diffs them against cluster state, and
removes resources no longer in the manifest set.
