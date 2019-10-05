[javanalysis](../../index.md) / [io.disassemble.javanalysis.util](../index.md) / [CodeParser](./index.md)

# CodeParser

`object CodeParser : Opcode`

A simple utility class for parsing the bytecode instructions of a method.

**Author**
Tyler Sedlar

**Since**
3/30/2018

### Functions

| Name | Summary |
|---|---|
| [parse](parse.md) | `fun parse(method: CtMethod): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`>`<br>Parses the bytecode instructions of the given [CtMethod](#).`fun parse(method: CtMethod, iter: CodeIterator, pos: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)<br>Gets a string representation of the bytecode instruction at the specified position. |
