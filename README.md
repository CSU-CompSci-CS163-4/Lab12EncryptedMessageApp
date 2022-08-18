## Lab 12 - EncryptedMessageApp
 
## Scenario 
Your boss was impressed with your work last week. This week you will add methods to encrypt and decrypt messages, as well as compose messages. Instructions can be found in the [javadoc](https://csu-compsci-cs163-4.github.io/Lab12EncryptedMessageApp/package-summary.html).

Here is an example of the program running:

```text
Welcome to Wonderland Messenger.
[C]: compose new message
[S]: search for a message
[X]: exit
What would you like to do? c
TO:  Cheshire Cat
FROM:  Red
SUBJECT:  Grumpy Cat
BODY:  What are you smiling at?
What file would you like to write your message to?  output.txt
Message composed.
Welcome to Wonderland Messenger.
[C]: compose new message
[S]: search for a message
[X]: exit
What would you like to do? s
What type of search would you like to do?
Options are: subject, to, from to
Enter your search phrase:  cat
Found message!
TO: Cheshire Cat
FROM: Quick Rabbit
SUBJECT: Important Meeting
BODY: Don't be late for our very important date!

Found message!
TO: Cheshire Cat
FROM: Red
SUBJECT: Grumpy Cat
BODY: What are you smiling at?


Welcome to Wonderland Messenger.
[C]: compose new message
[S]: search for a message
[X]: exit
What would you like to do? x
Would you like to save your messages from this session? (y/n) y

Process finished with exit code 0
```

After running, `input.txt` looks like:
```text
TO: Alice
FROM: Hatter
SUBJECT: Red Queen
BODY: To keep ahead, run from the red queen.
TO: Hatter
FROM: Red
SUBJECT: New Hat
BODY: Hatter, I need a new hat, and if I don't get it, you won't need one.
TO: Cheshire Cat
FROM: Quick Rabbit
SUBJECT: Important Meeting
BODY: Don't be late for our very important date!
TO: Quick Rabbit
FROM: Cheshire Cat
SUBJECT: Directions
BODY: Am I going this way or that to meet you?
TO: Cheshire Cat
FROM: Red
SUBJECT: Grumpy Cat
BODY: What are you smiling at?
```

And `output.txt` looks like: 

``` text
WR=#Fkhvkluh#Fdw
IURP=#Uhg
VXEMHFW=#Juxps|#Fdw
ERG\=#Zkdw#duh#|rx#vplolqj#dwB

TO: Cheshire Cat
FROM: Red
SUBJECT: Grumpy Cat
BODY: What are you smiling at?
```

## Step 1: Getting Started
Take a look at the [javadoc](https://csu-compsci-cs163-4.github.io/Lab12EncryptedMessageApp/package-summary.html) and take note of what methods you need to create from scratch, which ones you need to modify from Lab 10, and which ones you already did and don't need to change. `NOTE:` The ArrayList in `MessageApp` needs to be changed from private to public for testing purposes. Make sure you update that in your code. Also, we have provided a new `MessageMain` .java file above for you. It contains added functionality. Take a look at what it does and update your code. Also notice that there is no src folder this time. This is on purpose, as you will be working in the project that you created for Lab 10. (Feel free to make a duplicate project and call it Lab 12, but keep working with the code you already wrote.) You may also need to look at your `searchHelper()` method in `MessageApp` and make sure that when you change the `messageToString()` method in `MessageView` to `toString()` in `OpenMessage` that you replace the old call to `messageToString()` to the new `toString()`.

## Step 2: Implementation
Follow the [javadoc](https://csu-compsci-cs163-4.github.io/Lab12EncryptedMessageApp/package-summary.html) and write some code. Make sure to write tests for your code as you work on each method.

## Step 3: Finishing up
To turn in your assignment, click through the link on Canvas, upload your files to Zybooks and click submit for grading. Note you can do this more than once.
