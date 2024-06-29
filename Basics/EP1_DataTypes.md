# Java Data Types

## Primitive Data Types

| Data Type | Size     | Value Range                                 | Default Value | Usage                                                |
|-----------|----------|---------------------------------------------|---------------|------------------------------------------------------|
| byte      | 8-bit    | -128 to 127                                 | 0             | Saving memory in large arrays                        |
| short     | 16-bit   | -32,768 to 32,767                           | 0             | Saving memory in large arrays                        |
| int       | 32-bit   | -2^31 to 2^31-1                             | 0             | Default data type for integral values                |
| long      | 64-bit   | -2^63 to 2^63-1                             | 0L            | When a wider range than `int` is needed              |
| float     | 32-bit   | ±3.40282347E+38F (6-7 significant digits)   | 0.0f          | Saving memory in large arrays of floating point nums |
| double    | 64-bit   | ±1.79769313486231570E+308 (15 significant digits) | 0.0d          | Default data type for decimal values                 |
| char      | 16-bit   | '\u0000' to '\uffff'                        | '\u0000'      | Storing characters                                   |
| boolean   | 1-bit    | true or false                               | false         | Simple flags that track true/false conditions        |

## Non-Primitive Data Types

| Data Type | Description                                                | Default Value | Usage                                    |
|-----------|------------------------------------------------------------|---------------|------------------------------------------|
| String    | A sequence of characters                                   | null          | Storing text                             |
| Array     | A container object that holds a fixed number of values of a single type | n/a           | Storing multiple values in a single variable |
| Class     | A blueprint for creating objects which contains methods and variables | n/a           | Creating user-defined data types         |
| Interface | An abstract type used to specify a behavior that classes must implement | n/a           | Achieving abstraction and multiple inheritance |
| Enum      | A special class that represents a group of constants       | n/a           | Defining collections of constants        |

## Example Usage

```java
public class DataTypesExample {
    public static void main(String[] args) {
        // Primitive data types
        byte byteVar = 100;
        short shortVar = 1000;
        int intVar = 10000;
        long longVar = 100000L;
        float floatVar = 10.5f;
        double doubleVar = 20.5;
        char charVar = 'A';
        boolean booleanVar = true;

        // Non-primitive data types
        String stringVar = "Hello, World!";
        int[] arrayVar = {1, 2, 3, 4, 5};
        
        // Printing values
        System.out.println("byteVar: " + byteVar);
        System.out.println("shortVar: " + shortVar);
        System.out.println("intVar: " + intVar);
        System.out.println("longVar: " + longVar);
        System.out.println("floatVar: " + floatVar);
        System.out.println("doubleVar: " + doubleVar);
        System.out.println("charVar: " + charVar);
        System.out.println("booleanVar: " + booleanVar);
        System.out.println("stringVar: " + stringVar);
        System.out.print("arrayVar: ");
        for (int i : arrayVar) {
            System.out.print(i + " ");
        }
    }
}
```
