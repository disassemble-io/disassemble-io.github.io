[javanalysis](../../index.md) / [io.disassemble.javanalysis.util](../index.md) / [CtClassScanner](./index.md)

# CtClassScanner

`object CtClassScanner`

A utility class used for parsing a class structure into a [CtClass](#) structure.

**Author**
Tyler Sedlar

**Since**
5/19/2017

### Functions

| Name | Summary |
|---|---|
| [scanClassFile](scan-class-file.md) | `fun scanClassFile(path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, predicate: Predicate<CtClass>?, consumer: Consumer<CtMethod>?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Applies the given [Predicate](#) and [Consumer](#) against the class file.`fun scanClassFile(path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): CtClass?`<br>Reads the given .class file path into a [CtClass](#) object. |
| [scanClassPath](scan-class-path.md) | `fun scanClassPath(predicate: Predicate<CtClass>?, consumer: Consumer<CtMethod>?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Scans the class path for matching [CtClass](#). |
| [scanDirectory](scan-directory.md) | `fun scanDirectory(directory: `[`File`](https://docs.oracle.com/javase/6/docs/api/java/io/File.html)`, predicate: Predicate<CtClass>?, consumer: Consumer<CtMethod>?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Scans the given directory for matching [CtClass](#).`fun scanDirectory(directory: `[`File`](https://docs.oracle.com/javase/6/docs/api/java/io/File.html)`): `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, CtClass>`<br>Scans the given directory for matching [CtClass](#), putting it within a map. The map key matches [CtClass.getName](#) |
| [scanInputStream](scan-input-stream.md) | `fun scanInputStream(inputStream: `[`InputStream`](https://docs.oracle.com/javase/6/docs/api/java/io/InputStream.html)`, predicate: Predicate<CtClass>?, consumer: Consumer<CtMethod>?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Reads the [InputStream](https://docs.oracle.com/javase/6/docs/api/java/io/InputStream.html) into a [CtClass](#) object. |
| [scanJar](scan-jar.md) | `fun scanJar(file: `[`File`](https://docs.oracle.com/javase/6/docs/api/java/io/File.html)`): `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, CtClass>`<br>Reads the given jar [File](https://docs.oracle.com/javase/6/docs/api/java/io/File.html) path into a [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html) of [CtClass](#), where the key is [CtClass.getName](#). |
