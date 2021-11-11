##Review of the code submitted
    The choice to use a do while loop was great

    However, within the while loop you needed to write code that 
    does checks for both the number of times the user has entered 
    the password, and if more than three showcase the password and write 
    a new method that checks if the newly entered password meets the 
    password requirements 

    You will realise, in that case you will need another loop that 
    continuously checks for that. For good programming practices, it is greate
    if the two operations are written in different methods

    In that case, I would suggest you do the following, using the code 
    attached as a reference point. 

        In your do while loop, track the number of times 
        the user has entered the password

        if more than three, call a method for creating a new 
        password that also within it checks that new 
        password meets the requirements

        while the number of times is less than three, if correct
        use the message dialog to showcase success insted of using 
        a print statement. The same goes for when a new password has 
        been successfully created.