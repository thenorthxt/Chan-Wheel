# Chan-Wheel
A chan-native memecoin flywheel combining buybacks, burn, and culture loops.
![Uploading Gemini_Generated_Image_jyqj21jyqj21jyqj.png…]()


What is Chan Wheel?

Chan Wheel is a community-first experiment where token mechanics reinforce cultural persistence.

It’s designed to avoid one-off spikes by continuously recycling value into:

automated buy pressure (buybacks)

supply reduction (burn)

sustained presence (formats, tools, distribution)

The end goal is simple:
a wheel that keeps turning.
EOF

cat > docs/tokenomics.md <<'EOF'

Tokenomics: Chan Wheel Tek

This document describes a generic, implementation-agnostic model.

Objectives

Create a self-reinforcing loop between activity ↔ culture

Convert fee flow into programmatic buybacks

Reduce circulating supply via burn

Preserve long-term presence via recycling budgets

Fee Routing

Let F be total fees accumulated over a period.

A recommended split:

BURN_BUYBACK = 50% of F → buyback then burn

RECYCLE_BUYBACK = 30% of F → buyback then recycle to treasury/presence

OPS_TREASURY = 20% of F → operations, tooling, listings, audits

The split is a parameter. Keep it explicit and on-chain if possible.

Buyback + Burn

Buyback: use routed fees to buy tokens from the open market (or DEX route).
Burn: send a portion of bought tokens to an irrecoverable address.

Benefits:

supply contraction

sustained buy pressure

creates price “memory” and narrative persistence

Buyback + Recycle

Recycling is not “marketing spend” in the traditional sense.

Recycling funds:

community tools (bots, dashboards, content kits)

distribution primitives (format packs, templates)

small bounties (remixes, art, threads)

integrations that make posting easier

The intention: reduce friction to create, remix, and repost.

Parameters (Recommended Defaults)

Buyback cadence: hourly or daily (depending on chain/fees)

Burn ratio: 50–70% of bought tokens (rest to recycle)

Max slippage: defined and bounded

Cooldown / TWAP: avoid predictable MEV patterns
