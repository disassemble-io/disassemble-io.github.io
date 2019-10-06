[javanalysis](../../index.md) / [io.disassemble.javanalysis.util.insn.query](../index.md) / [JumpInsnQuery](index.md) / [target](./target.md)

# target

`fun target(target: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`JumpInsnQuery`](index.md)

Adds a condition to [InsnQuery.conditions](../-insn-query/conditions.md) in which [JumpInsn.target](../../io.disassemble.javanalysis.insn/-jump-insn/target.md) must match the given value.

### Parameters

`target` - The value to match against [JumpInsn.target](../../io.disassemble.javanalysis.insn/-jump-insn/target.md).

**Return**
The same [JumpInsnQuery](index.md) that this method was called from.

