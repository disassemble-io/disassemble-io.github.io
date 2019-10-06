---
title: InvokeDynamicInsnQuery.bootstrap - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis.util.insn.query](../index.html) / [InvokeDynamicInsnQuery](index.html) / [bootstrap](./bootstrap.html)

# bootstrap

`fun bootstrap(bootstrap: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`InvokeDynamicInsnQuery`](index.html)

Adds a condition to [InsnQuery.conditions](../-insn-query/conditions.html) in which [InvokeDynamicInsn.bootstrap](../../io.disassemble.javanalysis.insn/-invoke-dynamic-insn/bootstrap.html) must match the given value.

### Parameters

`bootstrap` - The value to match against [InvokeDynamicInsn.bootstrap](../../io.disassemble.javanalysis.insn/-invoke-dynamic-insn/bootstrap.html).

**Return**
The same [InvokeDynamicInsnQuery](index.html) that this method was called from.

