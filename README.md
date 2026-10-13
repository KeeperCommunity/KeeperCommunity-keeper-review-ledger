# Keeper review payment ledger

Private administrator-managed storage for Bitcoin Keeper's independent advisory review payment history.

The reviewer remains disabled. This README initializes the repository only; the signed `keeper-claude-review-state` branch and `ledger.json` have not been created.

Before any payment, complete administrator setup, reconcile and preserve all historical charged/uncertain attempts, and enforce the two branch rulesets required by the reviewed infrastructure.

Store credential and signing-key values only in the protected reviewer environment and an administrator-controlled secret manager.

Infrastructure: https://github.com/KeeperCommunity/bitcoin-keeper/pull/7049
Runbook: https://github.com/KeeperCommunity/bitcoin-keeper/blob/143526a0927ac2d72959218439968a79d210239d/.github/CLAUDE_REVIEW.md
