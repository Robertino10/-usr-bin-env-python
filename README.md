# -usr-bin-env-python
class Biz:
    """r is rate, hr list of hours, w week pay
    Methods:
         yr()
         sethr()
    """

    def __init__(self):
        self.r=70
        self.hr=[40,43,46,48,51]
        self.w=[self.r*i for i in self.hr]

    def yr(self,value=48):
        self.w=[self.r*i for i in self.hr]
        return [48*i for i in self.w]

    def r(self):
        return self.r

    def setr(self,value):
        self.r=value

    def week(self):
        self.w=[self.r*i for i in self.hr]
        return  [self.r*i for i in self.hr]

    def sethr(self,value):
        self.hr.append(value)
        self.w=[self.r*i for i in self.hr]
        return [48*i for i in self.w]
        

    def rate(self,value):
        self.r=value
        w=[self.r*i for i in hr]

    def __add__(self, other):
        return Foo(self.hrs + other.value)
Back to Top

