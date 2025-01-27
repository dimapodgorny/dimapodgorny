<h2>dimapodgorny.py</h2>

```python
class dimapodgorny:
    def __init__(self, personal: dict, socials : dict):
        self.personal = {
            "name" : "Dimitri Apollon Podgorny", #FIRST -> MIDDLE -> LAST
            "age" : 17,
            "birthday" : [06, 10, 2007], # DDMMYYYY
            "location" : "Oslo, Norway",
            "studying" : [True, "Studying IT at Kuben Upper Secondary"],
            "lookingForWork" : [True, "Looking for internship"],
            "attributes" : {
                "languages" : ["Norwegian", "French", "English"],
                "coding" : [Python, GDScript, Javascript, HTML, CSS, ("Learning", C#)],
                "hobbies/interests" : ["gaming", "climbing", "parkour", "training"],
            }
        }
        
        self.socials = {
            "GitHub" : "https://github.com/dimapodgorny",
            "Instagram" : "https://github.com/dimapodgorny",
        }
```

#note: this page is still a WIP
