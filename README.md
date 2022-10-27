```python
class Me:
  hobbys           : list = ["tech stuff", "science", "languages"]
  job_exp          : str  = "2+ years"

class Contacts(Me):
  discord         : str = "kirei#8097"
  
class Stack(BackEndDeveloper):
  languages        : list = ["Python", "JS"]
  frameworks       : dict = {
                              "Python": [
                                          "Django",
                                          "Django Rest Framework",
                                          "Celery"
                                        ],
                              "JS": [
                                      "React"
                                    ]
                            }
  database         : list = ["MySQL", "PostgreSQL", "Redis"]
```
