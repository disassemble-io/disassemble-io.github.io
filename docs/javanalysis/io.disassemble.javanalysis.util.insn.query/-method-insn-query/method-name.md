[javanalysis](../../index.md) / [io.disassemble.javanalysis.util.insn.query](../index.md) / [MethodInsnQuery](index.md) / [methodName](./method-name.md)

# methodName

`fun methodName(methodName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`MethodInsnQuery`](index.md)

Adds a condition to [InsnQuery.conditions](../-insn-query/conditions.md) in which [MethodInsn.name](../../io.disassemble.javanalysis.insn/-method-insn/name.md) must match the given value.

### Parameters

`methodName` - The value to match against [MethodInsn.name](../../io.disassemble.javanalysis.insn/-method-insn/name.md).

**Return**
The same [MethodInsnQuery](index.md) that this method was called from.

