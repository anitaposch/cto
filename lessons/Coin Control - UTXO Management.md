---
title: Coin Control - UTXO Management
post_status: draft
featured_image: /_images/CoinControlUTXOManagement.jpeg
taxonomy:
    post_tag:
        - advanced
---

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/843671126?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;" title="075 Coin Control - UTXO Management"></iframe></div>

<div style="margin-bottom:30px;"></div>

## Additional Information
* [Sparrow Wallet](https://sparrowwallet.com/) for coin control (UTXO management)

## Transcript

The amount of fee you are paying for a Bitcoin transaction is not depending on the amount you're sending. It's not like in the banking system, when you send a high amount, you will pay high fees. You can send, I say like a value of $5 in Bitcoin. You can also send a value of 5 billion euros in Bitcoin and you will pay the same transaction fee, because the transaction fees in Bitcoin are derived from the data size of your transaction. And that's why you can actually save fees if you are doing UTXO management, coin control. 

This for instance, is the Sparrow wWallet where you can do coin control. When Bitcoin blocks are full, the highest fee transactions are confirmed first. And while your Bitcoin wallet shows a single balance that's in your wallet, as you can see here, it's like 17 million satoshis. In reality, it's like here 15 UTXO and every UTXO has a certain value attached to it. It's like what you received on a Bitcoin address. UTXO stands for unspent transaction output. It's basically identifying the place on the blockchain where the value that you own is stored. As soon as you send a transaction, it's not an unspent transaction anymore. Now you can see that basically the total balance of your wallet is split up into many UTXO, into many Bitcoin addresses. And if you want to make a payment from that, your wallet will select as many UTXOs as unnecessary to reach the amount of Bitcoin you wish to send. And as I said before, on-chain transaction fees are calculated based on the size in bytes and not the amount of satoshis sent or the amount of bitcoin sent. So the more UTXOs are required on the input side, the higher the fee will be. And from a cost perspective, you will want to consolidate UTXOs, meaning fewer UTXOs with larger amounts because then if you want to send a larger amount, the wallet doesn't have to choose several UTXOs, but can use only one which reduces the amount of data that is needed to send a transaction. So it's a difficult equilibrium, because that consolidation of coins or UTXOs has privacy trade-offs. If you link any UTXOs, you also connected to being owned by the same person. So larger UTXOs mean you will dock more of your stack to anyone you pay in the future. Remember that if you're doing coin control. So you want to reduce the number of UTXOs you have in your wallet while being mindful of the privacy concerns. And last but not least, if you want to consolidate your UTXOs, do it when the fees are low, which is usually on the weekends. So here you can see I could select two UTXOs and then I can send those together in one transaction. 

This of course is advanced knowledge and you don't need to know that when you start using Bitcoin. So please, don't be discouraged by that. Start using it, start practicing and you will deepen your knowledge further and further, also with the videos and tutorials I'm providing here in my program.
