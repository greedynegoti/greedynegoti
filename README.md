class Node:
    def __init__(self,data):
        self.__data = data
        self.__next = None
class Word_Table:
    def __init__(self):
        self.__head = None

    def insert(self,value):
        newnode = Node(value)
        newnode.__next = self.__head
        self.__head = newnode
    def contains(self,value):
        current = self.__head
        while current.__value is not value:
            return true
        current = current.__next
        return False
                
            
    def isempty(self):
        if self.__head.__next is None:
            print('empty')
