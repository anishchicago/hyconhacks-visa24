# hyconhacks-visa24
This is our submission to the Hycon hackathon, September 2018 in Seoul
https://hacks.hycon.io/


## Inspiration
Our team has a very international background. We all had to deal with immigration services at some point in our lives. To register for health insurance we may need to confirm our employment status. When signing up for a bank account we may need to confirm our residency address and so forth. To prove those things, it usually involves getting a document with an official stamp from a government office. Those offices are only available at certain times of the day, not on weekends or holidays. We wanted to come up with a better way to easily and securely complete those cumbersome tasks using blockchain technology.

## What it does
- It stores a citizens visa status in a smart contract on the ethereum blockchain. 
- Immigrants can access their own data at any time of the day without visiting a government office.
- That data can be accessed only by authorized parties. A) the government and B) the immigrant. 
- Additionally every now and then the Government will have to change the visa status. They can do that without input from the immigran
- Every information put in by the government can have a expiry date

## How we built it
We built three frontends for the different use cases we have. 
- A immigrant verifying his/her visa status
- A immigration officer first registering the immigrant at the border, including the persons private passphrase
- A government official who is changing the visa status without input from the immigrant

Information about an immigrant is retrieved using an anonymous hash. 

## Challenges we ran into
- Getting the concept for privacy right was hard in the beginning. 
- Making sure all data is anonymous on the public blockchain.
- Designing a robust permission system on the public blockchain

## Accomplishments that we're proud of
- Collaborating in a team of 5 people who previously didnt know each other and finishing a project in 36 hours
- We think that a solution like ours can solve real social issues

## What we learned
- How to write and use smart contracts
- It's impossible to have a perfectly secure solution
- We learned how to use javascript web3 to access smart contracts

## What's next for visa24
- implementing a frontend to manage government officials permissions
- convincing the government to use it
