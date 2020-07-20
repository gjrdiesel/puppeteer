<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [DOMSnapshot](./puppeteer.protocol.domsnapshot.md) &gt; [LayoutTreeSnapshot](./puppeteer.protocol.domsnapshot.layouttreesnapshot.md) &gt; [paintOrders](./puppeteer.protocol.domsnapshot.layouttreesnapshot.paintorders.md)

## Protocol.DOMSnapshot.LayoutTreeSnapshot.paintOrders property

Global paint order index, which is determined by the stacking order of the nodes. Nodes that are painted together will have the same index. Only provided if includePaintOrder in captureSnapshot was true.

<b>Signature:</b>

```typescript
paintOrders?: integer[];
```