Linked Lists 


# How to create a linked list
```
class ListNode:
		def __init__(self, value):
			self.value = value
			self.next = None
	



	node1 =  ListNode(1)
	node2 = ListNode(2)
	node3 = ListNode(3)
		
    
    node1.next = node2
    node2.next = node3
```

	


# Adding to the head of Linked list 
```
newNode = ListNode(4)
newNode.next = node1
node1 = newNode
```