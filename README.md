# Module_18_Assignment

This assignment is to create block for each transaction between sender and receiver, and reflect transfer amounts as well. From each block being created, I need to verify if each block or transaction can be sent out to the receiver under high security and monitoring.

Below are the pictures of web interface illustrates transaction record.

Each block represents a transaction. Below is an example of three transactions(blocks) that I have created. According to first picture below, each record include the name of sender, receiver and amount. In order to verify if each transaction(block) has been successfully go through, you can see the result below "True" by simply clicking the botton "Validate Chain". If the result is False, that means something wrong with the transaction. That is my way to verify the integrity of the data in the ledger. From the second picture "They Pychain Ledger", it shows the full information of each transaction, record, creator_id, hash, time of transaction and nounce(numbers of times to find leading four zero).

![Module_18_Assignment](./Transaction%20record.PNG)
![Module_18_Assignment](./The%20PyChain%20Ledger.PNG)

Also, I created a side bar to select the block difficulty(numbers of leading zero created for each unique hash). I have select Block Difficulty #4, which means heading "0000" at the beginning for hash. 

![Module_18_Assignment](./Side%20bar.PNG)

For Block Inspector to select and visualize each transaction(block), I create a scroll down list to select the transaction that I want to review.

![Module_18_Assignment](./Block%20Inspector.PNG)

