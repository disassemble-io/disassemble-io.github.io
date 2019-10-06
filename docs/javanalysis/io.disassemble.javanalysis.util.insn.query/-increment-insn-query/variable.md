---
title: IncrementInsnQuery.variable - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis.util.insn.query](../index.html) / [IncrementInsnQuery](index.html) / [variable](./variable.html)

# variable

`fun variable(variable: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`IncrementInsnQuery`](index.html)

Adds a condition to [InsnQuery.conditions](../-insn-query/conditions.html) in which [IncrementInsn.variable](../../io.disassemble.javanalysis.insn/-increment-insn/variable.html) must match the given value.

### Parameters

`variable` - The value to match against [IncrementInsn.variable](../../io.disassemble.javanalysis.insn/-increment-insn/variable.html).

**Return**
The same [IncrementInsnQuery](index.html) that this method was called from.

