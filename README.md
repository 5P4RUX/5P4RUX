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
