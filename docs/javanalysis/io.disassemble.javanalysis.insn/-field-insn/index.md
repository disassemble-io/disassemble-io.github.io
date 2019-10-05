[javanalysis](../../index.md) / [io.disassemble.javanalysis.insn](../index.md) / [FieldInsn](./index.md)

# FieldInsn

`class FieldInsn : `[`ClassMemberInsn`](../-class-member-insn/index.md)

A class representing a field instruction.

### Parameters

`owner` - The [CtMethod](#) that this instruction is a part of.

`index` - The index of this instruction in [CtMethod](#).

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `FieldInsn(owner: CtMethod, index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`)`<br>A class representing a field instruction. |

### Properties

| Name | Summary |
|---|---|
| [desc](desc.md) | `var desc: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>The descriptor of this member. |
| [key](key.md) | `val key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>A string in the format of .. |
| [name](name.md) | `var name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>The name of this member. |
| [parent](parent.md) | `var parent: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>The parent member this instruction is pointed at. |

### Inherited Properties

| Name | Summary |
|---|---|
| [nameAndTypeIndex](../-class-member-insn/name-and-type-index.md) | `val nameAndTypeIndex: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The nameAndTypeIndex internally used with [javassist.bytecode.CodeIterator](#). |
