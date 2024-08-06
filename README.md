### Hi  everyone 👋
![Screenshot from 2024-04-22 11-40-01](https://github.com/0x3f3c/0x3f3c/assets/154844497/9dacdef3-6e86-43d1-be9c-c39b341568db)
<script src="https://tryhackme.com/badge/1326789"></script>


```
package main

import (
    "fmt"
    "strconv"
)

func main() {
    hexValue := "0x3F3C"
    
    decimalValue, err := strconv.ParseInt(hexValue, 0, 64)
    if err != nil {
        fmt.Println("Error converting hexadecimal to decimal:", err)
        return
    }
    
    fmt.Printf("The decimal value of %s is %d\n", hexValue, decimalValue)
}

```
<!--
**0x3f3c/0x3f3c** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
