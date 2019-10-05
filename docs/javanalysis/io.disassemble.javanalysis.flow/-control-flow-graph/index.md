[javanalysis](../../index.md) / [io.disassemble.javanalysis.flow](../index.md) / [ControlFlowGraph](./index.md)

# ControlFlowGraph

`class ControlFlowGraph`

### Parameters

`flow` - The [ControlFlow](#) for this graph to represent

`blocks` - The list of [ControlFlow.Block](#)s within this graph

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
| [blocks](blocks.md) | `val blocks: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<Block>`<br>The list of [ControlFlow.Block](#)s within this graph |
| [dominatorTree](dominator-tree.md) | `val dominatorTree: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<Node>`<br>Retrieves the dominator tree of this [ControlFlowGraph](./index.md). |
| [flow](flow.md) | `val flow: ControlFlow`<br>The [ControlFlow](#) for this graph to represent |
| [postDominatorTree](post-dominator-tree.md) | `val postDominatorTree: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<Node>`<br>Retrieves the post dominator tree of this [ControlFlowGraph](./index.md). |

### Functions

| Name | Summary |
|---|---|
| [findBlockByIndex](find-block-by-index.md) | `fun findBlockByIndex(index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): Block?`<br>Gets the block within this graph matching the given index. |
