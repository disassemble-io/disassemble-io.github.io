---
title: InsnLine.find - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis](../index.html) / [InsnLine](index.html) / [find](./find.html)

# find

`fun find(vararg queries: `[`InsnQuery`](../../io.disassemble.javanalysis.util.insn.query/-insn-query/index.html)`<out `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.html)`>): `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.html)`>`

Searches for the given queries within [list](list.html).

### Parameters

`queries` - The list of [InsnQuery](../../io.disassemble.javanalysis.util.insn.query/-insn-query/index.html) to search for.

**Return**
A map of matching [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.html), where the key is [InsnQuery.name](../../io.disassemble.javanalysis.util.insn.query/-insn-query/name.html).

