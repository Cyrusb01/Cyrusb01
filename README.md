```python
#!/usr/bin/python
# -*- coding: utf-8 -*-


class Cyrus:

    def __init__(self):
        self.name = "Cyrus Buhariwalla"
        self.role = "Quant Developer"
        self.languages = ["Python", "C++", "SQL", "HTML", "CSS"]
        self.hobbies = ["Rock Climbing", "Tennis", "Cooking", "Crypto", "Quant Trading"] 

    def introduce_myself(self):
        print(f"Hi, I'm {self.name} and am an {self.role}. Thanks for stopping by!")


me = Cyrus()
me.introduce_myself()
```
