# Tipe Data Number

Secara garis besar tipe data number pada bahasa Go ada dua jenis, yaitu :

* Integer
* Floating Point

## Tipe Data Integer

### Integer

| Tipe Data | Nilai Minimum        | Nilai Maksimum      |
| --------- | -------------------- | ------------------- |
| int8      | -128                 | 127                 |
| int16     | -32768               | 32767               |
| int32     | -2147483648          | 2147483647          |
| int64     | -9223372036854775808 | 9223372036854775807 |

### Unsigned Integer

| Tipe Data | Nilai Minimum | Nilai Maksimum       |
| --------- | ------------- | -------------------- |
| uint8     | 0             | 255                  |
| uint16    | 0             | 65535                |
| uint32    | 0             | 4294967295           |
| uint64    | 0             | 18446744073709551615 |

## Tipe Data Floating Point

### Float

| Tipe Data | Nilai Minimum | Nilai Maksimum |
| --------- | ------------- | -------------- |
| float32   | 1.18×10−38    | 3.4×1038       |
| float64   | 2.23×10−308   | 1.80×10308     |

### Complex

| Tipe Data  | Deskripsi                                              |
| ---------- | ------------------------------------------------------ |
| complex64  | complex numbers with float32 real and imaginary parts. |
| complex128 | complex numbers with float64 real and imaginary parts. |

## Alias

| Tipe Data | Alias untuk    |
| --------- | -------------- |
| byte      | uint8          |
| rune      | int32          |
| int       | minimal int32  |
| uint      | minimal uint32 |

## Kode Program Number

{% code title="number.go" lineNumbers="true" %}
```go
package main

import "fmt"

func main() {
	fmt.Println("Satu =", 1)
	fmt.Println("Dua =", 2)
	fmt.Println("Tiga Koma Lima =", 3.5)
}
```
{% endcode %}
