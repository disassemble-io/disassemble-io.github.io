---
title: VarInsn - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis.insn](../index.html) / [VarInsn](./index.html)

# VarInsn

`class VarInsn : `[`CtInsn`](../-ct-insn/index.html)

A class representing a local variable instruction.

### Parameters

`owner` - The [CtMethod](#) that this instruction is a part of.

`index` - The index of this instruction in [CtMethod](#).

### Constructors

| [&lt;init&gt;](-init-.html) | `VarInsn(owner: CtMethod, index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`)`<br>A class representing a local variable instruction. |

### Properties

| [variable](variable.html) | `var variable: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The variable on the stack. |

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

### Inherited Functions

| [hasNext](../-ct-insn/has-next.html) | `operator fun hasNext(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the next [CtInsn](../-ct-insn/index.html) is valid. |
| [hasPrevious](../-ct-insn/has-previous.html) | `fun hasPrevious(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the previous [CtInsn](../-ct-insn/index.html) is valid. |
| [toString](../-ct-insn/to-string.html) | `open fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>A basic [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) representation of this instruction. |

### Companion Object Functions

| [normalize](normalize.html) | `fun normalize(iter: CodeIterator, index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, op: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Normalizes this instruction by changing iload_1 to iload, etc. |

