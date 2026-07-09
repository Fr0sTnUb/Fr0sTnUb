```
class Nitesh:
    def __init__(self):
        self.name = "Nitesh Sha"
        self.role = "Data Science Undergrad"
        self.education = "B.Tech CS, Lovely Professional University (CGPA: 8.88)"
        self.os = "Garuda Linux (Arch) + Fish shell, dual-boot Windows"
        self.editors = ["VS Code", "Antigravity IDE"]

    def stack(self):
        return {
            "languages": ["Python", "C++", "TypeScript", "SQL"],
            "backend": ["FastAPI", "Node.js", "PostgreSQL"],
            "frontend": ["React", "Angular"],
            "ml": ["scikit-learn", "XGBoost", "Pandas", "NumPy"],
            "infra": ["Docker", "AWS", "Nginx"],
        }

    def building(self):
        return [
            "SentriQ - real-time MLOps fraud detection platform",
            "personal portfolio - React/Vite + GSAP, self-deployed on AWS EC2",
            "MTA ridership analysis - transit data pipeline",
            "MEAN stack app - migrated dev environment Windows to Linux",
        ]

    def learning(self):
        return ["Angular", "Tailwind CSS v4"]

    def looking_for(self):
        return "data science / full-stack roles"

    def contact(self):
        return {
            "github": "github.com/Fr0sTnUb",
            "linkedin": "linkedin.com/in/nitesh-sha",
        }


if __name__ == "__main__":
    nitesh = Nitesh()
    print(nitesh.building())
```
