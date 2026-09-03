# gotth-federation

> **Distribution:** GitHub is the public clone and, only if implementation is
> admitted later, the future release endpoint.
> Forgejo remains canonical development and the issue/contribution location.
> See [the distribution contract](docs/distribution.md).


Reserved for reusable federation transport and reconciliation shared by future
GOTTH applications.

## Intended boundary

This project may eventually own ActivityPub transport, strict remote-object and
identity handling, inbox/outbox delivery, signatures, deduplication, bounded
remote fetches, delivery queues, and reconciliation. Consumers retain local
visibility, identity, moderation, blocking, retention, and every decision to
publish an activity outside the application.

## Non-goals

- Making local objects public or federated by default.
- Trusting remote content, redirects, identities, or keys.
- Embedding one application's moderation policy in the transport layer.

## Status

Placeholder only. There is no implementation, API, release, tag, compatibility
promise, or dependency to pin.

## Installation, compatibility, and support

Planned placeholder only. There is no implementation, API, support promise, or
release.

There is nothing to install or import. Do not add this repository as a
dependency.

The repository has no selected license and no long-term support promise.
Versioning, release admission, security reporting, and contribution details are
in [the release policy](docs/RELEASING.md), [security policy](SECURITY.md), and
[contribution guide](CONTRIBUTING.md).
