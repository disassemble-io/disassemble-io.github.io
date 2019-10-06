---
title: distAll - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis.util.insn.query](../index.html) / [kotlin.Array](index.html) / [distAll](./dist-all.html)

# distAll

`fun `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`InsnQuery`](../-insn-query/index.html)`<out `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.html)`>>.distAll(dist: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`InsnQuery`](../-insn-query/index.html)`<out `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.html)`>>`

Sets the distance for each of the [InsnQuery](../-insn-query/index.html) in the array.

### Parameters

`dist` - The distance allowed to be traveled between queries within [io.disassemble.javanalysis.InsnLine.find](../../io.disassemble.javanalysis/-insn-line/find.html).

**Return**
The [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html) that this method was called on.

