---
title: InsnUtil - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis.util.insn](../index.html) / [InsnUtil](./index.html)

# InsnUtil

`object InsnUtil`

**Author**
Tyler Sedlar

**Since**
5/20/2017

### Functions

| [isFieldInsn](is-field-insn.html) | `fun isFieldInsn(opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the given opcode is a [FieldInsn](../../io.disassemble.javanalysis.insn/-field-insn/index.html). |
| [isIncrementInsn](is-increment-insn.html) | `fun isIncrementInsn(opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the given opcode is a [IncrementInsn](../../io.disassemble.javanalysis.insn/-increment-insn/index.html). |
| [isIntInsn](is-int-insn.html) | `fun isIntInsn(opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the given opcode is an [IntInsn](../../io.disassemble.javanalysis.insn/-int-insn/index.html). |
| [isInvokeDynamicInsn](is-invoke-dynamic-insn.html) | `fun isInvokeDynamicInsn(opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the given opcode is an [InvokeDynamicInsn](../../io.disassemble.javanalysis.insn/-invoke-dynamic-insn/index.html). |
| [isJumpInsn](is-jump-insn.html) | `fun isJumpInsn(opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the given opcode is a [JumpInsn](../../io.disassemble.javanalysis.insn/-jump-insn/index.html). |
| [isLdcInsn](is-ldc-insn.html) | `fun isLdcInsn(opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the given opcode is an [LdcInsn](../../io.disassemble.javanalysis.insn/-ldc-insn/index.html). |
| [isLookupSwitchInsn](is-lookup-switch-insn.html) | `fun isLookupSwitchInsn(opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the given opcode is a [LookupSwitchInsn](../../io.disassemble.javanalysis.insn/-lookup-switch-insn/index.html). |
| [isMethodInsn](is-method-insn.html) | `fun isMethodInsn(opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the given opcode is a [MethodInsn](../../io.disassemble.javanalysis.insn/-method-insn/index.html). |
| [isTableSwitchInsn](is-table-switch-insn.html) | `fun isTableSwitchInsn(opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the given opcode is a [TableSwitchInsn](../../io.disassemble.javanalysis.insn/-table-switch-insn/index.html). |
| [isTypeInsn](is-type-insn.html) | `fun isTypeInsn(opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the given opcode is a [TypeInsn](../../io.disassemble.javanalysis.insn/-type-insn/index.html). |
| [isUnderscoreInsn](is-underscore-insn.html) | `fun isUnderscoreInsn(opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the given opcode is an opcode containing an underscore (iload_0, iload_1, etc.) |
| [isVarInsn](is-var-insn.html) | `fun isVarInsn(opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if the given opcode is a [VarInsn](../../io.disassemble.javanalysis.insn/-var-insn/index.html). |
| [stringify](stringify.html) | `fun stringify(insn: `[`CtInsn`](../../io.disassemble.javanalysis.insn/-ct-insn/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Gets the string representation of the given [CtInsn](../../io.disassemble.javanalysis.insn/-ct-insn/index.html). |
| [underVal](under-val.html) | `fun underVal(opcode: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Gets the value of the underscore variable. (iload_0 = 0, iload_1 = 1, etc.) |

