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
newlist = Word_Table()
new_list.__head = Node('h')
new_list.__head.__next = Node('hi')
new_list.__head.__next.__next = Node('hii')
new_list.__head.__next.__next.__next = Node('hiii')
new_list.__head.__next.__next.__next.__next = Node('hiiii')
new_list.__head.__next.__next.__next.__next.__next = Node('hiiiii')
new_list.__head.__next.__next.__next.__next.__next.__next = Node('hiiiiii')
new_list.__head.__next.__next.__next.__next.__next.__next.__next = Node('hiiiiiii')
new_list.__head.__next.__next.__next.__next.__next.__next.__next.__next = Node('hiiiiiiii')
new_list.__head.__next.__next.__next.__next.__next.__next.__next.__next.__next = Node('hiiiiiiiii')
