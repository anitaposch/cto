---
title: Coin Control - UTXO Management
post_status: publish
featured_image: /_images/CoinControl.jpeg
taxonomy:
    post_tag:
        - advanced
---

## Video 1
<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/843671126?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;" title="075 Coin Control - UTXO Management"></iframe></div>

<div style="margin-bottom:30px;"></div>

## Video 2
<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/903170650?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;" title="What Is UTXO Management and Why Is It Important? Explainer: Impact On Fees and Privacy"></iframe></div>

<div style="margin-bottom:30px;"></div>

## Additional Information
* [Sparrow Wallet](https://sparrowwallet.com/) - Desktop Wallet for coin control (UTXO management)
* [BlueWallet](/https://bluewallet.io/) - Bitcoin Wallet for coin control (UTXO management)
* [BlueWallet Tutorial](https://youtu.be/NqY3wBhloH4) - Start Using Bitcoin in under 5 Minutes

## Transcript Video 1

The amount of fee you are paying for a Bitcoin transaction is not depending on the amount you're sending. It's not like in the banking system, when you send a high amount, you will pay high fees. You can send, I say like a value of 5 Eur in bitcoin. You can also send a value of 5 billion euros in bitcoin and you will pay the same transaction fee, because the transaction fees in Bitcoin are derived from the data size of your transaction. And that's why you can actually save fees if you are doing UTXO management, coin control. 

This for instance, is the Sparrow Wallet where you can do coin control. When Bitcoin blocks are full, the highest fee transactions are confirmed first. And while your Bitcoin wallet shows a single balance that's in your wallet, as you can see here, it's like 17 million satoshis. In reality, it's like here 15 UTXO and every UTXO has a certain value attached to it. It's like what you received on a Bitcoin address. UTXO stands for unspent transaction output. It's basically identifying the place on the blockchain where the value that you own is stored. As soon as you send a transaction, it's not an unspent transaction anymore. Now you can see that basically the total balance of your wallet is split up into many UTXO, into many Bitcoin addresses. And if you want to make a payment from that, your wallet will select as many UTXOs as necessary to reach the amount of bitcoin you wish to send. And as I said before, on-chain transaction fees are calculated based on the size in bytes and not the amount of satoshis sent or the amount of bitcoin sent. So the more UTXOs are required on the input side, the higher the fee will be. And from a cost perspective, you will want to consolidate UTXOs, meaning fewer UTXOs with larger amounts because then if you want to send a larger amount, the wallet doesn't have to choose several UTXOs, but can use only one which reduces the amount of data that is needed to send a transaction. So it's a difficult equilibrium, because that consolidation of coins or UTXOs has privacy trade-offs. If you link any UTXOs, you also connect it to being owned by the same entity. So larger UTXOs mean you will doxx more of your stack to anyone you pay in the future. Remember that if you're doing coin control. So you want to reduce the number of UTXOs you have in your wallet while being mindful of the privacy concerns. And last but not least, if you want to consolidate your UTXOs, do it when the fees are low, which is usually on the weekends. So here you can see I could select two UTXOs and then I can send those together in one transaction. 

This of course is advanced knowledge and you don't need to know that when you start using Bitcoin. So please, don't be discouraged by that. Start using it, start practicing and you will deepen your knowledge further and further, also with the videos and tutorials I'm providing here in my program.

## Transcript Video 2

I find it hard to understand UTXOs and how I do the coin control. Could you please explain it again in a more simple way? How important is it to do the UTXO management and which tools can I use to do it? 

Okay, I repeat. A UTXO, an unspent transaction output, is basically chunk of bitcoin that sits on a location on the blockchain, which is a Bitcoin address. A Bitcoin address can be empty, it can hold one UTXO (one chunk of bitcoin) or multiple UTXOs if you reuse the address. So let's assume you have a wallet and in that you have several addresses with chunks of bitcoin. Let's say you have one coin with 10,000 satoshis, another one with 10,000 satoshis, another one with 30,000 satoshis and one with 50,000 satoshis which is in total 100,000 satoshis. So these 10,000 satoshi chunks, the transaction fees will be higher than that amount that you have sitting in that address, in that UTXO. So assume, now you want to send someone 90,000 satoshis. Your wallet if it doesn't provide you with the possibility to do coin control, then your wallet will choose which coins to combine to the new transaction. So it might use one 10,000 satoshi chunk, the 30,000 satoshi chunk and the 50,000 satoshi chunk. Then it can send exactly the 90,000 satoshis but each of these UTXOs has a data size. So it's a little bit like imagine you want to send one PDF to someone. Then this one PDF has lower data size than if you were to send three of those PDFs. So it's the same way with UTXOs. The more UTXOs your wallet has to combine to build a new transaction to send it, the higher the fees because the transaction fees in Bitcoin are coming from the data size of the transaction. So that means if you had, for instance, an UTXO with let's say 300,000 satoshis on it and you could choose it via coin control then you would only need one of these UTXOs, one data size, one data set, to send which reduces your fees. So you can save on fees like that. 

So for instance in the BlueWallet you can do coin control. When you're preparing a transaction to be sent, you click on the sent button and then on the top right of the BlueWallet you see three dots, clicking on the dots opens a menu where you find the coin control and on that page you can see all the coins, all the UTXOs that you have in your wallet and can you can manually click on those that you want to combine. And in that way you can save on fees because you are so clever to combine the least transactions you need, the least UTXOs you need for that. And also, you can also do that in Sparrow. The Sparrow Wallet is a desktop wallet which you can also use in combination with your hardware wallet. And the Sparrow Wallet allows you to scroll through all the UTXOs within your wallet and you can select one or multiple of these UTXOs. It looks a little bit like a spreadsheet, you can delete one or more rows and then you can combine them and send them in one transaction. 

And this coin control management, the UTXO management, is not something, it's not a singular goal so you don't do it and then you're done forever. You basically have to constantly do it. So like I don't know, two times a year or something. To balance your priorities also between privacy, short-term fee savings and long-term fee savings and even the possibility to send you 20 euros for instance from your Green Wallet somewhere else. So having lots of small UTXOs is better for privacy because if someone gets your address they can look it up in on the blockchain and see how much bitcoin you have on that so it might be better for privacy. But it will cost you more fees if you want to send a higher balance, a higher amount and on the other hand having all your bitcoin in one big UTXOs and reusing that address over and over is not good for your privacy and security as well. 

So UTXO management is really something that also I'm working on. I have the plan to do a guide and a tutorial on that and to show you how that works because I believe this is really going to be important in the coming years and also for people who start using Bitcoin now.