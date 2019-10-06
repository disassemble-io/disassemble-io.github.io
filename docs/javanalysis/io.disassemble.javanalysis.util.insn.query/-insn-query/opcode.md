---
title: InsnQuery.opcode - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis.util.insn.query](../index.html) / [InsnQuery](index.html) / [opcode](./opcode.html)

# opcode

`fun opcode(vararg opcodes: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`InsnQuery`](index.html)`<`[`T`](index.html#T)`>`

Adds a condition to [InsnQuery.conditions](conditions.html) in which the matching [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.html) must be of one of the given opcodes.

### Parameters

`opcodes` - A list of opcodes to match.

**Return**
The same [InsnQuery](index.html) that this method was called from.

