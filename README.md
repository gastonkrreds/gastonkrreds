```
PROFILE_README = {
    "name": "Juan Pérez",
    "description": "¡Hola! Soy Juan Pérez, un desarrollador de software apasionado por la tecnología y la innovación.",
    "skills": [
        "Python",
        "JavaScript",
        "HTML/CSS",
        "React",
        "Node.js"
    ],
    "interests": [
        "Desarrollo web",
        "Inteligencia artificial",
        "Machine learning",
        "Desarrollo móvil"
    ],
    "projects": [
        {
            "name": "Proyecto1",
            "description": "Una herramienta para gestionar tareas de manera eficiente.",
            "link": "https://github.com/juanperez/proyecto1"
        },
        {
            "name": "Proyecto2",
            "description": "Una aplicación web para seguimiento de hábitos.",
            "link": "https://github.com/juanperez/proyecto2"
        }
    ],
    "contact": {
        "email": "juan.perez@example.com",
        "linkedin": "https://www.linkedin.com/in/juanperez",
        "twitter": "https://twitter.com/juanperez"
    }
}

def print_profile_readme(profile_readme):
    print(f"# {profile_readme['name']}\n")
    print(f"{profile_readme['description']}\n")
    print("## Habilidades\n")
    for skill in profile_readme["skills"]:
        print(f"- {skill}")
    print("\n## Intereses\n")
    for interest in profile_readme["interests"]:
        print(f"- {interest}")
    print("\n## Proyectos\n")
    for project in profile_readme["projects"]:
        print(f"- [{project['name']}]({project['link']}): {project['description']}")
    print("\n## Contacto\n")
    print(f"- **Email**: [{profile_readme['contact']['email']}](mailto:{profile_readme['contact']['email']})")
    print(f"- **LinkedIn**: [LinkedIn]({profile_readme['contact']['linkedin']})")
    print(f"- **Twitter**: [Twitter]({profile_readme['contact']['twitter']})")

if __name__ == "__main__":
    print_profile_readme(PROFILE_README)
```



<!--
**gastonkrreds/gastonkrreds** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
