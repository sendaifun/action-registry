# Solana Action Registry 

This is a registry of Solana Actions supported by the Solana Agent Kit. 

- [Solana Agent Kit](https://github.com/sendaifun/solana-agent-kit)
- [Solana Actions](https://solana.com/actions)
- [Get your action supported](https://github.com/sendaifun/action-registry/issues/new)

## Solana Actions

Using Solana Actions, you can turn any transaction into a blockchain link that can be shared anywhere on the internet — no third party application required. Request a payment in a text message. Vote on governance in a chatroom. Buy an NFT on social media. It’s all possible.

## Solana Agent Kit

[Solana Agent Kit](https://github.com/sendaifun/solana-agent-kit), connect any ai agents to solana protocols.

All actions in this registry are supported by the Solana Agent Kit. 

## The Action Interface

```typescript
interface Action {
  name: string;
  similes: string[];
  description: string;
  examples: ActionExample[][];
  handler: Handler;
  validate: Validator;
}
```

This was taken/inspired from [Eliza](https://elizaos.github.io/eliza/docs/core/actions/)

