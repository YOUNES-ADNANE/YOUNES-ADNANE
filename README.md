## Hi there 👋
class AspiringProgrammer:

    def __init__(self):
        # Personal information
        self.name = "CNOS"
        self.birth_year = 2008
        self.country = "Morocco"
        self.role = "Aspiring Software Developer"
        self.languages_spoken = ["Arabic", "French", "English"]
        # Goal
        self.goal = "Learn C, complete 1337 C00-C02 exercises, build projects, and share my learning journey on GitHub."

    def introduce_myself(self):
        print(f"Hi! My name is {self.name}.")
        print(f"I was born in {self.birth_year} in {self.country}.")
        print(f"I am an {self.role}.")
        print(f"I speak: {', '.join(self.languages_spoken)}.")
        print(f"My goal: {self.goal}")
        print("Thanks for visiting my GitHub profile! I hope you find my projects interesting.")

# Create an object and run the introduction
me = AspiringProgrammer()
me.introduce_myself()
