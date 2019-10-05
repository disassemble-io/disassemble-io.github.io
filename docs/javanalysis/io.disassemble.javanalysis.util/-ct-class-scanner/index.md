[javanalysis](../../index.md) / [io.disassemble.javanalysis.util](../index.md) / [CtClassScanner](./index.md)

# CtClassScanner

`object CtClassScanner`

**Author**
Tyler Sedlar

**Since**
5/19/2017

### Functions

| Name | Summary |
|---|---|
| [scanClassFile](scan-class-file.md) | `fun scanClassFile(path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, predicate: Predicate<CtClass>?, consumer: Consumer<CtMethod>?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun scanClassFile(path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): CtClass?` |
| [scanClassPath](scan-class-path.md) | `fun scanClassPath(predicate: Predicate<CtClass>?, consumer: Consumer<CtMethod>?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [scanDirectory](scan-directory.md) | `fun scanDirectory(directory: `[`File`](https://docs.oracle.com/javase/6/docs/api/java/io/File.html)`, predicate: Predicate<CtClass>?, consumer: Consumer<CtMethod>?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun scanDirectory(directory: `[`File`](https://docs.oracle.com/javase/6/docs/api/java/io/File.html)`): `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, CtClass>` |
| [scanInputStream](scan-input-stream.md) | `fun scanInputStream(inputStream: `[`InputStream`](https://docs.oracle.com/javase/6/docs/api/java/io/InputStream.html)`, predicate: Predicate<CtClass>?, consumer: Consumer<CtMethod>?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [scanJar](scan-jar.md) | `fun scanJar(file: `[`File`](https://docs.oracle.com/javase/6/docs/api/java/io/File.html)`): `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, CtClass>` |
