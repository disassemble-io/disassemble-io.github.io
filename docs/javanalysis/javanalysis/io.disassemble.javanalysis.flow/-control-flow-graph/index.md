[javanalysis](../../index.md) / [io.disassemble.javanalysis.flow](../index.md) / [ControlFlowGraph](./index.md)

# ControlFlowGraph

`class ControlFlowGraph`

**Author**
Tyler Sedlar

**Since**
5/20/2017

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ControlFlowGraph(flow: ControlFlow, blocks: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<Block>)` |

### Properties

| Name | Summary |
|---|---|
| [blocks](blocks.md) | `val blocks: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<Block>` |
| [dominatorTree](dominator-tree.md) | `val dominatorTree: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<Node>` |
| [flow](flow.md) | `val flow: ControlFlow` |
| [postDominatorTree](post-dominator-tree.md) | `val postDominatorTree: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<Node>` |

### Functions

| Name | Summary |
|---|---|
| [findBlockByIndex](find-block-by-index.md) | `fun findBlockByIndex(index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): Block?` |
