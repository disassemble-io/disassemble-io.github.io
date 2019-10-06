---
title: queryList - javanalysis
---

[javanalysis](../index.html) / [io.disassemble.javanalysis.util.insn.query](index.html) / [queryList](./query-list.html)

# queryList

`fun queryList(vararg queries: `[`InsnQuery`](-insn-query/index.html)`<out `[`CtInsn`](../io.disassemble.javanalysis.insn/-ct-insn/index.html)`>): `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`InsnQuery`](-insn-query/index.html)`<out `[`CtInsn`](../io.disassemble.javanalysis.insn/-ct-insn/index.html)`>>`

Creates a typed array of the given instructions.
This function exists because arrayOf(...) does not give  for the InsnQuery type.

### Parameters

`queries` - The list of [InsnQuery](-insn-query/index.html) to give a type to.

**Return**
A typed array of the given instructions.

