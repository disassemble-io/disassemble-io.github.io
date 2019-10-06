[javanalysis](../../index.md) / [io.disassemble.javanalysis.util.insn.query](../index.md) / [kotlin.Array](index.md) / [distAll](./dist-all.md)

# distAll

`fun `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`InsnQuery`](../-insn-query/index.md)`<out `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`>>.distAll(dist: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`InsnQuery`](../-insn-query/index.md)`<out `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`>>`

Sets the distance for each of the [InsnQuery](../-insn-query/index.md) in the array.

### Parameters

`dist` - The distance allowed to be traveled between queries within [io.disassemble.javanalysis.InsnLine.find](../../io.disassemble.javanalysis/-insn-line/find.md).

**Return**
The [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html) that this method was called on.

