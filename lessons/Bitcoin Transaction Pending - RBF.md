---
title: Bitcoin Transaction Pending - RBF
post_status: publish
featured_image: /_images/RBF.jpeg
---

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/847261072?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;" title="076 Bitcoin Transaction Pending - RBF"></iframe></div>

<div style="margin-bottom:30px;"></div>

## Additional Information
* Learn more about transactions in [my talk from the IDBC2023](https://my.cracktheorange.com/deep-dive_what-is-bitcoin-txs-mining/)
* Check your pending transactions and current fees in the block explorer: Mempool.space

## Transcript

When we are talking about transaction fees in Bitcoin, we also need to talk about a small problem that might come up when a lot of people at the same time are using Bitcoin and that is that one of your transactions is stuck in the mempool and isn't being mined. So that mostly shows up when you see a transaction is pending. 

For instance, you can see on that screen from a wallet I used, I used a too low transaction fee and the bitcoin is pending. So for hours and days, it was not confirmed. Since new blocks are mined every 10 minutes or around every 10 minutes, it'll take an average of at least 10 minutes until your transaction is confirmed. If you set the transaction fee too low, like I did in that example, your transaction might be pending for a longer period as the mempool gets cleared and miners begin to reinclude transactions with lower fees. 

Here you can see one of my transactions, which has been trapped in the mempool for a month. So here you see it's still unconfirmed, and here "time" I sent it a month ago, and you also can see its priority is very, very low. It's number 4,717 under 41,610 transactions in the mempool. What you also can see that back then I was using a wallet without RBF, which is the technique we are talking about in that video. 

RBF stands for replace by fee. And either the wallet didn't do it in a default manner or I didn't say yes, I want to use RBF for that transaction, and meaning that this transaction was not RBF enabled. So I couldn't do that, what I'm going to show you now. So how can you unstuck a transaction with replaced by fee in general? You can also wait. Sometimes low fee transactions remain valid for days and will eventually confirm, but sometimes they don't and they are really dropped. They fall out of the mempool and then you have to send them again. But as long as they are pending and you have replaced by fee activated, you can do that.

How to speed up a slow payment? I had a transaction recently in March, 2023 that was stuck for a week. I paid my dentist in Zimbabwe and used a low fee of 2 sats/vByte. The number of transactions in the mempool reached a new all time high these days, which even kicked my transaction out of the list of transactions in my blue wallet. So I didn't see it there anymore. As the congestion eased, the transaction showed up in my wallet again. It can happen, as I said before, that the transaction falls out of the mempool completely. In that case, the funds will reappear in your wallet and the money needs to be sent a second time, as I said. 

But before doing that, you can look up your transaction in a block explorer like mempool.space. I found mine there because I still knew the Bitcoin address I was sending to. As I saw it in the mempool, I knew that I didn't need to resend it. I had the option to use replace by fee in the blue wallet. I just needed to wait until the transaction reappeared in the blue wallet. And then I did that. I opened the transaction, the detail of the transaction, and then I said "bump fee", and then another screen opened up like this. And there you can choose higher fees. So basically I pay again for the fees, I put in more money so that the miners will take my transaction and put it into their block. As you can see, the blue wallet gives you an estimation of when your transaction will be settled. So if I pay 4 satoshis per byte, my transaction is estimated to be settled in 10 minutes. So I set the fee higher, clicked on create, and the wallet shows me another screen where I can confirm and send the higher transaction fee. After that, I went back into the block explorer to see what changed. And you can see now it says this transaction replaced this transaction, so replaced by fee, but the transaction is still unconfirmed. So RBF replaced by fee is a technique that allows you to speed up a pending transaction.
