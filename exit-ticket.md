### P(redict)

Predict what the following code snippet will do:
```py
class Human:
    def __init__(self, name, age, occupation):
        self.name = name
        self.age = age
        self.occupation = occupation

    def think(self):
        print("The human is thinking deeply.")

    def communicate(self):
        print("The human is communicating clearly.")

class AI(Human):
    def __init__(self, name, age, occupation, intelligence_level):
        self.intelligence_level = intelligence_level
        super().__init__(name, age, occupation)

    def think(self):
        print("The A`perform_task()` online.")

    def communicate(self):
        print("The AI is communicating digitally with its human.")

    def learn(self):
        print("The AI is learning and improving its capabilities.")

my_ai = AI("Athena", 5, "Virtual Assistant", 9.8)
print(my_ai.name)
print(my_ai.age)
print(my_ai.occupation)
print(my_ai.intelligence_level)
my_ai.think()
my_ai.communicate()
my_ai.learn()
```
---
The code snippet will establish one instance of the child class "AI" which will inherit attributes like the name "Athena," the age of 5 and the occupation of virtual assistant from the Human class. Additionally it will be given an intelligence_level attribute of 9.8. It then prints out every attribute and finally it will use the modules think, communicate and learn to print off different messages. I don't know what "The A`perform_task()` online." means but it will probably do nothing.

### I(nvestigate)

Answer these questions about the code snippet:

1. What is the relationship between the Human and AI classes?
   The AI class is a subclass or child class of the parent class or superclass Human.
2. How does the `__init__()` method in the AI class use the `super()` function?
   The init method uses the super function to inherit attributes from its super class, Human.
3. How does the output of the `think()` and `communicate()` methods differ between the Human and AI instances?
    Think and communicate differ between the human and ai instances as they print different strings.
4. Which attributes will the AI class get/grab from the Human class?
    It will inherit name, age, and occupation attributes.
5. Which attribute belongs specifically to the AI class?
    The intelligence_level attribute belongs exclusively to the AI class.
6. How many attributes **total** will an instance of the AI class have?
 It will have four. Name, age, occupation, and intelligence_level.
---
