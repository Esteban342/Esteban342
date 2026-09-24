```python
class Developer:
    def __init__(self):
        self.name = "Esteban Mejorado"
        self.role = "Software & IoT Developer"
        self.location = "Ciudad Mante, Tamaulipas"
        
    def get_tech_stack(self):
        return {
            "languages": ["Python", "Java", "JavaScript"],
            "databases": ["MySQL"],
            "mobile_and_web": ["Flutter", "HTML/CSS"],
            "tools": ["Git", "Blender", "Linux"]
        }

    def contact_me(self):
        return {
            "email": "estebanmejoradomartinez@gmail.com",
            "linkedin": "[linkedin.com/in/esteban-mejorado-martínez](https://linkedin.com/in/esteban-mejorado-martínez)"
        }

# Initializing profile...
esteban = Developer()
