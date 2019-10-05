[javanalysis](../../index.md) / [io.disassemble.javanalysis.insn](../index.md) / [MultiANewArrayInsn](./index.md)

# MultiANewArrayInsn

`class MultiANewArrayInsn : `[`TypeInsn`](../-type-insn/index.md)

A class representing a multianewarray instruction.

### Parameters

`owner` - The [CtMethod](#) that this instruction is a part of.

`index` - The index of this instruction in [CtMethod](#).

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `MultiANewArrayInsn(owner: CtMethod, index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`)`<br>A class representing a multianewarray instruction. |

### Properties

| Name | Summary |
|---|---|
| [dimensions](dimensions.md) | `val dimensions: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>How many dimensions within this [MultiANewArrayInsn](./index.md). |

### Inherited Properties

| Name | Summary |
|---|---|
| [type](../-type-insn/type.md) | `var type: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The type of this [TypeInsn](../-type-insn/index.md). |
