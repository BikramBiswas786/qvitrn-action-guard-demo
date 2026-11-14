# qvitrn-action-guard-demo

Public Action Guard demo. Synthetic paths only. No real secrets.

| Path | Decision | Hedera |
| --- | --- | --- |
| src/receipt.ts on agent/fix-receipt | PROPOSED | [0.0.10015230@1794697917.548764290](https://hashscan.io/testnet/transaction/0.0.10015230@1794697917.548764290) |
| .github/workflows/ci.yml on agent/ci-tweak | HELD | [0.0.10015230@1794697925.149564320](https://hashscan.io/testnet/transaction/0.0.10015230@1794697925.149564320) |
| secrets/deploy.pem on agent/keys | DENIED | [0.0.10015230@1794697926.863270115](https://hashscan.io/testnet/transaction/0.0.10015230@1794697926.863270115) |

Topic `0.0.11345042`. The chain stores the digest and the decision. It does not store source or secret text.
