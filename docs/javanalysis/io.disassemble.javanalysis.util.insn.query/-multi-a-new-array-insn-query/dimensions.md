[javanalysis](../../index.md) / [io.disassemble.javanalysis.util.insn.query](../index.md) / [MultiANewArrayInsnQuery](index.md) / [dimensions](./dimensions.md)

# dimensions

`fun dimensions(dimensions: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`MultiANewArrayInsnQuery`](index.md)

Adds a condition to [InsnQuery.conditions](../-insn-query/conditions.md) in which [MultiANewArrayInsn.dimensions](../../io.disassemble.javanalysis.insn/-multi-a-new-array-insn/dimensions.md) must match the given value.

### Parameters

`dimensions` - The value to match against [MultiANewArrayInsn.dimensions](../../io.disassemble.javanalysis.insn/-multi-a-new-array-insn/dimensions.md).

**Return**
The same [MultiANewArrayInsnQuery](index.md) that this method was called from.

