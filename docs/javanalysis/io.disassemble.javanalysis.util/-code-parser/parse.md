---
title: CodeParser.parse - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis.util](../index.html) / [CodeParser](index.html) / [parse](./parse.html)

# parse

`fun parse(method: CtMethod): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.html)`>`

Parses the bytecode instructions of the given [CtMethod](#).

### Parameters

`method` - The [CtMethod](#) to parse.

**Return**
A list of [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.html) contained within the given [CtMethod](#).

`fun parse(method: CtMethod, iter: CodeIterator, pos: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.html)

Gets a string representation of the bytecode instruction at the specified
position.

### Parameters

`method` - The [CtMethod](#) to parse from.

`iter` - The [CtMethod](#)'s [CodeIterator](#).

`pos` - The position of the [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.html) to parse.

**Return**
The [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.html) at the given position.

