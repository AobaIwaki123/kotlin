# Kotlin触ってみた

## 学習内容

- Hello World
  - println: 文字列表示後に改行される
  - print: 文字列を表示する
- variables
  - val: read-only
  - var: mutable
  - print variable: 
    - println("it's $variable")
    - println("it's ${variable + 1}")
  - 型推論あり
- Basic types
- Collections
  - each collection type can be mutable or read-only
  - casting is supported
- Control flow
- Functions
- Classes
- Null safety

## Basic Types

For more information on basic types and their properties, see [Basic types](https://kotlinlang.org/docs/basic-types.html).


| Category                 | **Basic types**                      |
|--------------------------|----------------------------|
| **Integers**             | Byte, Short, Int, Long     |
| **Unsigned integers**    | UByte, UShort, UInt, ULong |
| **Floating-point numbers** | Float, Double              |
| **Booleans**             | Boolean                    |
| **Characters**           | Char                       |
| **Strings**              | String                     |

## Collections

| Collection Type | Description                                        |
|-----------------|----------------------------------------------------|
| **Lists**       | Ordered collections of items                       |
| **Sets**        | Unique unordered collections of items              |
| **Maps**        | Sets of key-value pairs where keys are unique and map to only one value |

### casting

To prevent unwanted modifications, you can obtain read-only views of mutable lists by assigning them to a List:

```kotlin
val shapes: MutableList<String> = mutableListOf("triangle", "square", "circle")
val shapesLocked: List<String> = shapes
```
## 参考

- [Welcome to our tour of Kotlin!](https://kotlinlang.org/docs/kotlin-tour-welcome.html)
