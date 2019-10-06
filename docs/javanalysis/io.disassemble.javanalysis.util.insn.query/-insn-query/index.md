[javanalysis](../../index.md) / [io.disassemble.javanalysis.util.insn.query](../index.md) / [InsnQuery](./index.md)

# InsnQuery

`open class InsnQuery<T : `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`>`

A class representing a query.
Used for filtering in lists.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `InsnQuery()`<br>A class representing a query. Used for filtering in lists. |

### Properties

| Name | Summary |
|---|---|
| [conditions](conditions.md) | `var conditions: `[`ArrayList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-array-list/index.html)`<(`[`T`](index.md#T)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>`<br>The list of conditions that must be met. Used within [InsnQuery.check](check.md) |
| [dist](dist.md) | `var dist: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Sets the distance allowed to be traveled between queries within [io.disassemble.javanalysis.InsnLine.find](../../io.disassemble.javanalysis/-insn-line/find.md). |
| [name](name.md) | `var name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Gives this query a name. Used for putting into a map within [io.disassemble.javanalysis.InsnLine.find](../../io.disassemble.javanalysis/-insn-line/find.md). |

### Functions

| Name | Summary |
|---|---|
| [check](check.md) | `fun check(insn: `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if this [InsnQuery](./index.md)'s conditions are met by the given [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.md). |
| [dist](dist.md) | `fun dist(dist: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`InsnQuery`](./index.md)`<`[`T`](index.md#T)`>`<br>Sets the value of [InsnQuery.dist](dist.md) and returns itself. |
| [name](name.md) | `fun name(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`InsnQuery`](./index.md)`<`[`T`](index.md#T)`>`<br>Sets the value of [InsnQuery.name](name.md) and returns itself. |
| [opcode](opcode.md) | `fun opcode(vararg opcodes: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`InsnQuery`](./index.md)`<`[`T`](index.md#T)`>`<br>Adds a condition to [InsnQuery.conditions](conditions.md) in which the matching [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.md) must be of one of the given opcodes. |
| [plus](plus.md) | `operator fun plus(query: `[`InsnQuery`](./index.md)`<out `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`>): `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`InsnQuery`](./index.md)`<out `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`>>`<br>Creates an array of the two [InsnQuery](./index.md), being the [InsnQuery](./index.md) called from, and the given value. |

### Inheritors

| Name | Summary |
|---|---|
| [CtInsnQuery](../-ct-insn-query/index.md) | `class CtInsnQuery : `[`InsnQuery`](./index.md)`<`[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`>`<br>A class representing a query for an [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.md). Used for filtering in lists. |
| [FieldInsnQuery](../-field-insn-query/index.md) | `class FieldInsnQuery : `[`InsnQuery`](./index.md)`<`[`FieldInsn`](../../io.disassemble.javanalysis.insn/-field-insn/index.md)`>`<br>A class representing a query for an [FieldInsn](../../io.disassemble.javanalysis.insn/-field-insn/index.md). Used for filtering in lists. |
| [IncrementInsnQuery](../-increment-insn-query/index.md) | `class IncrementInsnQuery : `[`InsnQuery`](./index.md)`<`[`IncrementInsn`](../../io.disassemble.javanalysis.insn/-increment-insn/index.md)`>`<br>A class representing a query for an [IncrementInsn](../../io.disassemble.javanalysis.insn/-increment-insn/index.md). Used for filtering in lists. |
| [IntInsnQuery](../-int-insn-query/index.md) | `class IntInsnQuery : `[`InsnQuery`](./index.md)`<`[`IntInsn`](../../io.disassemble.javanalysis.insn/-int-insn/index.md)`>`<br>A class representing a query for an [IntInsn](../../io.disassemble.javanalysis.insn/-int-insn/index.md). Used for filtering in lists. |
| [InvokeDynamicInsnQuery](../-invoke-dynamic-insn-query/index.md) | `class InvokeDynamicInsnQuery : `[`InsnQuery`](./index.md)`<`[`InvokeDynamicInsn`](../../io.disassemble.javanalysis.insn/-invoke-dynamic-insn/index.md)`>`<br>A class representing a query for an [InvokeDynamicInsn](../../io.disassemble.javanalysis.insn/-invoke-dynamic-insn/index.md). Used for filtering in lists. |
| [JumpInsnQuery](../-jump-insn-query/index.md) | `class JumpInsnQuery : `[`InsnQuery`](./index.md)`<`[`JumpInsn`](../../io.disassemble.javanalysis.insn/-jump-insn/index.md)`>`<br>A class representing a query for an [JumpInsn](../../io.disassemble.javanalysis.insn/-jump-insn/index.md). Used for filtering in lists. |
| [LdcInsnQuery](../-ldc-insn-query/index.md) | `class LdcInsnQuery : `[`InsnQuery`](./index.md)`<`[`LdcInsn`](../../io.disassemble.javanalysis.insn/-ldc-insn/index.md)`>`<br>A class representing a query for an [LdcInsn](../../io.disassemble.javanalysis.insn/-ldc-insn/index.md). Used for filtering in lists. |
| [LookupSwitchInsnQuery](../-lookup-switch-insn-query/index.md) | `class LookupSwitchInsnQuery : `[`InsnQuery`](./index.md)`<`[`LookupSwitchInsn`](../../io.disassemble.javanalysis.insn/-lookup-switch-insn/index.md)`>`<br>A class representing a query for an [LookupSwitchInsn](../../io.disassemble.javanalysis.insn/-lookup-switch-insn/index.md). Used for filtering in lists. |
| [MethodInsnQuery](../-method-insn-query/index.md) | `class MethodInsnQuery : `[`InsnQuery`](./index.md)`<`[`MethodInsn`](../../io.disassemble.javanalysis.insn/-method-insn/index.md)`>`<br>A class representing a query for an [MethodInsn](../../io.disassemble.javanalysis.insn/-method-insn/index.md). Used for filtering in lists. |
| [MultiANewArrayInsnQuery](../-multi-a-new-array-insn-query/index.md) | `class MultiANewArrayInsnQuery : `[`InsnQuery`](./index.md)`<`[`MultiANewArrayInsn`](../../io.disassemble.javanalysis.insn/-multi-a-new-array-insn/index.md)`>`<br>A class representing a query for an [MultiANewArrayInsn](../../io.disassemble.javanalysis.insn/-multi-a-new-array-insn/index.md). Used for filtering in lists. |
| [TableSwitchInsnQuery](../-table-switch-insn-query/index.md) | `class TableSwitchInsnQuery : `[`InsnQuery`](./index.md)`<`[`TableSwitchInsn`](../../io.disassemble.javanalysis.insn/-table-switch-insn/index.md)`>`<br>A class representing a query for an [TableSwitchInsn](../../io.disassemble.javanalysis.insn/-table-switch-insn/index.md). Used for filtering in lists. |
| [TypeInsnQuery](../-type-insn-query/index.md) | `class TypeInsnQuery : `[`InsnQuery`](./index.md)`<`[`TypeInsn`](../../io.disassemble.javanalysis.insn/-type-insn/index.md)`>`<br>A class representing a query for an [TypeInsn](../../io.disassemble.javanalysis.insn/-type-insn/index.md). Used for filtering in lists. |
| [VarInsnQuery](../-var-insn-query/index.md) | `class VarInsnQuery : `[`InsnQuery`](./index.md)`<`[`VarInsn`](../../io.disassemble.javanalysis.insn/-var-insn/index.md)`>`<br>A class representing a query for an [VarInsn](../../io.disassemble.javanalysis.insn/-var-insn/index.md). Used for filtering in lists. |
| [WideInsnQuery](../-wide-insn-query/index.md) | `class WideInsnQuery : `[`InsnQuery`](./index.md)`<`[`WideInsn`](../../io.disassemble.javanalysis.insn/-wide-insn/index.md)`>`<br>A class representing a query for an [WideInsn](../../io.disassemble.javanalysis.insn/-wide-insn/index.md). Used for filtering in lists. |
