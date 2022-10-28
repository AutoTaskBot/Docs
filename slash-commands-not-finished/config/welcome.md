---
description: Configure the welcome message with an optional welcome image!
cover: ../../.gitbook/assets/welcome-img.png
coverY: 119.10460863204096
---

# 👋 Welcome

The welcome module is a nice way to welcome new members on your server! With this nice custom image, the new members are more attracted (only text is annoying...)

<figure><img src="../../.gitbook/assets/welcome-img.png" alt=""><figcaption></figcaption></figure>

## Get the current welcome config

Type <mark style="color:blue;">/config welcome get</mark> to get the current welcome message, image and what is enabled like below :

<figure><img src="../../.gitbook/assets/config_welcome_get.png" alt=""><figcaption></figcaption></figure>



## Define anything in the welcome config

To define the welcome message, just use the <mark style="color:blue;">/config welcome set\_msg</mark> command, then click on the button and type the welcome message in the FIRST field. The second field is only to help you with variables and to use as a draft.

To set something else like the welcome channel, or if it's enabled or not, use the <mark style="color:blue;">/config welcome set</mark> and enter the values that you want to change. For example:

<mark style="color:blue;">/config welcome set channel:#new-channel</mark> to only change the channel\
<mark style="color:blue;">/config welcome set channel:#new-channel img\_enabled:False</mark> if you want to change the channel and if the image is sended!
