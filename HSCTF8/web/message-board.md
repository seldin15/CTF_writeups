# Message-board
>Points: 305

## Challenge description
Your employer, LameCompany, has lots of gossip on its company message board: [message-board.hsc.tf](message-board.hsc.tf). You, `Kupatergen`, are able to access some of the tea, but not all of it! Unsatisfied, you figure that the admin user must have access to ALL of the tea. Your goal is to find the tea you've been missing out on.

Your login credentials: username: `kupatergent` password: `gandal`

Server code is attached (slightly modified).

Downloads: [message-borard-master.zip](message-board-master.zip)

## Challenge analysis
First, I logged in to the website using the credentials that were given to us above. I came to this screen:
![Screenshot](web_msgbrd_1.png)

Sadly, we had no flag (yet). After my initial website check, I downloaded the ZIP file that had the source code that was slightly modified. After inspecting the app.js code, something caught my eye:

![Screenshot](web_msgbrd_2.png)

In short: It was checking whether our cookie **UserID** matched to the **AdminID**. 
