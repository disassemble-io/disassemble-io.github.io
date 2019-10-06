---
title: IntInsnQuery.operand - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis.util.insn.query](../index.html) / [IntInsnQuery](index.html) / [operand](./operand.html)

# operand

`fun operand(operand: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`IntInsnQuery`](index.html)

Adds a condition to [InsnQuery.conditions](../-insn-query/conditions.html) in which [IntInsn.operand](../../io.disassemble.javanalysis.insn/-int-insn/operand.html) must match the given value.

### Parameters

`operand` - The value to match against [IntInsn.operand](../../io.disassemble.javanalysis.insn/-int-insn/operand.html).

**Return**
The same [IntInsnQuery](index.html) that this method was called from.

