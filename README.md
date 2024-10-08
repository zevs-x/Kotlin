# Типы Данных

В Kotlin типы данных можно разделить на примитивные и ссылочные.
Ссылочные типы данных включают объекты и массивы.
Примитивные типы данных представляют собой простые значения, такие как числа и символы. 

## Примитивных типы данных:

1. **byte**: хранит целое число от -128 до 127 и занимает 1 байт.
   ```
   val b: Byte = 100
   ```

2. **short**: хранит целое число от -32768 до 32767 и занимает 2 байта.
   ```
   val s: Short = 10000
   ```

3. **int**: хранит целое число от -2147483648 до 2147483647 и занимает 4 байта.
   ```
   val i: Int = 100000
   ```

4. **long**: хранит целое число от –9 223 372 036 854 775 808 до 9 223 372 036 854 775 807 и занимает 8 байт.
   ```
   val l: Long = 10000000000L
   ```

5. **float**: хранит число с плавающей точкой от -3.4*1038 до 3.4*1038 и занимает 4 байта.
   ```
   val f: Float = 10.5f
   ```

6. **double**: хранит число с плавающей точкой от ±4.9*10-324 до ±1.7976931348623157*10308 и занимает 8 байт.
   ```
   val d: Double = 20.99
   ```

7. **char**: хранит одиночный символ в кодировке UTF-16 и занимает 2 байта, поэтому диапазон хранимых значений от 0 до 65535.
   ```
   val c: Char = 'A'
   ```

8. **boolean**: Логический тип данных хранит true или false.
   ```
   val bool: Boolean = true
   ```

## Ссылочные Типы Данных

Ссылочные типы данных включают объекты и массив:

1. **String**: Для работы со строками.
   ```
   val str: String = "Hello, World!"
   ```

2. **Массивы**: Хранит нескольких элементов одного типа данных.
   ```
   val numbers: IntArray = intArrayOf(1, 2, 3, 4, 5)
   ```

## Объявление Переменных

Можно объединить объявление и инициализацию. val (неизменяемые) и var (изменяемые):
```
val name: String = "Alice"
var age: Int = 30
```

# Ввод Данных

## Ввод и вывод Данных в коде

Для ввода данных в Kotlin можно использовать библиотеку.

```
fun main()
{
    print("Введите ваше имя- ")                 //Вывод строки
    val a = readLine() ?: ""                    //Ввод данных

    print("Введите ваш год рождения- ")         //Вывод строки
    val s = readLine()?.toIntOrNull() ?: 0      //Ввод данных

    println("Привет $a Вы родились в $s ")      //Ввод всех веденныхданных
}
```

## Вывод Данных строки

Для вывода данных в Kotlin можно использовать. 

```println()		//С новой строки```

```print()		   //На той же строки```



