---
title: io.disassemble.javanalysis.javassist.CtMethod - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis](../index.html) / [javassist.CtMethod](./index.html)

### Extensions for javassist.CtMethod

| [cfg](cfg.html) | `val CtMethod.cfg: `[`ControlFlowGraph`](../../io.disassemble.javanalysis.flow/-control-flow-graph/index.html)<br>Gets the [ControlFlowGraph](../../io.disassemble.javanalysis.flow/-control-flow-graph/index.html) of this [CtMethod](#). |
| [code](code.html) | `val CtMethod.code: CodeAttribute`<br>Gets the [CodeAttribute](#) associated with this [CtMethod](#). |
| [desc](desc.html) | `val CtMethod.desc: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The descriptor of this [CtMethod](#). |
| [flatDT](flat-d-t.html) | `val CtMethod.flatDT: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.html)`>`<br>A flattened list of this method's [ControlFlowGraph.dominatorTree](../../io.disassemble.javanalysis.flow/-control-flow-graph/dominator-tree.html). |
| [flatPDT](flat-p-d-t.html) | `val CtMethod.flatPDT: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.html)`>`<br>A flattened list of this method's [ControlFlowGraph.postDominatorTree](../../io.disassemble.javanalysis.flow/-control-flow-graph/post-dominator-tree.html). |
| [hash](hash.html) | `val CtMethod.hash: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Gets a unique hash for this [CtMethod](#). |
| [hasIndex](has-index.html) | `fun CtMethod.hasIndex(index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the given index is within [indices](indices.html). |
| [index](--index--.html) | `fun CtMethod.index(insnIndex: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, position: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Maps the instruction index to the given position. |
| [indexOf](index-of.html) | `fun CtMethod.indexOf(insn: `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.html)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Gets the index of the given [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.html) within this [CtMethod](#). |
| [indices](indices.html) | `val CtMethod.indices: `[`HashMap`](https://docs.oracle.com/javase/6/docs/api/java/util/HashMap.html)`<`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>`<br>A map of the [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.html) indices associated with this [CtMethod](#). |
| [info](info.html) | `val CtMethod.info: MethodInfo`<br>Gets the [MethodInfo](#) associated with this [CtMethod](#). |
| [instructions](instructions.html) | `val CtMethod.instructions: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.html)`>`<br>Gets a [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html) of [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.html) within this [CtMethod](#). |
| [key](key.html) | `val CtMethod.key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>A string formed as &lt;owner.name&gt;. |
| [line](line.html) | `val CtMethod.line: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Gets the line that this [CtMethod](#) starts on. |
| [normalizeIndex](normalize-index.html) | `fun CtMethod.normalizeIndex(index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Gets the index if it appears within [indices](indices.html), else the previous one. |
| [owner](owner.html) | `val CtMethod.owner: CtClass`<br>The [CtClass](#) that this [CtMethod](#) is a part of. |
| [pool](pool.html) | `val CtMethod.pool: ConstPool`<br>Gets the [ConstPool](#) associated with this [CtMethod](#). |
| [unload](unload.html) | `fun CtMethod.unload(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Clears the cached data associated with this [CtMethod](#). |

