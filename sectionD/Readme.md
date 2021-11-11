## Review
    The current implementation has the followiung complexity
    
    Worst case: O(N)  
        This is because for every input string, it has to traverse    through the whole length of the string
    Worst case Extended: O(N^2)
        This is because, we will have to iterate through the whole string for every character to check for matching brackets. 
     

## Implementation Design Change Algorithm
I looked at sample two implementations that would be done to support the changes in the extension and I would only find one which is indeed quiote impressive:

    -> Declare a character stack S.
    -> Now traverse the expression string exp. 
    -> If the current character is a starting bracket (‘(‘ or ‘{‘ or ‘[‘) then push it to stack.
    -> If the current character is a closing bracket (‘)’ or ‘}’ or ‘]’) then pop from stack and if the popped character is the     matching starting bracket then fine else brackets are not balanced.
    -> After complete traversal, if there is some starting bracket left in stack then “not balanced”

The implementation has been done in the file named isBalanced.js

    To run the file you need to make sure you have nodejs installed in your machine. 

    To execute and get the ouput run the following line:

        node isBalanced.js
    
    You should get an output indicating balanced. The implemenation done works for any number of brackets and we don't need to specify
    which are the opening or cl;osing brackets. It is able to detect if all brackets are matching or not

## Space Complexity of the implementation    
    The worst case complexity is o(N) for any number of brackets 
