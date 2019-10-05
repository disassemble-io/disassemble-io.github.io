[javanalysis](../../index.md) / [io.disassemble.javanalysis.util](../index.md) / [CtClassScanner](index.md) / [scanJar](./scan-jar.md)

# scanJar

`fun scanJar(file: `[`File`](https://docs.oracle.com/javase/6/docs/api/java/io/File.html)`): `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, CtClass>`

Reads the given jar [File](https://docs.oracle.com/javase/6/docs/api/java/io/File.html) path into a [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html) of [CtClass](#), where the key is [CtClass.getName](#).

### Parameters

`file` - The path of the .jar file to read.

**Return**
A [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html) of [CtClass](#), where the key is [CtClass.getName](#).

