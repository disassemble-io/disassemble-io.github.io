---
title: CtInsn - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis.insn](../index.html) / [CtInsn](./index.html)

# CtInsn

`open class CtInsn`

A class representing a bytecode instruction.

### Parameters

`owner` - The [CtMethod](#) that this instruction is a part of.

`index` - The index of this instruction in [CtMethod](#).

### Constructors

| [&lt;init&gt;](-init-.html) | `CtInsn(owner: CtMethod, index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`)`<br>A class representing a bytecode instruction. |

### Properties

| [index](--index--.html) | `var index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The index of this instruction in [CtMethod](#). |
| [line](line.html) | `val line: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The line this instruction appears on. |
| [next](next.html) | `var next: `[`CtInsn`](./index.html)`?`<br>The [CtInsn](./index.html) that appears after this instruction. |
| [opcode](opcode.html) | `var opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The opcode of this instruction. |
| [opname](opname.html) | `val opname: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The name of this instruction, appearing within [Mnemonic.OPCODE](#). |
| [owner](owner.html) | `val owner: CtMethod`<br>The [CtMethod](#) that this instruction is a part of. |
| [position](position.html) | `val position: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The position of this instruction within its [CtMethod](#). |
| [previous](previous.html) | `var previous: `[`CtInsn`](./index.html)`?`<br>The [CtInsn](./index.html) that appears before this instruction. |
| [relativeLine](relative-line.html) | `val relativeLine: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The line this instruction appears on, relative to its [CtMethod](#). |
| [verbose](verbose.html) | `val verbose: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>A [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) representation of this instruction. |

### Functions

| [hasNext](has-next.html) | `operator fun hasNext(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the next [CtInsn](./index.html) is valid. |
| [hasPrevious](has-previous.html) | `fun hasPrevious(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the previous [CtInsn](./index.html) is valid. |
| [toString](to-string.html) | `open fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>A basic [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) representation of this instruction. |

### Inheritors

| [ClassMemberInsn](../-class-member-insn/index.html) | `open class ClassMemberInsn : `[`CtInsn`](./index.html)<br>A class representing a class member (field or method instruction). |
| [IncrementInsn](../-increment-insn/index.html) | `class IncrementInsn : `[`CtInsn`](./index.html)<br>A class representing a increment instruction. |
| [IntInsn](../-int-insn/index.html) | `class IntInsn : `[`CtInsn`](./index.html)<br>A class representing a numeric instruction. |
| [InvokeDynamicInsn](../-invoke-dynamic-insn/index.html) | `class InvokeDynamicInsn : `[`CtInsn`](./index.html)<br>A class representing a dynamic method instruction. |
| [JumpInsn](../-jump-insn/index.html) | `class JumpInsn : `[`CtInsn`](./index.html)<br>A class representing a jump instruction. |
| [LdcInsn](../-ldc-insn/index.html) | `class LdcInsn : `[`CtInsn`](./index.html)<br>A class representing a constant instruction. |
| [LookupSwitchInsn](../-lookup-switch-insn/index.html) | `class LookupSwitchInsn : `[`CtInsn`](./index.html)<br>A class representing a lookupswitch instruction. |
| [TableSwitchInsn](../-table-switch-insn/index.html) | `class TableSwitchInsn : `[`CtInsn`](./index.html)<br>A class representing a tableswitch instruction. |
| [TypeInsn](../-type-insn/index.html) | `open class TypeInsn : `[`CtInsn`](./index.html)<br>A class representing a typed instruction. |
| [VarInsn](../-var-insn/index.html) | `class VarInsn : `[`CtInsn`](./index.html)<br>A class representing a local variable instruction. |
| [WideInsn](../-wide-insn/index.html) | `class WideInsn : `[`CtInsn`](./index.html)<br>A class representing a wide instruction. |

