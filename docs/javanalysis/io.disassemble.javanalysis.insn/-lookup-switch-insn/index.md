[javanalysis](../../index.md) / [io.disassemble.javanalysis.insn](../index.md) / [LookupSwitchInsn](./index.md)

# LookupSwitchInsn

`class LookupSwitchInsn : `[`CtInsn`](../-ct-insn/index.md)

**Author**
Tyler Sedlar

**Since**
5/20/2017

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `LookupSwitchInsn(owner: CtMethod, index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`)` |

### Properties

| Name | Summary |
|---|---|
| [defaultIndex](default-index.md) | `val defaultIndex: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [end](end.md) | `val end: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [indices](indices.md) | `val indices: `[`IntArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int-array/index.html) |
| [keys](keys.md) | `val keys: `[`IntArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int-array/index.html) |
| [npairs](npairs.md) | `val npairs: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [start](start.md) | `val start: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

### Inherited Properties

| Name | Summary |
|---|---|
| [index](../-ct-insn/--index--.md) | `var index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [line](../-ct-insn/line.md) | `val line: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [next](../-ct-insn/next.md) | `var next: `[`CtInsn`](../-ct-insn/index.md)`?` |
| [opcode](../-ct-insn/opcode.md) | `var opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [opname](../-ct-insn/opname.md) | `val opname: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [owner](../-ct-insn/owner.md) | `val owner: CtMethod` |
| [position](../-ct-insn/position.md) | `val position: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [previous](../-ct-insn/previous.md) | `var previous: `[`CtInsn`](../-ct-insn/index.md)`?` |
| [relativeLine](../-ct-insn/relative-line.md) | `val relativeLine: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [verbose](../-ct-insn/verbose.md) | `val verbose: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [populateKeysAndIndices](populate-keys-and-indices.md) | `fun populateKeysAndIndices(force: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inherited Functions

| Name | Summary |
|---|---|
| [hasNext](../-ct-insn/has-next.md) | `operator fun hasNext(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hasPrevious](../-ct-insn/has-previous.md) | `fun hasPrevious(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [toString](../-ct-insn/to-string.md) | `open fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
