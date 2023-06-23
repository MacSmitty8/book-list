# What I knew
In class, most of what I did in the code along was already used in the code for the book list. It covered querySelector, list.appendChild, and even classList were all things I knew about from the previous lessons and understood right away.

# What I didn't know
What I didn't know that was covered in this code along was the alert function. 
In the code, he did two specific ones, one where where the browser itself would tell you that you needed to fill in all the required marks, which is:
`alert('Please fill in all fields');

Compared to on a message that would should up on the webpage, which is coded by using the UI class and attaching it to a function.

`if (title === '' || author === '' || isbn === '') {
        UI.ShowAlert('Please fill in all fields.', 'danger');
    }`

Another thing I wasn't aware of before this code along was the setTimeout method. I knew websites have a way of getting rid of stuff on the page after a set amount of time I never knew the method for it. Here it's used to remove the "Please fill in all fields messages" if the user doesn't fill all the fields. In my code, it goes away after 4 seconds compared to the original codes 3 seconds. I'm sure there's better ways of making the removal transition smoother because with this code it just disappears after the 4 seconds. It also apparently needs three zeroes in order for it to register a single digit.

`setTimeout(() => document.querySelector('.alert').remove(), 4000)`

# Things I still need to research/practice

Some of the things I need to go over again would be the static methods. In this case it's used so that the data doesn't get necessarily replicated, which in this case would be the adding the book, author, and isbn to the list. By doing this, the function doesn't need to be redone over and over, and can be done as many times the user wants, or is able to. There's also using JavaScript to add stuff to html without using some aspects of HTML and mainly CSS. Like, using innerHTML and variables to make things like rows and lists. I haven't had the chance to ask in class to ask why use things this way, but some parts of it do make it unique and sort of convenient, since I didn't have to use much CSS for this.