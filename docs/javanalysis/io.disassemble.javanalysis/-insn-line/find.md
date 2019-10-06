[javanalysis](../../index.md) / [io.disassemble.javanalysis](../index.md) / [InsnLine](index.md) / [find](./find.md)

# find

`fun find(vararg queries: `[`InsnQuery`](../../io.disassemble.javanalysis.util.insn.query/-insn-query/index.md)`<out `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`>): `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`>`

Searches for the given queries within [list](list.md).

### Parameters

`queries` - The list of [InsnQuery](../../io.disassemble.javanalysis.util.insn.query/-insn-query/index.md) to search for.

**Return**
A map of matching [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.md), where the key is [InsnQuery.name](../../io.disassemble.javanalysis.util.insn.query/-insn-query/name.md).

