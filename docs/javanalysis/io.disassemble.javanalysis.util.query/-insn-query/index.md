[javanalysis](../../index.md) / [io.disassemble.javanalysis.util.query](../index.md) / [InsnQuery](./index.md)

# InsnQuery

`class InsnQuery`

A class representing a query.
Used for filtering in lists.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `InsnQuery()`<br>A class representing a query. Used for filtering in lists. |

### Properties

| Name | Summary |
|---|---|
| [conditions](conditions.md) | `var conditions: `[`ArrayList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-array-list/index.html)`<(`[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>`<br>The list of conditions that must be met. Used within [InsnQuery.check](check.md) |
| [dist](dist.md) | `var dist: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Sets the distance allowed to be traveled between queries within [io.disassemble.javanalysis.InsnLine.find](../../io.disassemble.javanalysis/-insn-line/find.md). |
| [name](name.md) | `var name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Gives this query a name. Used for putting into a map within [io.disassemble.javanalysis.InsnLine.find](../../io.disassemble.javanalysis/-insn-line/find.md). |

### Functions

| Name | Summary |
|---|---|
| [check](check.md) | `fun check(insn: `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if this [InsnQuery](./index.md)'s conditions are met by the given [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.md). |
| [dist](dist.md) | `fun dist(dist: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`InsnQuery`](./index.md)<br>Sets the value of [InsnQuery.dist](dist.md) and returns itself. |
| [int](int.md) | `fun int(operand: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`InsnQuery`](./index.md)<br>Adds a condition to [InsnQuery.conditions](conditions.md) in which the matching [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.md) must be an [IntInsn](../../io.disassemble.javanalysis.insn/-int-insn/index.md) matching the given operand. |
| [name](name.md) | `fun name(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`InsnQuery`](./index.md)<br>Sets the value of [InsnQuery.name](name.md) and returns itself. |
| [opcode](opcode.md) | `fun opcode(vararg opcodes: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`InsnQuery`](./index.md)<br>Adds a condition to [InsnQuery.conditions](conditions.md) in which the matching [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.md) must be of one of the given opcodes. |
