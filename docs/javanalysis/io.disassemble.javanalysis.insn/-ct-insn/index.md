[javanalysis](../../index.md) / [io.disassemble.javanalysis.insn](../index.md) / [CtInsn](./index.md)

# CtInsn

`open class CtInsn`

A class representing a bytecode instruction.

### Parameters

`owner` - The [CtMethod](#) that this instruction is a part of.

`index` - The index of this instruction in [CtMethod](#).

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `CtInsn(owner: CtMethod, index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`)`<br>A class representing a bytecode instruction. |

### Properties

| Name | Summary |
|---|---|
| [index](--index--.md) | `var index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The index of this instruction in [CtMethod](#). |
| [line](line.md) | `val line: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The line this instruction appears on. |
| [next](next.md) | `var next: `[`CtInsn`](./index.md)`?`<br>The [CtInsn](./index.md) that appears after this instruction. |
| [opcode](opcode.md) | `var opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The opcode of this instruction. |
| [opname](opname.md) | `val opname: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The name of this instruction, appearing within [Mnemonic.OPCODE](#). |
| [owner](owner.md) | `val owner: CtMethod`<br>The [CtMethod](#) that this instruction is a part of. |
| [position](position.md) | `val position: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The position of this instruction within its [CtMethod](#). |
| [previous](previous.md) | `var previous: `[`CtInsn`](./index.md)`?`<br>The [CtInsn](./index.md) that appears before this instruction. |
| [relativeLine](relative-line.md) | `val relativeLine: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The line this instruction appears on, relative to its [CtMethod](#). |
| [verbose](verbose.md) | `val verbose: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>A [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) representation of this instruction. |

### Functions

| Name | Summary |
|---|---|
| [hasNext](has-next.md) | `operator fun hasNext(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the next [CtInsn](./index.md) is valid. |
| [hasPrevious](has-previous.md) | `fun hasPrevious(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the previous [CtInsn](./index.md) is valid. |
| [toString](to-string.md) | `open fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>A basic [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) representation of this instruction. |

### Inheritors

| Name | Summary |
|---|---|
| [ClassMemberInsn](../-class-member-insn/index.md) | `open class ClassMemberInsn : `[`CtInsn`](./index.md)<br>A class representing a class member (field or method instruction). |
| [IncrementInsn](../-increment-insn/index.md) | `class IncrementInsn : `[`CtInsn`](./index.md)<br>A class representing a increment instruction. |
| [IntInsn](../-int-insn/index.md) | `class IntInsn : `[`CtInsn`](./index.md)<br>A class representing a numeric instruction. |
| [InvokeDynamicInsn](../-invoke-dynamic-insn/index.md) | `class InvokeDynamicInsn : `[`CtInsn`](./index.md)<br>A class representing a dynamic method instruction. |
| [JumpInsn](../-jump-insn/index.md) | `class JumpInsn : `[`CtInsn`](./index.md)<br>A class representing a jump instruction. |
| [LdcInsn](../-ldc-insn/index.md) | `class LdcInsn : `[`CtInsn`](./index.md)<br>A class representing a constant instruction. |
| [LookupSwitchInsn](../-lookup-switch-insn/index.md) | `class LookupSwitchInsn : `[`CtInsn`](./index.md)<br>A class representing a lookupswitch instruction. |
| [TableSwitchInsn](../-table-switch-insn/index.md) | `class TableSwitchInsn : `[`CtInsn`](./index.md)<br>A class representing a tableswitch instruction. |
| [TypeInsn](../-type-insn/index.md) | `open class TypeInsn : `[`CtInsn`](./index.md)<br>A class representing a typed instruction. |
| [VarInsn](../-var-insn/index.md) | `class VarInsn : `[`CtInsn`](./index.md)<br>A class representing a local variable instruction. |
| [WideInsn](../-wide-insn/index.md) | `class WideInsn : `[`CtInsn`](./index.md)<br>A class representing a wide instruction. |
