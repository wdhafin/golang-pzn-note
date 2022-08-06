# Tipe Data Boolean

Tipe data boolean adalah tipe data yang hanya memiliki dua nilai, yaitu benar dan salah\
Di bahasa Go, tipe data boolean direpresentasikan menggunakan kata kunci **bool**

Walaupun tipe data ini sangat sederhana, namun ketika membuat sebuah program maka akan banyak sekali menggunakan tipe data ini, bahkan bisa di bilang sebuah tipe data yang wajib dalam suatu program.

## **Boolean**

| Nilai Boolean | Keterangan |
| ------------- | ---------- |
| true          | Benar      |
| false         | Salah      |

## Kode Program Boolean

{% code title="boolean.go" lineNumbers="true" %}
```go
package main

import "fmt"

func main() {
	fmt.Println("Benar = ", true)
	fmt.Println("Salah = ", false)
}
```
{% endcode %}
