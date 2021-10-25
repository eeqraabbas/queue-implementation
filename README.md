# queue-implementation
import numpy as np
class queue:
  def __init__(self,s):
    self.s=s
    self.element =np.empty([self.s])
    self.front=-1
    self.rear=-1

def enqueue(self,data):

  self.rear=self.rear+1
    if self.front ==-1:
      self.front == 0:
  self.element[self.rear]=data
def dequeue(self):
  d=(self.element[self.front])
  self.front =self.front+1
  return d
def isfull(self):
  return(self.rear ==self ,s-1)
def isempty(self):

q=queue(5)

q.enqueue(6)
q.enqueue(7)
q.enqueue(8) 
q.enqueue(9)
q.enqueue(10)


print(q.dequeue())
print(q.dequeue())


