[javanalysis](../../index.md) / [io.disassemble.javanalysis.util.insn.query](../index.md) / [IncrementInsnQuery](index.md) / [variable](./variable.md)

# variable

`fun variable(variable: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`IncrementInsnQuery`](index.md)

Adds a condition to [InsnQuery.conditions](../-insn-query/conditions.md) in which [IncrementInsn.variable](../../io.disassemble.javanalysis.insn/-increment-insn/variable.md) must match the given value.

### Parameters

`variable` - The value to match against [IncrementInsn.variable](../../io.disassemble.javanalysis.insn/-increment-insn/variable.md).

**Return**
The same [IncrementInsnQuery](index.md) that this method was called from.

