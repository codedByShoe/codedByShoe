```go

package codedByShoe;

func main() {
    LGTM()
}

func LGTM() map[string]interface{} {
        developer := struct{
		languages []string
		technologies []string
		yearsExperience int
		avaliable bool
	}{
		languages: []string{"Go", "PHP", "Javascript", "SQL", "Python", "Lua"},	
		technologies: []string{"Laravel", "TALL", "HTMX", "React", "InertiaJS"},	
		yearsExperience: 4,
		avaliable: true,
	}

	return map[string]interface{} {
		"Andrew Shoemaker": developer,
	}
}
```

