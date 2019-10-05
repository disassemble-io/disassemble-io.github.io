[javanalysis](../../index.md) / [io.disassemble.javanalysis.insn](../index.md) / [VarInsn](index.md) / [normalize](./normalize.md)

# normalize

`fun normalize(iter: CodeIterator, index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, op: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Normalizes this instruction by changing iload_1 to iload, etc.

### Parameters

`iter` - The [CodeIterator](#) to change [CtInsn](../-ct-insn/index.md) within.

`index` - The index of the [CtInsn](../-ct-insn/index.md) to change.

`op` - The opcode to be normalized.