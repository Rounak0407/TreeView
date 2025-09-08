The current version deployed in the MVP is for testing only and allows unlimited supply minting. This was intentional for fast prototyping of the scoring → token emission mechanism.

We will gradually move towards the final production-ready capped token contract.


✅ v0.1 – MVP (Testing Phase)

Unlimited Supply: Tokens are minted every time a score is submitted.

Purpose: Quickly validate MVP logic:

Wallet registration

Score submission

Token emission mechanism

Not for mainnet: This version is unsafe for production since it allows infinite inflation.

🚧 v0.2 – Cap-Enforced Token (Final Design)

Max Supply: xxxxx TREEV tokens .

Minting Rules:

Tokens can only be minted via score submission.

Enforced cap ensures total supply never exceeds max.

Governance Hooks: Only the owner (TreeView backend/DAO later) can submit scores.

🛠️ v0.3 – DAO-Ready Upgrade

Ownership Transfer: Move from single owner to DAO-controlled multi-sig or governance contract.

Dynamic Conversion Rate: POINTS_PER_TOKEN adjustable via governance proposal.

Additional Features:

Vesting for contributors/investors.

Pausable contract (already integrated).

Burnable tokens.