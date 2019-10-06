---
title: InvokeDynamicInsnQuery.type - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis.util.insn.query](../index.html) / [InvokeDynamicInsnQuery](index.html) / [type](./type.html)

# type

`fun type(type: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`InvokeDynamicInsnQuery`](index.html)

Adds a condition to [InsnQuery.conditions](../-insn-query/conditions.html) in which [InvokeDynamicInsn.type](../../io.disassemble.javanalysis.insn/-invoke-dynamic-insn/type.html) must match the given value.

### Parameters

`type` - The value to match against [InvokeDynamicInsn.type](../../io.disassemble.javanalysis.insn/-invoke-dynamic-insn/type.html).

**Return**
The same [InvokeDynamicInsnQuery](index.html) that this method was called from.

