```python
class Me:
  hobbys           : list = ["tech stuff", "science", "languages"]
  job_exp          : str  = "3+ years"

class Contacts(Me):
  discord         : str = ".kirssei"
  
class Stack(BackEndDeveloper):
  languages        : list = ["Python", "JS"]
  frameworks       : dict = {
                              "Python": [
                                          "Django",
                                          "Django Rest Framework",
                                          "Celery",
                                          "FastAPI"
                                        ],
                              "JS": [
                                      "React",
                                    ]
                            }
  database         : list = ["MySQL", "PostgreSQL", "Redis", "SQLite", "RabbitMQ"]
```
