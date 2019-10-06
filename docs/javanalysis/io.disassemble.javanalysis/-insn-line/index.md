---
title: InsnLine - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis](../index.html) / [InsnLine](./index.html)

# InsnLine

`class InsnLine`

A structure representing a line of code.
Acts as a [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html) of [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.html).

### Parameters

`line` - The line that the accompanied [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.html) appear on.

### Constructors

| [&lt;init&gt;](-init-.html) | `InsnLine(line: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`)`<br>A structure representing a line of code. Acts as a [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html) of [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.html). |

### Properties

| [line](line.html) | `val line: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The line that the accompanied [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.html) appear on. |
| [list](list.html) | `val list: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.html)`>`<br>The [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.html) that appear on this line. |

### Functions

| [add](add.html) | `fun add(insn: `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Adds the given [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.html) to this line. |
| [find](find.html) | `fun find(vararg queries: `[`InsnQuery`](../../io.disassemble.javanalysis.util.insn.query/-insn-query/index.html)`<out `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.html)`>): `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.html)`>`<br>Searches for the given queries within [list](list.html). |

