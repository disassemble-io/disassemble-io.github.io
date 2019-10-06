[javanalysis](../../index.md) / [io.disassemble.javanalysis.util.insn.query](../index.md) / [InvokeDynamicInsnQuery](index.md) / [bootstrap](./bootstrap.md)

# bootstrap

`fun bootstrap(bootstrap: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`InvokeDynamicInsnQuery`](index.md)

Adds a condition to [InsnQuery.conditions](../-insn-query/conditions.md) in which [InvokeDynamicInsn.bootstrap](../../io.disassemble.javanalysis.insn/-invoke-dynamic-insn/bootstrap.md) must match the given value.

### Parameters

`bootstrap` - The value to match against [InvokeDynamicInsn.bootstrap](../../io.disassemble.javanalysis.insn/-invoke-dynamic-insn/bootstrap.md).

**Return**
The same [InvokeDynamicInsnQuery](index.md) that this method was called from.

