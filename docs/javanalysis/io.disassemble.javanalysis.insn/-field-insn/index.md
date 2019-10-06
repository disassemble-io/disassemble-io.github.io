---
title: FieldInsn - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis.insn](../index.html) / [FieldInsn](./index.html)

# FieldInsn

`class FieldInsn : `[`ClassMemberInsn`](../-class-member-insn/index.html)

A class representing a field instruction.

### Parameters

`owner` - The [CtMethod](#) that this instruction is a part of.

`index` - The index of this instruction in [CtMethod](#).

### Constructors

| [&lt;init&gt;](-init-.html) | `FieldInsn(owner: CtMethod, index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`)`<br>A class representing a field instruction. |

### Properties

| [desc](desc.html) | `var desc: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>The descriptor of this member. |
| [key](key.html) | `val key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>A string in the format of .. |
| [name](name.html) | `var name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>The name of this member. |
| [parent](parent.html) | `var parent: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>The parent member this instruction is pointed at. |

### Inherited Properties

| [nameAndTypeIndex](../-class-member-insn/name-and-type-index.html) | `val nameAndTypeIndex: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The nameAndTypeIndex internally used with [javassist.bytecode.CodeIterator](#). |

