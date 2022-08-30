Hi 👋🏼, I'm Yavuz!


Security Engineer and Developer and H4cker 

“Kabexnuf” is a new word made by remixing my name, and it means me. pronunciation is a little vague. say ‘ha-hul’ but you can just call me ‘howl’





More about me...

package main

type Me struct {
	Job         string
	Pronouns    string
	SpecialMove string
	MainWeapon  string
	Language    []string
}

func main() {
	me := &Me{
		Job:         "🗡 Security engineer and Red team that aims for a purple team.",
		Pronouns:    "🧑🏽‍💻 He/Him",
		SpecialMove: "🔥 Web Hacking",
		MainWeapon:  "⚡️ OWASP ZAP",
		Language: []string{
			"🐹 I Love Golang",
			"💎 and Ruby",
		},
	}
	_ = me
}
