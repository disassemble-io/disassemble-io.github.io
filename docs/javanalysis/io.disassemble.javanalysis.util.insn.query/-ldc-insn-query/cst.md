[javanalysis](../../index.md) / [io.disassemble.javanalysis.util.insn.query](../index.md) / [LdcInsnQuery](index.md) / [cst](./cst.md)

# cst

`fun cst(cst: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): `[`LdcInsnQuery`](index.md)

Adds a condition to [InsnQuery.conditions](../-insn-query/conditions.md) in which [LdcInsn.cst](../../io.disassemble.javanalysis.insn/-ldc-insn/cst.md) must match the given value.

### Parameters

`cst` - The value to match against [LdcInsn.cst](../../io.disassemble.javanalysis.insn/-ldc-insn/cst.md).

**Return**
The same [LdcInsnQuery](index.md) that this method was called from.

