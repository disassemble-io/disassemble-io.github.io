[javanalysis](../../index.md) / [io.disassemble.javanalysis.util.insn.query](../index.md) / [CtInsnQuery](./index.md)

# CtInsnQuery

`class CtInsnQuery : `[`InsnQuery`](../-insn-query/index.md)`<`[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`>`

A class representing a query for an [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.md).
Used for filtering in lists.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `CtInsnQuery()`<br>A class representing a query for an [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.md). Used for filtering in lists. |

### Inherited Properties

| Name | Summary |
|---|---|
| [conditions](../-insn-query/conditions.md) | `var conditions: `[`ArrayList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-array-list/index.html)`<(`[`T`](../-insn-query/index.md#T)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>`<br>The list of conditions that must be met. Used within [InsnQuery.check](../-insn-query/check.md) |
| [dist](../-insn-query/dist.md) | `var dist: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Sets the distance allowed to be traveled between queries within [io.disassemble.javanalysis.InsnLine.find](../../io.disassemble.javanalysis/-insn-line/find.md). |
| [name](../-insn-query/name.md) | `var name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Gives this query a name. Used for putting into a map within [io.disassemble.javanalysis.InsnLine.find](../../io.disassemble.javanalysis/-insn-line/find.md). |

### Inherited Functions

| Name | Summary |
|---|---|
| [check](../-insn-query/check.md) | `fun check(insn: `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if this [InsnQuery](../-insn-query/index.md)'s conditions are met by the given [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.md). |
| [dist](../-insn-query/dist.md) | `fun dist(dist: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`InsnQuery`](../-insn-query/index.md)`<`[`T`](../-insn-query/index.md#T)`>`<br>Sets the value of [InsnQuery.dist](../-insn-query/dist.md) and returns itself. |
| [name](../-insn-query/name.md) | `fun name(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`InsnQuery`](../-insn-query/index.md)`<`[`T`](../-insn-query/index.md#T)`>`<br>Sets the value of [InsnQuery.name](../-insn-query/name.md) and returns itself. |
| [opcode](../-insn-query/opcode.md) | `fun opcode(vararg opcodes: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`InsnQuery`](../-insn-query/index.md)`<`[`T`](../-insn-query/index.md#T)`>`<br>Adds a condition to [InsnQuery.conditions](../-insn-query/conditions.md) in which the matching [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.md) must be of one of the given opcodes. |
| [plus](../-insn-query/plus.md) | `operator fun plus(query: `[`InsnQuery`](../-insn-query/index.md)`<out `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`>): `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`InsnQuery`](../-insn-query/index.md)`<out `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`>>`<br>Creates an array of the two [InsnQuery](../-insn-query/index.md), being the [InsnQuery](../-insn-query/index.md) called from, and the given value. |
