Deploy introduce:

Deploy coin is designed on DogeCoin fork (DRC20). We created a special schema on deploy coin which will be the utility part for Deploy is Decentralized tx Transaction part of POW (proof-of-work) and peer-to-peer cryptocurrency. The development of the Deploy coin utility will certainly be carried out in the future as the cryptocurrency technology itself develops and follows the needs of its users.

----------------------------------------------------------------------------------------------------------------------------------------------------------
Dogecoin

Introduction:
In the world of cryptocurrencies, where cutting-edge technology and financial innovation often take center stage, one digital currency stands out with its quirky origins and lighthearted nature. Dogecoin, born out of an internet meme featuring a Shiba Inu dog, has captured the attention of millions, gaining popularity and becoming a symbol of community, generosity, and the power of online communities. What started as a joke currency has now become a significant player in the crypto market. In this article, we will delve into the fascinating story behind Dogecoin and explore its rise to prominence.

The Origins:
Dogecoin was created in December 2013 by software engineers Billy Markus and Jackson Palmer. They initially designed it as a fun and light-hearted alternative to Bitcoin, the leading cryptocurrency at the time. Drawing inspiration from the popular "Doge" meme, featuring a Shiba Inu dog with captions written in Comic Sans font, Markus and Palmer aimed to create a more approachable and less intimidating digital currency.

Community and Philanthropy:
One of the key factors contributing to Dogecoin's success is its vibrant and dedicated community. The Dogecoin community, often referred to as the "Doge Army," has embraced the meme-centric culture, creating an inclusive and supportive environment. The community's members, known as "Shibes," actively engage in online forums, social media platforms, and even real-world events to discuss and promote Dogecoin.
Another notable aspect of the Dogecoin community is its philanthropic nature. From its early days, Dogecoin gained recognition for its charitable initiatives. The community has raised significant amounts of money for various causes, including sponsoring athletes, funding clean water projects in developing countries, and supporting disaster relief efforts. The generosity of Dogecoin holders has earned the cryptocurrency a reputation for being a force for good.

Market Performance and Popularity:
Despite its humorous origins, Dogecoin has experienced significant market success. In early 2021, the cryptocurrency gained unprecedented attention when a series of tweets from celebrities, including Elon Musk, brought it into the spotlight. This surge in popularity resulted in a meteoric rise in its value, making Dogecoin one of the top ten cryptocurrencies by market capitalization.
However, it's important to note that Dogecoin's market performance can be highly volatile. Its value is subject to fluctuations, often influenced by social media trends and online hype. As with investment, potential buyers should exercise caution and conduct thorough research before getting involved.

Future Outlook:
As Dogecoin continues to gain recognition and adoption, its future remains a topic of speculation and debate. While skeptics argue that its reliance on memes and social media buzz makes it an unstable investment, proponents believe that its strong community and established use cases, such as tipping content creators and supporting charitable causes, will contribute to its long-term sustainability.
Furthermore, the ongoing development and improvements within the Dogecoin ecosystem, including efforts to increase scalability and enhance security, indicate that the cryptocurrency is more than just a meme. Dogecoin has managed to carve out its own niche in the crypto space, attracting a dedicated following that goes beyond its meme origins.

Conclusion:
Dogecoin's journey from an internet meme to a prominent cryptocurrency is a testament to the power of online communities and the ever-evolving nature of the digital landscape. It has shown that cryptocurrencies can be about more than just financial gains, promoting the values of generosity, community, and lightheartedness. While its future remains uncertain, Dogecoin's impact on the crypto industry serves as a reminder that innovation can come from the most unexpected places, and even a meme can inspire a phenomenon.

----------------------------------------------------------------------------------------------------------------------------------------------------------
DRC20 

ComparisonDRC-20 and BRC-20 :
Gas Fees :
- DRC-20 (Doge): Offers fast transaction speeds with low fees.
-	BRC-20 (BTC): Often experiences congestion and high fees.


Consensus :
-	DRC-20 (Dogecoin): Benefits from having one of the largest communities outside of BTC/ETH. It also possesses the natural advantage of meme properties, which have the potential to go viral.
-	BRC-20 (Bitcoin): Relies heavily on Bitcoin whales and has fewer new users actively participating in the community.
Decentralization :
-	DRC-20: Achieves 100% decentralization.
-	The inscription ledger of DRC-20 tokens is stored on the ETHF chain.
-	BRC-20: Relies on centralized wallet-based storage.
-	The inscription ledger of BRC-20 tokens is centrally stored within wallets.

Limitations and Conditions :
-	DRC-20: Allows the use of three or four characters for token names, eliminates the risk of double-spending, and offers flexible transaction capabilities.
-	BRC-20: Limits token names to only four characters, does not support upgrades, involves double-spending risk, and does not allow for transaction cancellations.
These differences highlight the contrasting features and characteristics between DRC-20 and BRC-20 tokens.
DRC-20 inscriptions will only exist on the PoW chain, achieving multi-chain storage and maintaining decentralization.

