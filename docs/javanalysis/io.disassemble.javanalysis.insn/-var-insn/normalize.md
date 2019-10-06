---
title: VarInsn.normalize - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis.insn](../index.html) / [VarInsn](index.html) / [normalize](./normalize.html)

# normalize

`fun normalize(iter: CodeIterator, index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, op: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Normalizes this instruction by changing iload_1 to iload, etc.

### Parameters

`iter` - The [CodeIterator](#) to change [CtInsn](../-ct-insn/index.html) within.

`index` - The index of the [CtInsn](../-ct-insn/index.html) to change.

`op` - The opcode to be normalized.