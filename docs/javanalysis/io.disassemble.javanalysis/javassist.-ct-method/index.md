[javanalysis](../../index.md) / [io.disassemble.javanalysis](../index.md) / [javassist.CtMethod](./index.md)

### Extensions for javassist.CtMethod

| Name | Summary |
|---|---|
| [cfg](cfg.md) | `val CtMethod.cfg: `[`ControlFlowGraph`](../../io.disassemble.javanalysis.flow/-control-flow-graph/index.md) |
| [code](code.md) | `val CtMethod.code: CodeAttribute` |
| [desc](desc.md) | `val CtMethod.desc: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [flatDT](flat-d-t.md) | `val CtMethod.flatDT: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`>` |
| [flatPDT](flat-p-d-t.md) | `val CtMethod.flatPDT: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`>` |
| [hash](hash.md) | `val CtMethod.hash: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [hasIndex](has-index.md) | `fun CtMethod.hasIndex(index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [index](--index--.md) | `fun CtMethod.index(insnIndex: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, position: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [indexOf](index-of.md) | `fun CtMethod.indexOf(insn: `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [indices](indices.md) | `val CtMethod.indices: `[`HashMap`](https://docs.oracle.com/javase/6/docs/api/java/util/HashMap.html)`<`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>` |
| [info](info.md) | `val CtMethod.info: MethodInfo` |
| [instructions](instructions.md) | `val CtMethod.instructions: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`>` |
| [key](key.md) | `val CtMethod.key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [line](line.md) | `val CtMethod.line: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [normalizeIndex](normalize-index.md) | `fun CtMethod.normalizeIndex(index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [owner](owner.md) | `val CtMethod.owner: CtClass` |
| [pool](pool.md) | `val CtMethod.pool: ConstPool` |
| [unload](unload.md) | `fun CtMethod.unload(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
