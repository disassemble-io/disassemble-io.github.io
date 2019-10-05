[javanalysis](../../index.md) / [io.disassemble.javanalysis](../index.md) / [javassist.CtMethod](./index.md)

### Extensions for javassist.CtMethod

| Name | Summary |
|---|---|
| [cfg](cfg.md) | `val CtMethod.cfg: `[`ControlFlowGraph`](../../io.disassemble.javanalysis.flow/-control-flow-graph/index.md)<br>Gets the [ControlFlowGraph](../../io.disassemble.javanalysis.flow/-control-flow-graph/index.md) of this [CtMethod](#). |
| [code](code.md) | `val CtMethod.code: CodeAttribute`<br>Gets the [CodeAttribute](#) associated with this [CtMethod](#). |
| [desc](desc.md) | `val CtMethod.desc: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The descriptor of this [CtMethod](#). |
| [flatDT](flat-d-t.md) | `val CtMethod.flatDT: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`>`<br>A flattened list of this method's [ControlFlowGraph.dominatorTree](../../io.disassemble.javanalysis.flow/-control-flow-graph/dominator-tree.md). |
| [flatPDT](flat-p-d-t.md) | `val CtMethod.flatPDT: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`>`<br>A flattened list of this method's [ControlFlowGraph.postDominatorTree](../../io.disassemble.javanalysis.flow/-control-flow-graph/post-dominator-tree.md). |
| [hash](hash.md) | `val CtMethod.hash: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Gets a unique hash for this [CtMethod](#). |
| [hasIndex](has-index.md) | `fun CtMethod.hasIndex(index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the given index is within [indices](indices.md). |
| [index](--index--.md) | `fun CtMethod.index(insnIndex: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, position: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Maps the instruction index to the given position. |
| [indexOf](index-of.md) | `fun CtMethod.indexOf(insn: `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Gets the index of the given [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.md) within this [CtMethod](#). |
| [indices](indices.md) | `val CtMethod.indices: `[`HashMap`](https://docs.oracle.com/javase/6/docs/api/java/util/HashMap.html)`<`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>`<br>A map of the [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.md) indices associated with this [CtMethod](#). |
| [info](info.md) | `val CtMethod.info: MethodInfo`<br>Gets the [MethodInfo](#) associated with this [CtMethod](#). |
| [instructions](instructions.md) | `val CtMethod.instructions: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`>`<br>Gets a [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html) of [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.md) within this [CtMethod](#). |
| [key](key.md) | `val CtMethod.key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>A string formed as &lt;owner.name&gt;. |
| [line](line.md) | `val CtMethod.line: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Gets the line that this [CtMethod](#) starts on. |
| [normalizeIndex](normalize-index.md) | `fun CtMethod.normalizeIndex(index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Gets the index if it appears within [indices](indices.md), else the previous one. |
| [owner](owner.md) | `val CtMethod.owner: CtClass`<br>The [CtClass](#) that this [CtMethod](#) is a part of. |
| [pool](pool.md) | `val CtMethod.pool: ConstPool`<br>Gets the [ConstPool](#) associated with this [CtMethod](#). |
| [unload](unload.md) | `fun CtMethod.unload(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Clears the cached data associated with this [CtMethod](#). |
