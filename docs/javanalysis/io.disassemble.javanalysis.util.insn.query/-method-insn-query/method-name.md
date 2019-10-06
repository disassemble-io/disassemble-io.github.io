---
title: MethodInsnQuery.methodName - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis.util.insn.query](../index.html) / [MethodInsnQuery](index.html) / [methodName](./method-name.html)

# methodName

`fun methodName(methodName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`MethodInsnQuery`](index.html)

Adds a condition to [InsnQuery.conditions](../-insn-query/conditions.html) in which [MethodInsn.name](../../io.disassemble.javanalysis.insn/-method-insn/name.html) must match the given value.

### Parameters

`methodName` - The value to match against [MethodInsn.name](../../io.disassemble.javanalysis.insn/-method-insn/name.html).

**Return**
The same [MethodInsnQuery](index.html) that this method was called from.

