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
		languages: []string{"Go", "Javascript", "SQL", "PHP", "Python", "CSS"},	
		technologies: []string{"React", "TailwindCss", "Bootstrap", "HTMX", "Prisma", "InertiaJS", "Laravel"},	
		yearsExperience: 4,
		avaliable: true,
	}

	return map[string]interface{} {
		"Andrew Shoemaker": developer,
	}
}
```

