---
title: VarInsnQuery.variable - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis.util.insn.query](../index.html) / [VarInsnQuery](index.html) / [variable](./variable.html)

# variable

`fun variable(variable: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`VarInsnQuery`](index.html)

Adds a condition to [InsnQuery.conditions](../-insn-query/conditions.html) in which [VarInsn.variable](../../io.disassemble.javanalysis.insn/-var-insn/variable.html) must match the given value.

### Parameters

`variable` - The value to match against [VarInsn.variable](../../io.disassemble.javanalysis.insn/-var-insn/variable.html).

**Return**
The same [VarInsnQuery](index.html) that this method was called from.

