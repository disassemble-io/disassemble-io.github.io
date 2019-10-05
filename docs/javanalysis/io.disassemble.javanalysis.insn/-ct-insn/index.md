[javanalysis](../../index.md) / [io.disassemble.javanalysis.insn](../index.md) / [CtInsn](./index.md)

# CtInsn

`open class CtInsn`

**Author**
Tyler Sedlar

**Since**
5/20/2017

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `CtInsn(owner: CtMethod, index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`)` |

### Properties

| Name | Summary |
|---|---|
| [index](--index--.md) | `var index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [line](line.md) | `val line: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [next](next.md) | `var next: `[`CtInsn`](./index.md)`?` |
| [opcode](opcode.md) | `var opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [opname](opname.md) | `val opname: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [owner](owner.md) | `val owner: CtMethod` |
| [position](position.md) | `val position: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [previous](previous.md) | `var previous: `[`CtInsn`](./index.md)`?` |
| [relativeLine](relative-line.md) | `val relativeLine: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [verbose](verbose.md) | `val verbose: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [hasNext](has-next.md) | `operator fun hasNext(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hasPrevious](has-previous.md) | `fun hasPrevious(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [toString](to-string.md) | `open fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [ClassMemberInsn](../-class-member-insn/index.md) | `open class ClassMemberInsn : `[`CtInsn`](./index.md) |
| [IncrementInsn](../-increment-insn/index.md) | `class IncrementInsn : `[`CtInsn`](./index.md) |
| [IntInsn](../-int-insn/index.md) | `class IntInsn : `[`CtInsn`](./index.md) |
| [InvokeDynamicInsn](../-invoke-dynamic-insn/index.md) | `class InvokeDynamicInsn : `[`CtInsn`](./index.md) |
| [JumpInsn](../-jump-insn/index.md) | `class JumpInsn : `[`CtInsn`](./index.md) |
| [LdcInsn](../-ldc-insn/index.md) | `class LdcInsn : `[`CtInsn`](./index.md) |
| [LookupSwitchInsn](../-lookup-switch-insn/index.md) | `class LookupSwitchInsn : `[`CtInsn`](./index.md) |
| [TableSwitchInsn](../-table-switch-insn/index.md) | `class TableSwitchInsn : `[`CtInsn`](./index.md) |
| [TypeInsn](../-type-insn/index.md) | `open class TypeInsn : `[`CtInsn`](./index.md) |
| [VarInsn](../-var-insn/index.md) | `class VarInsn : `[`CtInsn`](./index.md) |
| [WideInsn](../-wide-insn/index.md) | `class WideInsn : `[`CtInsn`](./index.md) |
