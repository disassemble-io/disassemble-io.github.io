[javanalysis](../../index.md) / [io.disassemble.javanalysis.insn](../index.md) / [IncrementInsn](./index.md)

# IncrementInsn

`class IncrementInsn : `[`CtInsn`](../-ct-insn/index.md)

**Author**
Tyler Sedlar

**Since**
5/20/2017

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `IncrementInsn(owner: CtMethod, index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`)` |

### Properties

| Name | Summary |
|---|---|
| [increment](increment.md) | `var increment: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [variable](variable.md) | `var variable: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

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

### Inherited Functions

| Name | Summary |
|---|---|
| [hasNext](../-ct-insn/has-next.md) | `operator fun hasNext(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hasPrevious](../-ct-insn/has-previous.md) | `fun hasPrevious(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [toString](../-ct-insn/to-string.md) | `open fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
