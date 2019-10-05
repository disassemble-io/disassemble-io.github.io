[javanalysis](../../index.md) / [io.disassemble.javanalysis.insn](../index.md) / [ClassMemberInsn](./index.md)

# ClassMemberInsn

`open class ClassMemberInsn : `[`CtInsn`](../-ct-insn/index.md)

A class representing a class member (field or method instruction).

### Parameters

`owner` - The [CtMethod](#) that this instruction is a part of.

`index` - The index of this instruction in [CtMethod](#).

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ClassMemberInsn(owner: CtMethod, index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`)`<br>A class representing a class member (field or method instruction). |

### Properties

| Name | Summary |
|---|---|
| [desc](desc.md) | `open var desc: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>The descriptor of this member. |
| [key](key.md) | `open val key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>A string in the format of .. |
| [name](name.md) | `open var name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>The name of this member. |
| [nameAndTypeIndex](name-and-type-index.md) | `val nameAndTypeIndex: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The nameAndTypeIndex internally used with [javassist.bytecode.CodeIterator](#). |
| [parent](parent.md) | `open var parent: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>The parent member this instruction is pointed at. |

### Inherited Properties

| Name | Summary |
|---|---|
| [index](../-ct-insn/--index--.md) | `var index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The index of this instruction in [CtMethod](#). |
| [line](../-ct-insn/line.md) | `val line: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The line this instruction appears on. |
| [next](../-ct-insn/next.md) | `var next: `[`CtInsn`](../-ct-insn/index.md)`?`<br>The [CtInsn](../-ct-insn/index.md) that appears after this instruction. |
| [opcode](../-ct-insn/opcode.md) | `var opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The opcode of this instruction. |
| [opname](../-ct-insn/opname.md) | `val opname: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The name of this instruction, appearing within [Mnemonic.OPCODE](#). |
| [owner](../-ct-insn/owner.md) | `val owner: CtMethod`<br>The [CtMethod](#) that this instruction is a part of. |
| [position](../-ct-insn/position.md) | `val position: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The position of this instruction within its [CtMethod](#). |
| [previous](../-ct-insn/previous.md) | `var previous: `[`CtInsn`](../-ct-insn/index.md)`?`<br>The [CtInsn](../-ct-insn/index.md) that appears before this instruction. |
| [relativeLine](../-ct-insn/relative-line.md) | `val relativeLine: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The line this instruction appears on, relative to its [CtMethod](#). |
| [verbose](../-ct-insn/verbose.md) | `val verbose: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>A [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) representation of this instruction. |

### Inherited Functions

| Name | Summary |
|---|---|
| [hasNext](../-ct-insn/has-next.md) | `operator fun hasNext(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the next [CtInsn](../-ct-insn/index.md) is valid. |
| [hasPrevious](../-ct-insn/has-previous.md) | `fun hasPrevious(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the previous [CtInsn](../-ct-insn/index.md) is valid. |
| [toString](../-ct-insn/to-string.md) | `open fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>A basic [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) representation of this instruction. |

### Inheritors

| Name | Summary |
|---|---|
| [FieldInsn](../-field-insn/index.md) | `class FieldInsn : `[`ClassMemberInsn`](./index.md)<br>A class representing a field instruction. |
| [MethodInsn](../-method-insn/index.md) | `class MethodInsn : `[`ClassMemberInsn`](./index.md)<br>A class representing a method instruction. |
