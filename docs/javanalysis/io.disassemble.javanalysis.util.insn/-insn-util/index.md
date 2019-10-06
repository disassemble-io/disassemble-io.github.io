[javanalysis](../../index.md) / [io.disassemble.javanalysis.util.insn](../index.md) / [InsnUtil](./index.md)

# InsnUtil

`object InsnUtil`

**Author**
Tyler Sedlar

**Since**
5/20/2017

### Functions

| Name | Summary |
|---|---|
| [isFieldInsn](is-field-insn.md) | `fun isFieldInsn(opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the given opcode is a [FieldInsn](../../io.disassemble.javanalysis.insn/-field-insn/index.md). |
| [isIncrementInsn](is-increment-insn.md) | `fun isIncrementInsn(opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the given opcode is a [IncrementInsn](../../io.disassemble.javanalysis.insn/-increment-insn/index.md). |
| [isIntInsn](is-int-insn.md) | `fun isIntInsn(opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the given opcode is an [IntInsn](../../io.disassemble.javanalysis.insn/-int-insn/index.md). |
| [isInvokeDynamicInsn](is-invoke-dynamic-insn.md) | `fun isInvokeDynamicInsn(opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the given opcode is an [InvokeDynamicInsn](../../io.disassemble.javanalysis.insn/-invoke-dynamic-insn/index.md). |
| [isJumpInsn](is-jump-insn.md) | `fun isJumpInsn(opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the given opcode is a [JumpInsn](../../io.disassemble.javanalysis.insn/-jump-insn/index.md). |
| [isLdcInsn](is-ldc-insn.md) | `fun isLdcInsn(opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the given opcode is an [LdcInsn](../../io.disassemble.javanalysis.insn/-ldc-insn/index.md). |
| [isLookupSwitchInsn](is-lookup-switch-insn.md) | `fun isLookupSwitchInsn(opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the given opcode is a [LookupSwitchInsn](../../io.disassemble.javanalysis.insn/-lookup-switch-insn/index.md). |
| [isMethodInsn](is-method-insn.md) | `fun isMethodInsn(opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the given opcode is a [MethodInsn](../../io.disassemble.javanalysis.insn/-method-insn/index.md). |
| [isTableSwitchInsn](is-table-switch-insn.md) | `fun isTableSwitchInsn(opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the given opcode is a [TableSwitchInsn](../../io.disassemble.javanalysis.insn/-table-switch-insn/index.md). |
| [isTypeInsn](is-type-insn.md) | `fun isTypeInsn(opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the given opcode is a [TypeInsn](../../io.disassemble.javanalysis.insn/-type-insn/index.md). |
| [isUnderscoreInsn](is-underscore-insn.md) | `fun isUnderscoreInsn(opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the given opcode is an opcode containing an underscore (iload_0, iload_1, etc.) |
| [isVarInsn](is-var-insn.md) | `fun isVarInsn(opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the given opcode is a [VarInsn](../../io.disassemble.javanalysis.insn/-var-insn/index.md). |
| [stringify](stringify.md) | `fun stringify(insn: `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.md)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Gets the string representation of the given [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.md). |
| [underVal](under-val.md) | `fun underVal(opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Gets the value of the underscore variable. (iload_0 = 0, iload_1 = 1, etc.) |
