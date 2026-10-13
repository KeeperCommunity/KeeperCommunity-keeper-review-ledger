# Keeper review payment ledger

Administrator-managed, public metadata-only payment history for Bitcoin Keeper's independent advisory Claude reviewer. The public design uses branch rulesets available on GitHub Free; repository visibility may remain private until its administrator changes it.

The reviewer remains disabled. Only this README exists on main. The signed orphan `keeper-claude-review-state` branch and `ledger.json` have not been created.

The ledger schema contains PR numbers, immutable head/base SHAs, request/run IDs, status, counters and permanent $3 reservations. It contains no prompts, source code, model output, wallet data or credentials. Existing Claude findings are public comments on the application PR.

Before any payment, complete protected-environment/App setup, reconcile all historical charged/uncertain attempts, verify App-only writes and no-bypass deletion/force-push protections with the actual App token, and obtain independent production security evidence. Preserve every reservation; no fresh allowance or runtime reset is permitted.

Store API, App-private-key and signing-secret values only in the protected reviewer environment and an administrator-controlled secret manager. Never commit them here, including in commit metadata.

Infrastructure PR: https://github.com/KeeperCommunity/bitcoin-keeper/pull/7049
Candidate runbook: https://github.com/KeeperCommunity/bitcoin-keeper/blob/89561308b51f155b5c85d4cb8c41e41a429e0350/.github/CLAUDE_REVIEW.md

No activation, Copilot disable, merge or release is authorized.
