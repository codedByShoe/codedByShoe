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
		languages: []string{"Go", "Python", "C#", "SQL", "PHP", "Lua"},	
		technologies: []string{"Laravel", "HTMX", "React", "Vue", "InertiaJS"},	
		yearsExperience: 4,
		avaliable: true,
	}

	return map[string]interface{} {
		"Andrew Shoemaker": developer,
	}
}
```

