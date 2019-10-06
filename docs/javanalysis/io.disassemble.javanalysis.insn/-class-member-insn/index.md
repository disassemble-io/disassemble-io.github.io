---
title: ClassMemberInsn - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis.insn](../index.html) / [ClassMemberInsn](./index.html)

# ClassMemberInsn

`open class ClassMemberInsn : `[`CtInsn`](../-ct-insn/index.html)

A class representing a class member (field or method instruction).

### Parameters

`owner` - The [CtMethod](#) that this instruction is a part of.

`index` - The index of this instruction in [CtMethod](#).

### Constructors

| [&lt;init&gt;](-init-.html) | `ClassMemberInsn(owner: CtMethod, index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`)`<br>A class representing a class member (field or method instruction). |

### Properties

| [desc](desc.html) | `open var desc: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>The descriptor of this member. |
| [key](key.html) | `open val key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>A string in the format of .. |
| [name](name.html) | `open var name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>The name of this member. |
| [nameAndTypeIndex](name-and-type-index.html) | `val nameAndTypeIndex: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The nameAndTypeIndex internally used with [javassist.bytecode.CodeIterator](#). |
| [parent](parent.html) | `open var parent: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>The parent member this instruction is pointed at. |

### Inherited Properties

| [index](../-ct-insn/--index--.html) | `var index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The index of this instruction in [CtMethod](#). |
| [line](../-ct-insn/line.html) | `val line: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The line this instruction appears on. |
| [next](../-ct-insn/next.html) | `var next: `[`CtInsn`](../-ct-insn/index.html)`?`<br>The [CtInsn](../-ct-insn/index.html) that appears after this instruction. |
| [opcode](../-ct-insn/opcode.html) | `var opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The opcode of this instruction. |
| [opname](../-ct-insn/opname.html) | `val opname: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The name of this instruction, appearing within [Mnemonic.OPCODE](#). |
| [owner](../-ct-insn/owner.html) | `val owner: CtMethod`<br>The [CtMethod](#) that this instruction is a part of. |
| [position](../-ct-insn/position.html) | `val position: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The position of this instruction within its [CtMethod](#). |
| [previous](../-ct-insn/previous.html) | `var previous: `[`CtInsn`](../-ct-insn/index.html)`?`<br>The [CtInsn](../-ct-insn/index.html) that appears before this instruction. |
| [relativeLine](../-ct-insn/relative-line.html) | `val relativeLine: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>The line this instruction appears on, relative to its [CtMethod](#). |
| [verbose](../-ct-insn/verbose.html) | `val verbose: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>A [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) representation of this instruction. |

### Inherited Functions

| [hasNext](../-ct-insn/has-next.html) | `operator fun hasNext(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the next [CtInsn](../-ct-insn/index.html) is valid. |
| [hasPrevious](../-ct-insn/has-previous.html) | `fun hasPrevious(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the previous [CtInsn](../-ct-insn/index.html) is valid. |
| [toString](../-ct-insn/to-string.html) | `open fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>A basic [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) representation of this instruction. |

### Inheritors

| [FieldInsn](../-field-insn/index.html) | `class FieldInsn : `[`ClassMemberInsn`](./index.html)<br>A class representing a field instruction. |
| [MethodInsn](../-method-insn/index.html) | `class MethodInsn : `[`ClassMemberInsn`](./index.html)<br>A class representing a method instruction. |

