---
title: Create and use the Green Wallet
post_status: publish
featured_image: /_images/_Self-Custody-Green-Wallet-vimeo.png
---

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/887498272?h=921eac6775&amp;badge=0&amp;autopause=0&amp;quality_selector=1&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" style="position:absolute;top:0;left:0;width:100%;height:100%;" title="How to Use a Bitcoin Self-Custody Wallet: Blockstream Green"></iframe></div>

<div style="margin-bottom:30px;"></div>

## Here's what you will learn

Find the chapter marks on the right bottom of the video.

- Install and open a new wallet
- Backup your wallet with a seed phrase
- Secure your wallet with a 2FA and a pin
- Set your wallet preferences and adjust the app settings according to your needs
- Receive and send bitcoin
- Create several accounts and wallets
- Restore your wallet, e.g. in case you lose your phone
- Check your used Bitcoin addresses

## Additional Information
* [Green Wallet](https://blockstream.com/green/) by Blockstream
* [CoinGecko](https://www.coingecko.com/)
* Block Explorer: [Blockstream](https://blockstream.info/) & [Mempool.space](https://mempool.space/)
* Secure Messenger: [Signal](https://signal.org/)

## Transcript

Hello everyone. Today I want to show you how to install the Green Wallet, which is a self-custody Bitcoin wallet. 

First we go to the app store and download and open the wallet. Then it asks you to agree to the terms of service. We do that and say "Add wallet". Now Green Wallet asks you for your usage data to improve the wallet. I say "don't collect my data". Next step is new wallet. And now this is a critical moment because now you have to write down your seed phrase, which is also called recovery phrase. And you also should only write it down on a sheet of paper. Don't do any screenshots, no digital copies of it, don't put it into the clipboard or send it with an email. Write it down on a sheet of paper. And it's really important to write it down in the correct order. That's why you see the 1, 2, 3, 4, 5 until 12. And then the wallet asks you to check the seed phrase with a small test. Basically, then you can set the pin for the wallet. The pin I'm setting is of course just a test pin and I'm also not using that wallet, because of the seed phrase you saw. 

Now we are creating an account and now you can choose between a single-sig, which is native SegWit or a so-called 2FA account. This gives you more protection because you have need to have a second method of authentication to send the bitcoin. So, now we set up a 2FA protected account. Now it's set up, but it's still missing the 2FA. And this is now what we are setting up. We are adding a second factor of authorization method and the wallet offers a few: email, SMS, call or authenticator app. I'm always using email and the authenticator app. Why? Because I don't want to be depending on text messages. They are also insecure and I also can't depend on a call because my number changes and I don't like to to add my phone number to a wallet. So, as you can see, this is the second method. Now I'm adding a authenticator app. This one is called Raivo and you have to connect it with the Green Wallet by scanning either a QR code that the Green Wallet gives you, or you can also copy the content basically of the QR code and add the connection manually in the Raivo authenticator app. And then the authenticator app always gives you a new code whenever you need it. So here we have to confirm that we want to use the authenticator app with the new created connection to the authenticator app. And that's why I have to add here he code. And as you can see now both authentication methods are set up. Then there's a possibility to set a threshold. So basically it means under that amount you don't need to do the 2FA authentication. So you can basically say if it's a amount under a hundred US dollars or 50 US dollars, I don't need to do the 2FA. And then there is a expiry function, which means if you ever should lose access to one of those two authentication methods, then the wallet resets that after a certain amount of time. Then another thing is you can rename the created account. So you can say office or private or whatever. I'm leaving the 2FA there to know it's a 2A account. 

Then you can go to the wallet preferences, to the settings. You can find the denomination and exchange rate here that you can set. So it's basically, do you want to have bitcoin or SATs or bits as your units? And the second thing is where does the wallet take the reference exchange rate from? I'm mostly using CoinGecko and the currency I want to show the value of my bitcoin in. Then you can see, you can change here the pin if you ever want to change it. You can also change the 2FA methods here. You can have it auto log-out of the wallet. You can set it to the minutes you like. So basically you have to log in again with your code pin and then you can here go back to the seed. You can see it here again if you've lost it. And as you can see, I'm using my iPhone passcode now to enter the wallet again. To confirm that I'm allowed to see the recovery phrase, it's basically to just check back. Do I have the word secured in the right way? You should do that every like couple of months, actually. 

You can also create the second account in the wallet. And the great thing is that the second account will have the same seed as the first account. And these are single-sig natives addresses that begin with bc1 at the beginning. They have lower fees, but you can't add 2FA to this account. So usually this is enough security. The 2FA is a great way, if you can't afford a hardware wallet for instance. Then set up a 2FA account. If you have a hardware wallet, and this is just for daily spendings, you can use the single-sig account. So now you can see you have two accounts in one wallet and they only have one seed. 

Now let's receive some Bitcoin. What do you have to do? You have to click "Receive Bitcoin", and then the wallet shows you one of many Bitcoin addresses in your wallet or that the wallet is managing for you. And the sender has to scan the QR code of this address. You can also send the address to the sender. If you're not nearby, then the sender adds the amount he or she wants to send you. This was a time where we had very low fees as you can see. And then the sender has to set the transaction fee and you know that the lower fee, the longer it takes, the higher the fee, the faster the transaction will be confirmed. Now the sender sends the transaction after adding the amount and the transaction fee, and now you see the green "transaction incoming notification" on the left hand wallet and now it's receiving. And of course it's still unconfirmed because with Bitcoin transactions we have to wait at least 10 minutes until it's mined and in a block and settled. You can look up your transactions in a block explorer, for instance, in the blockstream.info explorer or the Mempool.Space Explorer when you don't know what's going on and why it's not being mined. But you can also add a note to this specific transaction so that later on, you know what it was or why you sent it. It's still waiting to be confirmed. 

Now, in between, let's go into the app settings. You go back to the first screen and below you find the app settings. There are a lot of possibilities. You can connect your wallet with TOR, you can connect it through a proxy, you can enable Testnet Bitcoin and whatever. But this is when you are in the next stage. 

Now everything is set and now we are doing something. We are imagining our phone is dead, we are deleting the app. And if you need to buy a new phone, you then just restore from the seed. You have it somewhere secured and then you do the whole process again. You say "add wallet". But this time we want to restore a wallet. We don't say "new wallet". We restore from the seed. And then the wallet asks you for the seed phrase that you wrote down at the beginning. You also can set the pin again. And as you can see, the wallet is back and it also has received our transaction from before in the meantime. And here is everything again. And you can see we have one confirmation out of six. 

Then receive a Bitcoin transaction with a certain amount when the recipient is not around and can't scan the QR code. You go to "more options" and there you can say "request amount". Then you can enter the amount of bitcoin, the value in USD or in your currency you want to receive from the sender. And then you can share the address with a messenger. I always use the Signal messenger because it's the most secure, but you can also send it via WhatsApp or even via email. Yeah, but it's not as private. 

Then you can also view all addresses that you have used in your wallet. And this page shows you if you received one transaction or not and you actually should not reuse your addresses. The wallet will always present you a new address. Always take a fresh address. You can copy it from here and send it to someone. Some exchanges want you to prove that an address is yours. You can do it here. You can authenticate addresses here. 

Then you can also add a second wallet, not only accounts A wallet has accounts within it, but you can have a second wallet in the app as well. That one will have a new seed phrase, so you do the same as before. Write down the seed, take a pin, and then you have a second wallet and you can do the same as before if you want. If you want to split office and a private wallet for instance. Now you have two wallets.
