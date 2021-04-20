<h2 align="center">Hi there, I'm Dang Huu Loc 👋</h2>

```Go
package main

import (
    "fmt"
)

type Bio map[string]string

func main() {
    for k, v := range GetBio() {
	fmt.Printf("%+v: %+v\n", k, v)
    }
}

func GetBio() Bio {
    return Bio{
	"- ⚡ Quick bio:":                    "I like technology and programing, I like Mechanical Keyboard and setup workspace💥",
	"- 🔭 I’m currently working on":      "College students",
	"- 🌱 I’m currently learning":        "Jhipster stack, Spring framework, Angular and React,",
	"- 👯 I’m looking to collaborate on": "Java, JS/TS, C# and related projects",
	"- 🤔 I’m looking for help with":     "Anything",
	"- 💬 Ask me about":                  "Spring Boot, Golang, Jhipster, SQL, Non-SQL, Software Design & Architecture",
	"- 📫 How to reach me:":              "https://www.facebook.com/loc.yen.512/",
    }
}
```

