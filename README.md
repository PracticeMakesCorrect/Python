# Python

class the_best:
  def __init__(self, fname, lname):
    self.firstname = fname
    self.lastname = lname

  def printname(self):
    print(self.firstname,self.lastname)

class one_and_only(the_best):
  pass

myname = one_and_only("Jeffrey", "Confidential")
myname.printname()
