[javanalysis](../../index.md) / [io.disassemble.javanalysis.util.insn.query](../index.md) / [InsnQuery](index.md) / [opcode](./opcode.md)

# opcode

`fun opcode(vararg opcodes: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`InsnQuery`](index.md)`<`[`T`](index.md#T)`>`

Adds a condition to [InsnQuery.conditions](conditions.md) in which the matching [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.md) must be of one of the given opcodes.

### Parameters

`opcodes` - A list of opcodes to match.

**Return**
The same [InsnQuery](index.md) that this method was called from.

