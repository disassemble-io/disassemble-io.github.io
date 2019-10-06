---
title: TableSwitchInsn - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis.insn](../index.html) / [TableSwitchInsn](./index.html)

# TableSwitchInsn

`class TableSwitchInsn : `[`CtInsn`](../-ct-insn/index.html)

A class representing a tableswitch instruction.

### Parameters

`owner` - The [CtMethod](#) that this instruction is a part of.

`index` - The index of this instruction in [CtMethod](#).

### Constructors

| [&lt;init&gt;](-init-.html) | `TableSwitchInsn(owner: CtMethod, index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`)`<br>A class representing a tableswitch instruction. |

### Properties

| [defaultIndex](default-index.html) | `val defaultIndex: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The default index to internally look at within [javassist.bytecode.CodeIterator](#). |
| [end](end.html) | `val end: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The end index to internally look at within [javassist.bytecode.CodeIterator](#). |
| [high](high.html) | `val high: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The highest value within the [TableSwitchInsn](./index.html). |
| [indices](indices.html) | `val indices: `[`IntArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int-array/index.html)<br>The indices within this [TableSwitchInsn](./index.html). |
| [keys](keys.html) | `val keys: `[`IntArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int-array/index.html)<br>The keys of this [TableSwitchInsn](./index.html). |
| [low](low.html) | `val low: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The lowest value within the [TableSwitchInsn](./index.html). |
| [start](start.html) | `val start: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The start index to internally look at within [javassist.bytecode.CodeIterator](#). |

### Inherited Properties

| [index](../-ct-insn/--index--.html) | `var index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The index of this instruction in [CtMethod](#). |
| [line](../-ct-insn/line.html) | `val line: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The line this instruction appears on. |
| [next](../-ct-insn/next.html) | `var next: `[`CtInsn`](../-ct-insn/index.html)`?`<br>The [CtInsn](../-ct-insn/index.html) that appears after this instruction. |
| [opcode](../-ct-insn/opcode.html) | `var opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The opcode of this instruction. |
| [opname](../-ct-insn/opname.html) | `val opname: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The name of this instruction, appearing within [Mnemonic.OPCODE](#). |
| [owner](../-ct-insn/owner.html) | `val owner: CtMethod`<br>The [CtMethod](#) that this instruction is a part of. |
| [position](../-ct-insn/position.html) | `val position: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The position of this instruction within its [CtMethod](#). |
| [previous](../-ct-insn/previous.html) | `var previous: `[`CtInsn`](../-ct-insn/index.html)`?`<br>The [CtInsn](../-ct-insn/index.html) that appears before this instruction. |
| [relativeLine](../-ct-insn/relative-line.html) | `val relativeLine: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The line this instruction appears on, relative to its [CtMethod](#). |
| [verbose](../-ct-insn/verbose.html) | `val verbose: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>A [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) representation of this instruction. |

### Functions

| [populateIndices](populate-indices.html) | `fun populateIndices(force: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Populates both [keys](keys.html) and [indices](indices.html). |

### Inherited Functions

| [hasNext](../-ct-insn/has-next.html) | `operator fun hasNext(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the next [CtInsn](../-ct-insn/index.html) is valid. |
| [hasPrevious](../-ct-insn/has-previous.html) | `fun hasPrevious(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the previous [CtInsn](../-ct-insn/index.html) is valid. |
| [toString](../-ct-insn/to-string.html) | `open fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>A basic [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) representation of this instruction. |

