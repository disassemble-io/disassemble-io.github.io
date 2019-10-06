---
title: MethodInsnQuery.parent - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis.util.insn.query](../index.html) / [MethodInsnQuery](index.html) / [parent](./parent.html)

# parent

`fun parent(parent: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`MethodInsnQuery`](index.html)

Adds a condition to [InsnQuery.conditions](../-insn-query/conditions.html) in which [MethodInsn.parent](../../io.disassemble.javanalysis.insn/-method-insn/parent.html) must match the given value.

### Parameters

`parent` - The value to match against [MethodInsn.parent](../../io.disassemble.javanalysis.insn/-method-insn/parent.html).

**Return**
The same [MethodInsnQuery](index.html) that this method was called from.

