[javanalysis](../../index.md) / [io.disassemble.javanalysis.util.insn.query](../index.md) / [FieldInsnQuery](index.md) / [fieldName](./field-name.md)

# fieldName

`fun fieldName(fieldName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`FieldInsnQuery`](index.md)

Adds a condition to [InsnQuery.conditions](../-insn-query/conditions.md) in which [FieldInsn.name](../../io.disassemble.javanalysis.insn/-field-insn/name.md) must match the given value.

### Parameters

`fieldName` - The value to match against [FieldInsn.name](../../io.disassemble.javanalysis.insn/-field-insn/name.md).

**Return**
The same [FieldInsnQuery](index.md) that this method was called from.

