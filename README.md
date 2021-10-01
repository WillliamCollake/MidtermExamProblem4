# MidtermExamProblem4
Problem 4 Midterm

def deep_reverse(L):
  ''' 
  assumes L is a list of lists whose elements are ints
  Mutates L such that it reverses its elements and also
  reverses the order of the int elements in every element of L.
  It does not return anything.
  '''
  #iterate over reversed list
  #reverse each item and append it at end
  #then cut in half and get rid of first half
  
  
  for i in reversed(L):
      i.reverse()
      L.append(i)
  L[:] = L[len(L)//2:]
