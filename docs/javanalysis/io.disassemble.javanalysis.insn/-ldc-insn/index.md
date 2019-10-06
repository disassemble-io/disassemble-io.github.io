---
title: LdcInsn - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis.insn](../index.html) / [LdcInsn](./index.html)

# LdcInsn

`class LdcInsn : `[`CtInsn`](../-ct-insn/index.html)

A class representing a constant instruction.

### Parameters

`owner` - The [CtMethod](#) that this instruction is a part of.

`index` - The index of this instruction in [CtMethod](#).

### Constructors

| [&lt;init&gt;](-init-.html) | `LdcInsn(owner: CtMethod, index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`)`<br>A class representing a constant instruction. |

### Properties

| [cst](cst.html) | `val cst: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)<br>The constant value |
| [tag](tag.html) | `val tag: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The type of constant that this instruction is |

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

| [setDouble](set-double.html) | `fun setDouble(value: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Sets this constant to a new [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) value. |
| [setFloat](set-float.html) | `fun setFloat(value: `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Sets this constant to a new [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) value. |
| [setInt](set-int.html) | `fun setInt(value: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Sets this constant to a new [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) value. |
| [setLong](set-long.html) | `fun setLong(value: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Sets this constant to a new [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) value. |
| [setString](set-string.html) | `fun setString(value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Sets this constant to a new [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) value. |
| [setUtf8](set-utf8.html) | `fun setUtf8(value: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Sets this constant to a new [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) value. |

### Inherited Functions

| [hasNext](../-ct-insn/has-next.html) | `operator fun hasNext(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the next [CtInsn](../-ct-insn/index.html) is valid. |
| [hasPrevious](../-ct-insn/has-previous.html) | `fun hasPrevious(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the previous [CtInsn](../-ct-insn/index.html) is valid. |
| [toString](../-ct-insn/to-string.html) | `open fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>A basic [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) representation of this instruction. |

