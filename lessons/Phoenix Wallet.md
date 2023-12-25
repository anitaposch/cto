---
title: Phoenix Wallet - Use Lightning with Self-Custody in 10 Minutes
post_status: publish
featured_image: /_images/_Thumbnail-Phoenix-Wallet-Tutorial.jpeg
---

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/896849263?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" style="position:absolute;top:0;left:0;width:100%;height:100%;" title="Phoenix Wallet Tutorial"></iframe></div>

<div style="margin-bottom:30px;"></div>

## Here's what you will learn

Find the chapter marks on the right bottom of the video.

- How to download and install the wallet
- How to create a new wallet
- How to backup your wallet with a seed phrase
- How to adjust the app settings according to your needs
- How to receive on-chain sats and open a new channel
- How to look up the transaction details
- How to receive a Lightning payment on your wallet
- How to send sats from your wallet
- How to create an invoice to receive a Lightning payment
- How to send sats from Phoenix (Lightning) to a Bitcoin on-chain address
- How much the payment fees for Phoenix are

## Additional Information
* [Phoenix Wallet FAQs](https://phoenix.acinq.co/faq) by Acinq
* Block Explorer: [Mempool.space](https://mempool.space/)
* [Boltz Exchange](https://boltz.exchange/swap) Swapping Service

## Transcript
Hello everyone. Today we are looking into the Phoenix Wallet, which is a self-custody Lightning wallet. Basically a node on your phone. At phoenix.acinq.co/faq you find answers to the most common questions. Now let's start. 

Let's download the wallet either from the PlayStore for Android or from the Apple store, and then install it. 

We are creating a wallet now and securing that with the seed. And then we will set up our Lightning channel. First, back up the seed. As always, you can display the seed here and write down these 12 words in the correct order on a sheet of paper. Don't make any screenshots or digital copies. It'll always gives you access to your funds. 

Now let's take a look into the settings. What are the most important settings? First, you can change the units. So you can choose which bitcoin unit you want to see. You can also choose in which fiat currency your bitcoin amount shall be displayed. There are a lot of fiat currencie in the Phoenix wallet, as you can see. I'm going to choose the South African Rand. You can also set an invoice description. So every payment you receive will have a description that you can set here. I'm choosing tips. So every invoice I send out and the payment I receive will have the description tips attached to it. In the channel management option, you can set the maximum fee that you are willing to pay to open your channel or to add new amounts to the channel. So when the channel needs to increase the liquidity, then you need another on-chain transaction. Then we have payment history. This will show you all payments that you've received or sent. Access control, you can lock the wallet the same way as your system is locking your phone. Under recovery phrase, you can find the seed again in case you need to check it. In wallet info, you will see your node ID and your swap in wallet. That's the wallet where funds are being sent to and where automatically a Lightning channel is being created or it's sent to the Lightning channel. And the final wallet is your on chain wallet derived from the seed. This means, when channel needs to be closed that's the final wallet where the funds will be sent to. Payment channels, here we will find the payment channel as soon as we have created one. Close channel, only close the channel if you know what you're doing. Your funds will be redirected on-chain to your final destination wallet. Okay, now our wallet is ready. 

Let's receive some sats to open our channel. It's advisable to open a bigger channel and then you can send the amount of bitcoin back to your other wallet. So then you have liquidity for the future. If you don't do that and you only open a small channel, then you will need more liquidity and need to buy liquidity or to send more funds, more on-chain funds maybe to your channel. And that costs transaction fees on-chain transaction fees. And now in times where the on-chain fees are so high, it's advisable to better maybe buy some liquidity from Phoenix, which is possible in your wallet or use Lightning funds to make your channel bigger. So use a higher amount than $20 if you can afford and send the amount you don't need back. Then you have a reserve in your channel to add funds, incoming funds. 

So we are now sending an on-chain transaction to the Phoenix Wallet. And now we are waiting for the payment to be incoming so that the Phoenix wallet then opens a channel. So here we see now that a payment is incoming and we check on mempool.space for the confirmation. The transaction is still pending. It'll take 10 minutes, 20 minutes maybe, depending on the transaction fee you set. Now, as you see, we've got one confirmation and now we are checking, yes, it has arrived. But to open the channel, we need 3 confirmations. So we need to wait longer. Now we got 3 of 3 confirmations. And now we go to payment channels and we see that we have successfully opened a channel on the Lightning Network. Your wallet is now a part of the Lightning Network. Here you can see the fees that have been paid, the mining fees and the service fees from Phoenix for an incoming Lightning payment that opened a channel. 

You can look up the fees in detail on the detail page where you also can check the transaction ID. Like this transaction ID is the same as this one here. This was the transaction that we sent on-chain to Phoenix's on-chain address. And then Phoenix used a second on-chain transaction. On the bottom, you can see the ID, which opened the channel. 

Now let's receive sats from another Lightning wallet like the Breez wallet. Now in the Phoenix wallet, you create an invoice, the other person can now send you a tip, and now you find the description again that we put in before as an invoice description. So from the Breez Wallet, we are sending 100 satoshis via Lightning to our Phoenix wallet. And here it is. And this is a Bitcoin payment. It's super fast received, you don't need to wait for confirmations, and you have basically almost no fees when receiving Lightning. And we can also see the channel, not the size hasn't increased, but the amount of funds, the amount of sats inside of the channel has increased. 

So now we send some sats from the Phoenix wallet. Now in the Breez wallet, we create an invoice for 121 sats, call it "test receive" and create the invoice. We can send it via a messenger or the other person is around. Then we can scan the QR code of the Lightning invoice and we can check everything if, if everything is correct. And as you can see, Phoenix charges a small fee for sending satoshis. And it's there. Now let's take a look to the payment channel. What I wrote on the left hand side is actually incorrect. The payment channel has not gotten smaller. The funds inside of the payment channel have gotten less because we sent something out. 

Now let's receive an amount. We create an invoice, we add an amount to the invoice. So 300 satoshis, and now we are creating the invoice, including the amount. We are scanning the invoice QR and we can see it's 300 satoshis for tips. And it's there. This is how fast Lightning payments are going. Let's look into the payment channel. The funds inside the channel have changed again. 

What you also can do with Phoenix is send from Lightning to an on-chain address, but it's not really a good idea. Why? Because when you send from your Lightning channel to an on-chain address, the capacity of your payment channel decreases. It's getting less. You don't want that. Better to use Boltz exchange swap service to swap out from Lightning to on-chains to save for the long term because you might not want to have a high amount on a Lightning wallet, which is a hot wallet. You can't secure it with a hardware wallet, but you can do that with on-chain. And secondly, in this example, I used a very small amount to send it on-chain, which is a mistake now because now the fees have risen so much that the fee for one transaction that I would need to pay this small amount from my on-chain UTXO would be higher than the value of the on chain UTXO. So for several reasons, use Lightning to send from your Lightning wallet. 

And now let's look into the fees. Sending via Lightning costs you 0.4% + 4 sats per payment. Receiving via Lightning is free, except when your Lightning capacity doesn't allow to receive anymore. Then the channel needs splicing and needs more capacity. And this will cost you the mining fees from on-chain and 1000 satoshis one time. Sending on chain costs you only the mining fees that you can set yourself (the on chain mining fees are that). And finally, you can request more inbound liquidity directly in your Phoenix wallet. So you won't need to send an on-chain transaction to increase the capacity of your payment channel. In a high fee environment like currently where you have sometimes $20, $30, $40 to pay for an on-chain transaction, it might be a great idea to request inbound liquidity directly in Phoenix. 

Thanks for watching. I've got one question for you. Did you know that all my work is free to use and I am not sponsored by any companies to stay an independent source of Bitcoin education and knowledge. Therefore, please consider donating towards my non-profit initiative Bitcoin For Fairness or join my membership program Crack The Orange where you not only can learn more about Bitcoin, but will also have access to me. You can ask me questions for my Live Call and you will receive the newest content first and be a part of a greater community of learners. You can learn more about these options at anita.link/donate. Thank you very much.
