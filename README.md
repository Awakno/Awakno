```py 
class Me:
    def __init__(self):
        super().__init__()
        self.name = "Awakno"
        self.age = 404
        self.discord = "awakno"
    
    @staticmethod
    async def skill(language):
        if isinstance(language,python):
            skills = {
                "Discord API": True,
                "Request": True,
                "Backend": True,
                "API":True,
                "Automatisation": True,
                "Front-End": "Learning"
            }
        if isinstance(language,javascript):
            skills = {
                "FrontEnd": True,
                "BackEnd": False
             }
        if isistance(language,html):
            skills = {
                "Static": True,
                "FrameWork-FrontEnd": []
            }
        
        return skills

        
```
