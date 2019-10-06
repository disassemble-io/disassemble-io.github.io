---
title: InsnQuery - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis.util.insn.query](../index.html) / [InsnQuery](./index.html)

# InsnQuery

`open class InsnQuery<T : `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.html)`>`

A class representing a query.
Used for filtering in lists.

### Constructors

| [&lt;init&gt;](-init-.html) | `InsnQuery()`<br>A class representing a query. Used for filtering in lists. |

### Properties

| [conditions](conditions.html) | `var conditions: `[`ArrayList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-array-list/index.html)`<(`[`T`](index.html#T)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>`<br>The list of conditions that must be met. Used within [InsnQuery.check](check.html) |
| [dist](dist.html) | `var dist: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Sets the distance allowed to be traveled between queries within [io.disassemble.javanalysis.InsnLine.find](../../io.disassemble.javanalysis/-insn-line/find.html). |
| [name](name.html) | `var name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Gives this query a name. Used for putting into a map within [io.disassemble.javanalysis.InsnLine.find](../../io.disassemble.javanalysis/-insn-line/find.html). |

### Functions

| [check](check.html) | `fun check(insn: `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if this [InsnQuery](./index.html)'s conditions are met by the given [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.html). |
| [dist](dist.html) | `fun dist(dist: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`InsnQuery`](./index.html)`<`[`T`](index.html#T)`>`<br>Sets the value of [InsnQuery.dist](dist.html) and returns itself. |
| [name](name.html) | `fun name(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`InsnQuery`](./index.html)`<`[`T`](index.html#T)`>`<br>Sets the value of [InsnQuery.name](name.html) and returns itself. |
| [opcode](opcode.html) | `fun opcode(vararg opcodes: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`InsnQuery`](./index.html)`<`[`T`](index.html#T)`>`<br>Adds a condition to [InsnQuery.conditions](conditions.html) in which the matching [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.html) must be of one of the given opcodes. |
| [plus](plus.html) | `operator fun plus(query: `[`InsnQuery`](./index.html)`<out `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.html)`>): `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`InsnQuery`](./index.html)`<out `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.html)`>>`<br>Creates an array of the two [InsnQuery](./index.html), being the [InsnQuery](./index.html) called from, and the given value. |

### Inheritors

| [CtInsnQuery](../-ct-insn-query/index.html) | `class CtInsnQuery : `[`InsnQuery`](./index.html)`<`[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.html)`>`<br>A class representing a query for an [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.html). Used for filtering in lists. |
| [FieldInsnQuery](../-field-insn-query/index.html) | `class FieldInsnQuery : `[`InsnQuery`](./index.html)`<`[`FieldInsn`](../../io.disassemble.javanalysis.insn/-field-insn/index.html)`>`<br>A class representing a query for an [FieldInsn](../../io.disassemble.javanalysis.insn/-field-insn/index.html). Used for filtering in lists. |
| [IncrementInsnQuery](../-increment-insn-query/index.html) | `class IncrementInsnQuery : `[`InsnQuery`](./index.html)`<`[`IncrementInsn`](../../io.disassemble.javanalysis.insn/-increment-insn/index.html)`>`<br>A class representing a query for an [IncrementInsn](../../io.disassemble.javanalysis.insn/-increment-insn/index.html). Used for filtering in lists. |
| [IntInsnQuery](../-int-insn-query/index.html) | `class IntInsnQuery : `[`InsnQuery`](./index.html)`<`[`IntInsn`](../../io.disassemble.javanalysis.insn/-int-insn/index.html)`>`<br>A class representing a query for an [IntInsn](../../io.disassemble.javanalysis.insn/-int-insn/index.html). Used for filtering in lists. |
| [InvokeDynamicInsnQuery](../-invoke-dynamic-insn-query/index.html) | `class InvokeDynamicInsnQuery : `[`InsnQuery`](./index.html)`<`[`InvokeDynamicInsn`](../../io.disassemble.javanalysis.insn/-invoke-dynamic-insn/index.html)`>`<br>A class representing a query for an [InvokeDynamicInsn](../../io.disassemble.javanalysis.insn/-invoke-dynamic-insn/index.html). Used for filtering in lists. |
| [JumpInsnQuery](../-jump-insn-query/index.html) | `class JumpInsnQuery : `[`InsnQuery`](./index.html)`<`[`JumpInsn`](../../io.disassemble.javanalysis.insn/-jump-insn/index.html)`>`<br>A class representing a query for an [JumpInsn](../../io.disassemble.javanalysis.insn/-jump-insn/index.html). Used for filtering in lists. |
| [LdcInsnQuery](../-ldc-insn-query/index.html) | `class LdcInsnQuery : `[`InsnQuery`](./index.html)`<`[`LdcInsn`](../../io.disassemble.javanalysis.insn/-ldc-insn/index.html)`>`<br>A class representing a query for an [LdcInsn](../../io.disassemble.javanalysis.insn/-ldc-insn/index.html). Used for filtering in lists. |
| [LookupSwitchInsnQuery](../-lookup-switch-insn-query/index.html) | `class LookupSwitchInsnQuery : `[`InsnQuery`](./index.html)`<`[`LookupSwitchInsn`](../../io.disassemble.javanalysis.insn/-lookup-switch-insn/index.html)`>`<br>A class representing a query for an [LookupSwitchInsn](../../io.disassemble.javanalysis.insn/-lookup-switch-insn/index.html). Used for filtering in lists. |
| [MethodInsnQuery](../-method-insn-query/index.html) | `class MethodInsnQuery : `[`InsnQuery`](./index.html)`<`[`MethodInsn`](../../io.disassemble.javanalysis.insn/-method-insn/index.html)`>`<br>A class representing a query for an [MethodInsn](../../io.disassemble.javanalysis.insn/-method-insn/index.html). Used for filtering in lists. |
| [MultiANewArrayInsnQuery](../-multi-a-new-array-insn-query/index.html) | `class MultiANewArrayInsnQuery : `[`InsnQuery`](./index.html)`<`[`MultiANewArrayInsn`](../../io.disassemble.javanalysis.insn/-multi-a-new-array-insn/index.html)`>`<br>A class representing a query for an [MultiANewArrayInsn](../../io.disassemble.javanalysis.insn/-multi-a-new-array-insn/index.html). Used for filtering in lists. |
| [TableSwitchInsnQuery](../-table-switch-insn-query/index.html) | `class TableSwitchInsnQuery : `[`InsnQuery`](./index.html)`<`[`TableSwitchInsn`](../../io.disassemble.javanalysis.insn/-table-switch-insn/index.html)`>`<br>A class representing a query for an [TableSwitchInsn](../../io.disassemble.javanalysis.insn/-table-switch-insn/index.html). Used for filtering in lists. |
| [TypeInsnQuery](../-type-insn-query/index.html) | `class TypeInsnQuery : `[`InsnQuery`](./index.html)`<`[`TypeInsn`](../../io.disassemble.javanalysis.insn/-type-insn/index.html)`>`<br>A class representing a query for an [TypeInsn](../../io.disassemble.javanalysis.insn/-type-insn/index.html). Used for filtering in lists. |
| [VarInsnQuery](../-var-insn-query/index.html) | `class VarInsnQuery : `[`InsnQuery`](./index.html)`<`[`VarInsn`](../../io.disassemble.javanalysis.insn/-var-insn/index.html)`>`<br>A class representing a query for an [VarInsn](../../io.disassemble.javanalysis.insn/-var-insn/index.html). Used for filtering in lists. |
| [WideInsnQuery](../-wide-insn-query/index.html) | `class WideInsnQuery : `[`InsnQuery`](./index.html)`<`[`WideInsn`](../../io.disassemble.javanalysis.insn/-wide-insn/index.html)`>`<br>A class representing a query for an [WideInsn](../../io.disassemble.javanalysis.insn/-wide-insn/index.html). Used for filtering in lists. |

