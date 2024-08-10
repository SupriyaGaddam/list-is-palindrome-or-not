# list-is-palindrome-or-not
def is_palindrome(Linked_list):
    values=Linked_list
    left=0
    right=len(values)-1
    while left<right:
        if values[left]!=values[right]:
            return False
        left+=1
        right-=1
    return True
Linked_list=[1,2,2,1]
print(is_palindrome(Linked_list))
Linked_list=[1,8,9,1]    
print(is_palindrome(Linked_list))
