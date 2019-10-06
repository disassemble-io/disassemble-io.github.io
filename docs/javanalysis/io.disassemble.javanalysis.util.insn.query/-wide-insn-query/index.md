---
title: WideInsnQuery - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis.util.insn.query](../index.html) / [WideInsnQuery](./index.html)

# WideInsnQuery

`class WideInsnQuery : `[`InsnQuery`](../-insn-query/index.html)`<`[`WideInsn`](../../io.disassemble.javanalysis.insn/-wide-insn/index.html)`>`

A class representing a query for an [WideInsn](../../io.disassemble.javanalysis.insn/-wide-insn/index.html).
Used for filtering in lists.

### Constructors

| [&lt;init&gt;](-init-.html) | `WideInsnQuery()`<br>A class representing a query for an [WideInsn](../../io.disassemble.javanalysis.insn/-wide-insn/index.html). Used for filtering in lists. |

### Inherited Properties

| [conditions](../-insn-query/conditions.html) | `var conditions: `[`ArrayList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-array-list/index.html)`<(`[`T`](../-insn-query/index.html#T)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>`<br>The list of conditions that must be met. Used within [InsnQuery.check](../-insn-query/check.html) |
| [dist](../-insn-query/dist.html) | `var dist: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Sets the distance allowed to be traveled between queries within [io.disassemble.javanalysis.InsnLine.find](../../io.disassemble.javanalysis/-insn-line/find.html). |
| [name](../-insn-query/name.html) | `var name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Gives this query a name. Used for putting into a map within [io.disassemble.javanalysis.InsnLine.find](../../io.disassemble.javanalysis/-insn-line/find.html). |

### Functions

| [wideIndex](wide-index.html) | `fun wideIndex(wideIndex: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`WideInsnQuery`](./index.html)<br>Adds a condition to [InsnQuery.conditions](../-insn-query/conditions.html) in which [WideInsn.wideIndex](../../io.disassemble.javanalysis.insn/-wide-insn/wide-index.html) must match the given value. |
| [wideOp](wide-op.html) | `fun wideOp(wideOp: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`WideInsnQuery`](./index.html)<br>Adds a condition to [InsnQuery.conditions](../-insn-query/conditions.html) in which [WideInsn.wideOp](../../io.disassemble.javanalysis.insn/-wide-insn/wide-op.html) must match the given value. |

### Inherited Functions

| [check](../-insn-query/check.html) | `fun check(insn: `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if this [InsnQuery](../-insn-query/index.html)'s conditions are met by the given [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.html). |
| [dist](../-insn-query/dist.html) | `fun dist(dist: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`InsnQuery`](../-insn-query/index.html)`<`[`T`](../-insn-query/index.html#T)`>`<br>Sets the value of [InsnQuery.dist](../-insn-query/dist.html) and returns itself. |
| [name](../-insn-query/name.html) | `fun name(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`InsnQuery`](../-insn-query/index.html)`<`[`T`](../-insn-query/index.html#T)`>`<br>Sets the value of [InsnQuery.name](../-insn-query/name.html) and returns itself. |
| [opcode](../-insn-query/opcode.html) | `fun opcode(vararg opcodes: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`InsnQuery`](../-insn-query/index.html)`<`[`T`](../-insn-query/index.html#T)`>`<br>Adds a condition to [InsnQuery.conditions](../-insn-query/conditions.html) in which the matching [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.html) must be of one of the given opcodes. |
| [plus](../-insn-query/plus.html) | `operator fun plus(query: `[`InsnQuery`](../-insn-query/index.html)`<out `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.html)`>): `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`InsnQuery`](../-insn-query/index.html)`<out `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.html)`>>`<br>Creates an array of the two [InsnQuery](../-insn-query/index.html), being the [InsnQuery](../-insn-query/index.html) called from, and the given value. |

