# Muhammed Shekho

Security researcher (`@SYR-ROOT`) focused on Rust, blockchain protocols, and Layer-1
infrastructure. I find and responsibly disclose high-impact vulnerabilities in decentralized
systems: reachable-panic / denial-of-service, consensus liveness (chain halts), and
economic-invariant and governance flaws.

- Website: https://mhd-shekho.com
- Contact: info@mhd-shekho.com
- Advisories crediting me: https://github.com/advisories?query=SYR-ROOT

## Published security advisories

| Advisory | Project | Issue | Credit |
|----------|---------|-------|--------|
| [GHSA-hrqp-8w79-gwgw](https://github.com/advisories/GHSA-hrqp-8w79-gwgw) | rust-nostr | Remote denial of service via a malformed NIP-44 v2 payload (reachable panic) | Reporter |
| [GHSA-xg7c-246g-6qpv](https://github.com/advisories/GHSA-xg7c-246g-6qpv) | rust-nostr | Remote denial of service via a malformed NIP-04 IV (reachable panic) | Reporter (CVE requested) |

Additional advisories across blockchain Layer-1 nodes and Rust infrastructure are currently in
coordinated disclosure and will be listed here once patched and published.

## Focus areas

- Rust safety bugs reachable from untrusted input: panics, out-of-bounds index/slice, integer
  overflow/underflow, unchecked deserialization
- Blockchain node security: consensus liveness and chain-halt classes, P2P and RPC attack
  surfaces, state-sync and snapshot paths
- Economic-invariant and governance flaws in Layer-1 protocols (value conservation, vote
  tallying, reward and bridge accounting)
- Clear, reproducible proof-of-concept development and coordinated disclosure

## How I work

Strictly coordinated disclosure: a private report first, a full root-cause trace with file and
line references, a runnable proof of concept, and a suggested fix, with any public write-up only
after a patch is available.
