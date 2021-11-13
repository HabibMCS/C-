# Doubly linked list data structure
Using the doubly linked list concept, write a function MoveToFront( ) with one argument of data type integer. This function will first search the linked list and compare the Data member of the node with the given number as argument. If the search finds the number in the list then this function will move that node to the start of the list as shown in the example below. The order of the remaining nodes is to remain unchanged. If no node in the list contains the integer, MoveToFront( ) should leave the list unchanged. Assume that the list contains no duplicate values.  The structure definition of the doubly linked list is 
	
structListNode{
		ListNode *pre;	
		int Data;
		ListNode *Next;
	}*head;
The function declaration of MoveToFront function is Void MoveToFront(int);