• DRC20 is a token standard for the Dfinity blockchain.  It was created by an anonymous developer in May 2023 and is designed to be faster and cheaper than the previous standard, BRC20.

DRC20 tokens are created using a process called minting.  Minting requires a user to have a certain amount of Dogecoin in their wallet.  Once a user has minted a DRC20 token, they can then transfer it to another user or use it to purchase goods or services.
DRC20 tokens are secured by the Dogecoin blockchain.  The Dogecoin blockchain is a decentralized network of computers that verify and record transactions.  
This makes DRC20 tokens very secure
Here are some of the key features of DRC-20 tokens:
-	Faster: DRC-20 transactions are processed much faster than BRC-20 transactions.  This is because DRC-20 uses a different consensus mechanism than BRC-20.
-	Cheaper: DRC-20 transactions are also much cheaper than BRC-20 transactions.  This is because DRC-20 uses a different fee structure than BRC-20.
-	Easier to use: DRC-20 tokens are easier to use than BRC-20 tokens.  This is because DRC-20 tokens are compatible with more wallets and exchanges than BRC-20 tokens.
-	DRC-20 tokens are a new and innovative way to use the Dogecoin blockchain.  They offer a number of advantages over other types of tokens, such as speed, cost, and ease of use. DRC-20 tokens are still in their early stages of development, but they have the potential to revolutionize the way we use the Dogecoin blockchain.

Here are some of the benefits of using DRC-20 tokens :
-	Speed: DRC-20 transactions are processed much faster than BRC-20 transactions.  This is because DRC-20 uses a different consensus mechanism than BRC-20.
-	Cost: DRC-20 transactions are also much cheaper than BRC-20 transactions.  This is because DRC-20 uses a different fee structure than BRC-20.
-	Ease of use: DRC-20 tokens are easier to use than BRC-20 tokens.
Source : Unielon and anonymous

----------------------------------------------------------------------------------------------------------------------------------------------------------

DRC-20
Cardinal theory can facilitate fungibility on dogecoin
Create a drc-20 with the deploy function
Mint an amount of drc-20's with the mint function
Transfer an amount of drc-20's with the transfer function. 

Mint drc-20
Inscribe the mint function to your cardinal compatible wallet. Make sure the ticker matches either a) the drc-20 you deployed in step 1, or b) any drc-20 that has yet to reach its fully diluted supply. Also if the drc-20 has a mint limit, make sure not to surpass this.
It's a example of mint script as following:

{ 
  "p": "drc-20",
  "op": "mint",
  "tick": "dply",
  "amt": "100"
}

command parameter description
Key	Require	Description
p	yes	Protocol: Helps other systems identify and process drc-20 events
op	yes	Operation: Type of event (Deploy, Mint, Transfer)
tick	yes	Ticker: letter identifier of the drc-20, equal to 3 or 4 characters
amt	yes	Amount to mint: States the amount of the drc-20 to mint. Has to be less than "lim" above if stated

----------------------------------------------------------------------------------------------------------------------------------------------------------

Transfer drc-20
Inscribe the transfer function to your ordinal compatible wallet. Make sure the transfer function inscription information is valid before inscribing
It's a example of transfer script as following:

{ 
  "p": "drc-20",
  "op": "transfer",
  "tick": "dply",
  "amt": "100"
}

command parameter description
Key	Require	Description
p	yes	Protocol: Helps other systems identify and process drc-20 events
op	yes	Operation: Type of event (Deploy, Mint, Transfer)
tick	yes	Ticker: letter identifier of the drc-20, equal to 3 or 4 characters
amt	yes	Amount to transfer: States the amount of the drc-20 to transfer.

----------------------------------------------------------------------------------------------------------------------------------------------------------

Deploy drc-20
Inscribe the deploy function to you ordinal compatible wallet with the desired drc-20 set. It's a example of deploy script as following:
{ 
  "p": "drc-20",
  "op": "deploy",
  "tick": "Dply",
  "max": "100000",
  "lim": "1000"
}

----------------------------------------------------------------------------------------------------------------------------------------------------------

command parameter description

Key	Require	Description
p	yes	Protocol: Helps other systems identify and process drc-20 events
op	yes	Operation: Type of event (Deploy, Mint, Transfer)
tick	yes	Ticker: letter identifier of the drc-20, equal to 3 or 4 characters
max	yes	Max supply: set max supply of the drc-20
lim	no	Mint limit: If letting users mint to themsleves, limit per cardinal
dec	no	Decimals: set decimal precision, default to 18
burn	no	burn some token
func	no	specific rules such as mining rules, rewards rules ...





