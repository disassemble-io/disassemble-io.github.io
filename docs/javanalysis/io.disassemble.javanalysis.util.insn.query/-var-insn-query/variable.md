[javanalysis](../../index.md) / [io.disassemble.javanalysis.util.insn.query](../index.md) / [VarInsnQuery](index.md) / [variable](./variable.md)

# variable

`fun variable(variable: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`VarInsnQuery`](index.md)

Adds a condition to [InsnQuery.conditions](../-insn-query/conditions.md) in which [VarInsn.variable](../../io.disassemble.javanalysis.insn/-var-insn/variable.md) must match the given value.

### Parameters

`variable` - The value to match against [VarInsn.variable](../../io.disassemble.javanalysis.insn/-var-insn/variable.md).

**Return**
The same [VarInsnQuery](index.md) that this method was called from.

