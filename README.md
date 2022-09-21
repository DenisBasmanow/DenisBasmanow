**Hi! 👋**

```py
from dataclasses import dataclass


@dataclass
class User:
    name: str
    location: str
    languages: list
    socials: dict


if __name__ == "__main__":
    me = User(
        name="Denis",
        location="Tbilisi, Georgia",
        languages=["Python", "CSS", "JavaScript"],
        socials={
            "discord": "Denis_(<->_<->)#7025",
            "guilded": "Denis_(<->_<->)",
            "twitter": "@_1_Denis_1_"
        }
    )
```
