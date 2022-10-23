# Blockchain_to_digitize_banking_system
## build a blockchain-based ledger system
###Installations:

![image](https://user-images.githubusercontent.com/69637182/197027429-aec47239-775c-466c-8a59-81f5687c53a3.png)


Pychain Ledger Structure provided to make ceratin updates:

### Step1:
Create class Record(sender, receiver, amount),
Create another class Block hashing function inherit class Record,
lastly chain class called Pychain: put class Block into List and set hashing difficulty to  4 zeros by keep incrementing the nonce which miners is looking for 
nonce and calculated hash that eplaines proof of work mechanism.


### Step2: 
display our result by using framework called Streamlit: Basically this software is easy to use by;
Creating Title "PyChain"
![image](https://user-images.githubusercontent.com/69637182/197032475-c4794796-51aa-4599-a0b9-6b5316f0ad54.png)

3 inputs Boxes ("sender, receiver, amount)
add block button
and the end: display our transaction and Validate Chain button 

![image](https://user-images.githubusercontent.com/69637182/197032619-504630ed-52da-4036-b001-2e8919a2e0ec.png)
![image](https://user-images.githubusercontent.com/69637182/197033485-82df0e53-3aa1-49b9-8402-433e1c62d003.png)

also we added side bars for Block Difficulty and Block inspection each time we add a new block 
![image](https://user-images.githubusercontent.com/69637182/197032768-bcfa6631-a206-4e50-8814-48fafb58bd7e.png)

### Winning Hash

![Winning_Hash](https://user-images.githubusercontent.com/69637182/197172325-f2301629-71c2-4d95-a63b-e46afe2b4589.jpg)




