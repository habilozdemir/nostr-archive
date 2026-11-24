# Nostr Public Digital Archive (`npub1c4j0eyejv2z9gy5l646l4h30s8qwcl079f3yrl6h0c2353kaegxqlf9z8m`)

Complete, SHA-256 verified public archive of Nostr events and attached media files retrieved across active and historical relays.

## Archive Contents
- `nostr-public-events.json`: All 516 public signed Nostr events (notes, replies, reactions, bookmarks, relay lists, metadata) in chronological order.
- `nostr-posts-readable.txt`: Human-readable plain text export of all notes and replies (`Kind 1`).
- `media/`: All 11 attached documents and images (PDFs, PNGs, JPGs) preserved locally.
- `MANIFEST.sha256`: Cryptographic SHA-256 checksums for every file in the archive.

## Verification
```bash
shasum -a 256 -c MANIFEST.sha256
```
