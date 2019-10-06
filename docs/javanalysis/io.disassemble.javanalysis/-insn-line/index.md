[javanalysis](../../index.md) / [io.disassemble.javanalysis](../index.md) / [InsnLine](./index.md)

# InsnLine

`class InsnLine`

A structure representing a line of code.
Acts as a [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html) of [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.md).

### Parameters

`line` - The line that the accompanied [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.md) appear on.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `InsnLine(line: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`)`<br>A structure representing a line of code. Acts as a [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html) of [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.md). |

### Properties

| Name | Summary |
|---|---|
| [line](line.md) | `val line: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The line that the accompanied [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.md) appear on. |
| [list](list.md) | `val list: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`>`<br>The [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.md) that appear on this line. |

### Functions

| Name | Summary |
|---|---|
| [add](add.md) | `fun add(insn: `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Adds the given [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.md) to this line. |
| [find](find.md) | `fun find(vararg queries: `[`InsnQuery`](../../io.disassemble.javanalysis.util.insn.query/-insn-query/index.md)`<out `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`>): `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`>`<br>Searches for the given queries within [list](list.md). |
