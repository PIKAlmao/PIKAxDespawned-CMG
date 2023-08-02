---
description: Connection issues with resolutions. Credit to Bean (updated by myself)
---

# 🔧 Connection issues

If there is ever a server outage that is related to CMG's infrastructure or through FiveM's infrastructure then there will be a message in the #status channel at the top of the discord. There are no expected wait times for incidents to be resolved when it is FiveM's infrastructure. So before trying to troubleshoot your issue check #status for any ongoing problems.

You can also see a more in-depth status through the status sites below.

**FiveM** - [Here](https://status.cfx.re/)

**CMG Studios** - [Here](https://status.cmgstudios.net/)

Before ruling out that any issues that you are facing are to do with CMG specifically it would be beneficial to read the official Cfx.re client issues FAQ found [here](https://docs.fivem.net/docs/support/client-issues/) in order to complete basic troubleshooting of your issue.

## Common Errors :warning:

There are quite a few common errors when connecting to the server you might face commonly and there will be resolutions attached to each explained error.

### "Your account is still connected to the server"

This commonly happens if you have been timed out from the server due to your current network conditions and the solution is to wait out the 120 seconds and then connect again once you have waited.

<figure><img src=".gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

### "Steam account not found"&#x20;

The reason this message appears when you try to join the server is because your steam account is an identifier for the server (to detect ban evaders / cheaters etc...), to fix this issue, you must close fivem fully, then go and open your steam fully (you must have an account), then you can launch fivem again whilst still having steam fully open and you'll be able to join the server perfectly fine. (It does not matter which launcher you have gta purchased on whether it's epic games, steam or the rockstar launcher, you just have to follow the steps above).

<figure><img src=".gitbook/assets/image420000.png" alt=""><figcaption></figcaption></figure>

{% hint style="success" %}
Press **F8** on your keyboard to open the Console and then type **Connect s1.cmg.city**
{% endhint %}

## Client-sided Issues

These are issues that are with your host machine that prevent you from joining the server and their resolutions.

### "Invalid modified game files (x64f.rpf)"

This server does not allow the use of modified game files like fps booster packs. If you're unable to join the server because of this then remove any modified game files you added.

<figure><img src=".gitbook/assets/Modified game files bruu.png" alt=""><figcaption></figcaption></figure>

This is a common error where either your FiveM cache is full and it is causing assets fail to download which prevent you from connecting or where you have no or little free memory left on the drive you have FiveM installed on.

<figure><img src=".gitbook/assets/useful 1.png" alt=""><figcaption></figcaption></figure>

{% hint style="success" %}
To solve this you can clear your Cache by following the steps below \
\
<mark style="color:green;">**1**</mark> - Right click **FiveM** on your desktop and click **Open file Location**\
\
<mark style="color:green;">**2**</mark> - You should then be brought to the start menu folder where you then need to repeat the same step to **Open file location**\
\
<mark style="color:green;">**3**</mark> - You should then be presented with a couple folders which you should then click **FiveM application data**\
\
<mark style="color:green;">**4**</mark> - Once you are in that folder if you open the folder **Data**\
\
<mark style="color:green;">**5**</mark> - Once you are in that folder if you open the folder **Cache**\
\
<mark style="color:green;">**6**</mark> - Once you are in that folder if you open the folder **Server-cache-priv**\
\
<mark style="color:green;">**7**</mark> - Delete **ALL** files in the folder except the two folders within it which can be done with **CTRL+A** to select everything and then hold **CTRL** and deselect the two folders by clicking on them\
\
<mark style="color:green;">**8**</mark> - Empty your recycling bin!
{% endhint %}
