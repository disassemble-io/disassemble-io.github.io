---
title: ControlFlowGraph - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis.flow](../index.html) / [ControlFlowGraph](./index.html)

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

| [&lt;init&gt;](-init-.html) | `ControlFlowGraph(flow: ControlFlow, blocks: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<Block>)` |

### Properties

| [blocks](blocks.html) | `val blocks: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<Block>`<br>The list of [ControlFlow.Block](#)s within this graph |
| [dominatorTree](dominator-tree.html) | `val dominatorTree: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<Node>`<br>Retrieves the dominator tree of this [ControlFlowGraph](./index.html). |
| [flow](flow.html) | `val flow: ControlFlow`<br>The [ControlFlow](#) for this graph to represent |
| [postDominatorTree](post-dominator-tree.html) | `val postDominatorTree: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<Node>`<br>Retrieves the post dominator tree of this [ControlFlowGraph](./index.html). |

### Functions

| [findBlockByIndex](find-block-by-index.html) | `fun findBlockByIndex(index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): Block?`<br>Gets the block within this graph matching the given index. |

