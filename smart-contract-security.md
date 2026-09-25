# Smart Contract & Security Due Diligence

For EVM projects, inspect deployed contracts on the relevant block explorer.

## Contract Checks

- Is the contract verified?
- Who owns/administers it?
- Can the owner mint tokens?
- Can transfers be paused?
- Can addresses be blacklisted?
- Can fees be changed?
- Can selling be disabled?
- Is the contract upgradeable?
- Who controls the proxy/upgrade authority?
- Are there dangerous privileged functions?
- Is ownership renounced, timelocked or controlled by a multisig?

The source emphasizes that a control should be assessed in context; the existence of a renounced owner, timelock or multisig does not by itself answer every relevant risk question.

## Audit Verification

When a project claims to be audited, verify:

1. The actual audit report.
2. The auditor.
3. The date.
4. The exact contract address/version reviewed.
5. Findings and severity.
6. Whether critical/high findings were fixed.
7. Whether the deployed code matches the reviewed code.

> **An audit is evidence, not a guarantee.**

An audit addresses certain technical risks. It does not guarantee honest founders, sustainable economics, good tokenomics or future security.

## Security Red Flags From the Source

- Unverified smart contract
- Unlimited minting or dangerous privileged functions
- Owner can freeze/blacklist users without a clear legitimate reason
- Owner can arbitrarily change fees
- Upgradeable contract controlled by one wallet without appropriate safeguards
- Unlocked or poorly controlled liquidity
- Fake or unverifiable audit claims

## Safety for Contributors and Job Seekers

Due diligence also protects professional identity and wallet security.

- Verify the company/project and founders.
- Understand the exact role and responsibilities.
- Get compensation and expectations in writing.
- Never pay money to obtain a legitimate role.
- Never share seed phrases, private keys, passwords or recovery codes.
- Be cautious with unknown wallet connections, token approvals and signatures.
- Do not install suspicious software or execute unknown scripts.
