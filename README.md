class AlwinJones:
    def __init__(self):
        self.name = "Alwin Jones S"
        self.location = "Bengaluru, India"
        self.degree = "MCA @ St. Joseph's"
        self.background = "B.Sc. CS, Loyola College"
        self.stack = [
            "Python", "Flask", "MySQL",
            "HTML", "CSS"
        ]
        self.currently_learning = [
            "Advanced Flask",
            "Cloud Computing",
            "Data Structures & Algorithms"
        ]
        self.fun_fact = "Cultural Secretary + " \
                         "240+ hrs NSS volunteer"

    def motto(self):
        return "Learn. Build. Ship."


me = AlwinJones()
print(me.motto())
