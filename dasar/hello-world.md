# Hello World

Membuat program Hello World di Golang memang tidak se simple ketika kita membuat program Hello World pada bahasa seperti PHP atau Python, lebih mirip ketika kita membuat Program Hello World pada bahasa yang sedikit kompleks seperti Java, C, dan lainnya,

## Program Hello World

{% code title="helloworld.go" lineNumbers="true" %}
```go
package main

import "fmt"

func main() {
	fmt.Println("Hello, world!")
}
```
{% endcode %}

Mirip seperti dengan di bahasa Java, C atau mungkin C# ketika kita membuat program maka harus ada di dalam function yang namanya `main`

Ketika ingin menampilkan tulisan maka harus menggunakan function `fmt.Println` lalu diberi masukan parameter berupa kalimat yang bertipe data `string`

Untuk mendapatkan function package `fmt` kita harus _import_ package yang bernama `fmt`

Untuk membuat function main maka package yang dibuat harus dinamai dengan `package main`

Mungkin terlihat agak menyulitkan dan panjang di awal padahal bahasa Go adalah bahasa yang bisa di bilang sederhana, namun lama kelamaan mempelajari bahasa Go ini maka akan terasa bahasa Go lebih sederhana daripada bahasa-bahasa lainnya seperti PHP, Java dan lainnya.

## Kompilasi File Golang

Untuk melakukan kompilasi pada bahasa Go maka menggunakan perintah `go build`

```bash
go build helloworld.go
```

hasil dari kompilasi ini akan menghasilkan file binary yang bernama  `helloworld` dan bisa dijalankan dengan menggunakan syntax

```
./helloworld
```

## Menjalankan Tanpa Kompilasi

Selain dengan cara kompilasi pada file yang telah dibuat, mejalankan program Go bisa juga menggunakan syntax `go run`

```
go run helloworld.go
```

Cara ini bisa digunakan saat melakukan development menggunakan Bahasa Go dan tidak di sarankan untuk menggunakan cara ini ketika deploy program yang dibuat ke server, karena sewajarnya di server hanya perlu file _binary_ hasil dari kompilasi program tersebut.
