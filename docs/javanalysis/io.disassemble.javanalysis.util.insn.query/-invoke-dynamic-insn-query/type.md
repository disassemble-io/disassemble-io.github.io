[javanalysis](../../index.md) / [io.disassemble.javanalysis.util.insn.query](../index.md) / [InvokeDynamicInsnQuery](index.md) / [type](./type.md)

# type

`fun type(type: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`InvokeDynamicInsnQuery`](index.md)

Adds a condition to [InsnQuery.conditions](../-insn-query/conditions.md) in which [InvokeDynamicInsn.type](../../io.disassemble.javanalysis.insn/-invoke-dynamic-insn/type.md) must match the given value.

### Parameters

`type` - The value to match against [InvokeDynamicInsn.type](../../io.disassemble.javanalysis.insn/-invoke-dynamic-insn/type.md).

**Return**
The same [InvokeDynamicInsnQuery](index.md) that this method was called from.

