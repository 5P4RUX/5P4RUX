## Merhaba! Ben SPARUX-666

### Profil Resmi

![Profil Resmi](assets/logo.png)

### Banner

![Banner](assets/banner.png)

### Logo ve Banner

<div>
  <img src="assets/logo.png" alt="Logo" style="width: 150px; height: auto; margin-right: 10px;" />
  <img src="assets/banner.png" alt="Banner" style="width: 600px; height: auto;" />
</div>

### Hakkımda

```go
package main

import "fmt"

type Person struct {
  name     string
  username string
  age      int
  hobbies  []string
  job      string
}

func main() {
  var me = new(Person)
  
  me.name     = "Sparux-666"
  me.username = "Sparux-666"
  me.age      = 20
  me.job      = "Android developer | Web developer | Pentester"
  me.hobbies  = []string{"code","music", "gaming", "Visual Studio"}
  
  fmt.Println(me)
}
