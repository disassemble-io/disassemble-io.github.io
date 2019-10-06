---
title: FieldInsnQuery.fieldName - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis.util.insn.query](../index.html) / [FieldInsnQuery](index.html) / [fieldName](./field-name.html)

# fieldName

`fun fieldName(fieldName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`FieldInsnQuery`](index.html)

Adds a condition to [InsnQuery.conditions](../-insn-query/conditions.html) in which [FieldInsn.name](../../io.disassemble.javanalysis.insn/-field-insn/name.html) must match the given value.

### Parameters

`fieldName` - The value to match against [FieldInsn.name](../../io.disassemble.javanalysis.insn/-field-insn/name.html).

**Return**
The same [FieldInsnQuery](index.html) that this method was called from.

