[javanalysis](../../index.md) / [io.disassemble.javanalysis.util.query](../index.md) / [InsnQuery](index.md) / [int](./int.md)

# int

`fun int(operand: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`InsnQuery`](index.md)

Adds a condition to [InsnQuery.conditions](conditions.md) in which the matching [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.md) must be an [IntInsn](../../io.disassemble.javanalysis.insn/-int-insn/index.md) matching
the given operand.

### Parameters

`operand` - The value to match against [IntInsn.operand](../../io.disassemble.javanalysis.insn/-int-insn/operand.md).

**Return**
The same [InsnQuery](index.md) that this method was called from.

