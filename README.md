# gotth-federation

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
