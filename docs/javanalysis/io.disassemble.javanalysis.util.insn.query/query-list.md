[javanalysis](../index.md) / [io.disassemble.javanalysis.util.insn.query](index.md) / [queryList](./query-list.md)

# queryList

`fun queryList(vararg queries: `[`InsnQuery`](-insn-query/index.md)`<out `[`CtInsn`](../io.disassemble.javanalysis.insn/-ct-insn/index.md)`>): `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`InsnQuery`](-insn-query/index.md)`<out `[`CtInsn`](../io.disassemble.javanalysis.insn/-ct-insn/index.md)`>>`

Creates a typed array of the given instructions.
This function exists because arrayOf(...) does not give  for the InsnQuery type.

### Parameters

`queries` - The list of [InsnQuery](-insn-query/index.md) to give a type to.

**Return**
A typed array of the given instructions.

