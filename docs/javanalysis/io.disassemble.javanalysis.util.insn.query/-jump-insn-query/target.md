---
title: JumpInsnQuery.target - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis.util.insn.query](../index.html) / [JumpInsnQuery](index.html) / [target](./target.html)

# target

`fun target(target: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`JumpInsnQuery`](index.html)

Adds a condition to [InsnQuery.conditions](../-insn-query/conditions.html) in which [JumpInsn.target](../../io.disassemble.javanalysis.insn/-jump-insn/target.html) must match the given value.

### Parameters

`target` - The value to match against [JumpInsn.target](../../io.disassemble.javanalysis.insn/-jump-insn/target.html).

**Return**
The same [JumpInsnQuery](index.html) that this method was called from.

