<p align="center">
  <img src="https://github.com/thompsonemerson/thompsonemerson/raw/master/cover-thompson.png" height="200"/>
</p>
<hr>

<h1 align="center">Hi <img src="https://raw.githubusercontent.com/ABSphreak/ABSphreak/master/gifs/Hi.gif" width="30px"> I'm Justin John</h1>
<!-- <h2> Connect with me <img src='https://raw.githubusercontent.com/ShahriarShafin/ShahriarShafin/main/Assets/handshake.gif' width="100px"> </h2>
<p align="left">
  <a href="https://www.linkedin.com/in/justin-john07/">
    <img src="https://www.vectorlogo.zone/logos/linkedin/linkedin-icon.svg" alt="Justin John's LinkedIn Profile" height="30" width="30">
  </a>
 </p> -->
 
```golang
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
		"- ⚡ Quick bio:":                    "A kind of stickShiftAddict-amateurSinger-traveler-foodLover-gamer-coder-programmer-cricketFanatic-footballCrazy-occasionalBookWorm",
		"- 🌱 I’m currently learning":        "Golang, PostgresSQL, Docker, K8s, Microservices(Personal goal)",
		"- 👯 I’m looking to collaborate on": "Golang and Docker related projects",
		"- 🤔 I’m looking for help with":     "Anything related to what I am currently learning 😅",
		"- 📫 How to reach me:":              "https://github.com/loosec9n","https://www.linkedin.com/in/justin-john07/"
	}
}
```
![Justin John's Activity Graph](https://activity-graph.herokuapp.com/graph?username=loosec9n&custom_title=Justin%20John's%20Contribution%20Graph&theme=gruvbox&bg_color=282828&hide_border=true&line=d1a01f&point=c58545)
