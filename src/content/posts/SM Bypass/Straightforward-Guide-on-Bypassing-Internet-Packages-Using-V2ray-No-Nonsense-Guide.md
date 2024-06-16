---
title: "Straightforward Guide on Bypassing Internet Packages Using V2ray : No Nonsense Guide"
date: 2024-06-09T22:09:40+05:30
description: 'How to Bypass SM Packages'
image: ''
tags: ['Windows','How-To','V2Ray']
category: 'Tech'
draft: false
---

Here's how to Utilizing V2Ray to overcome ISP Data Package Restrictions, Especially for **Zoom Conferencing Package**.

### What Is V2Ray ?

 Well you could say V2Ray is like a **Regular VPN on steroids**, "in a way" because it offers more flexibility, features and sh!t.

### Prerequisites
Before we begin, makesure you have these following things in line:

- A Windows computer with administrative access
- A V2ray server (self-hosted or a subscription from a service provider) -- There are free services like [FastSSH](https://www.fastssh.com), [VPN Jantit](https://www.vpnjantit.com)
- V2ray client software for Windows

### How To Install V2Ray On Your Windows PC ? 
* First Head towards to Github and download V2Ray Software     
**[Link](https://github.com/2dust/v2rayN)** (**V2rayN-With-Core.zip**)

Head towards to link and download the latest release.


![V2Ray Release Page](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgWIlg5dZxl1unwwFjcyTly5Y0OJTSfEfeJWeKluHTYna4gXM9cnPykTmNsHu5KnhB8o7xm7nz1RaVuhbpTzG1uLDN8cLbWcgUrEbZOxpoYzFFM-Sm-uD1wHkgyapPSnUvoYtNxf2ZsnThJ-ThZ0JgMK4ELzm7hCytr7wTHnhko_O9R-mHj5tJBSe6AGA-W/s1280/V2Ray_2.png)


Execute the V2Ray software, and you will see an interface like this :


![V2Ray Software](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEih_CGLvS1oKYja8A8dI5wJd5lEvE_F9knSuY8retl3zShQvi5AQPaECR2EOgQLmMxm67cS3JEX-AHlK-Oe4_PCrA9nGEDQbipcNhQjPLlv43PjjYqcvlg5P_uOiXHY49TkKGfeusPNTWyByMKYH6jJwilr098dhYFpwX5q415Q0opc0s_2-s0BKE1_5xkC/s1070/Screenshot%20(53).png)

### How To Make a V2Ray Account ?

You can make a server on your own or you can use a thirdparty service. I'm gonna use #Fastssh.com to create a V2Ray config for free just to demonstrate the method.

- - Head over to the site V2Ray section and create one for you just like this :
![FASTSSH](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhdutdRqpxcYDLoL5nj-nHASJH_3uvurS_CcUSP4CeJfsW4qHNirv282whg9bDVouHXWmsa8ohJVcNlwLsYfPvaQv1pd5rVSHZPOee2BRGkQ_FWazUKEsjVOKQz-i27Mp_2HJQ38cIvVfJzv6QjSF-ePZbDzErFU0Lj5mjJp-7owPX5DDJxqW5U7oIc2Khy/s1280/Screenshot%20(55).png)

**You don't have to fill SNI Host right away.**

- After that, Copy the first config, which is Port 433 TLS/SSL.
---
### How to setup the config you made earlier in V2Ray Software ?

- Open V2Ray Software again and Press **Ctrl + V** on your keyboard or Head over to Server Section and Click **"Import Bulk URL from ClipBoard."**

If all went well,This section will appear.

![V2RaySoftware](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhQLbIIO20SltwdiDnT2oYqnoD7iGcmrYHtGrM9mX0NAILyY6YnpVkJq_1GThzUrb45aOED7N9D5xVisct6_S-nDe9sBN9Eve_kvzVNk27ot1B0py9-Iq3am5OHtB2oiQCba-jG0YJ9mXsl1mirAcqaKfkQ18zFiLq9Rf3XNdXfpn0VAkEQlHMImO96gAhF/s883/Screenshot%20(56).png)


#### - Then Double Click On that section & Change these things :

1. Camouflage Type     | None
2. Camouflage Domain   | **st2.zoom.us** (If you are attempting to bypass a WhatsApp package, use www.whatsapp.com, etc. Currently, I'm trying to bypass a video conferencing data package from zoom.us. If the domain is not working, try subdomains belonging to the same provider.)
3. Fingerprint         | Random
4. AllowInsecure       | True

![V2Ray Config Settings](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEi102X7v0o1CQNYFxTHwRX8_5NJjpsj7cHjS2DdZHOuerjPkN0oI_zShD5Vsib9Fnr8HyYfJ7mdSFBgtHWOB53_4Y7400NNmLDTeGdK_uuqUkq40-v-pCyiuvwr5R1SOhC-nNIB-Nk7SdhR5pZ934hsRAYb4pmdafxwZmoDbQ-byGYdx_E74mr7BvFv8t-Z/s1154/Screenshot%20(57).png)

After those changes, You can press confirm button and exit that dialog.

### How to start V2Ray?
You can select the config and press the Enter key on your keyboard.

That's it. If your SNI Host(Domain/Subdomain) and V2Ray configurations are correct, now you will be able to use free internet through your limited data package.


## Extra
### How to find a SNI for your speific Data Pakage from your ISP?
**You can use a software like BurpSuite or Online Tools like subdomain finder to scan the domain and find subdomains that may work well with V2Ray & Tunneling.**

*  Here are some popular SNI Hosts used to bypass data packages:

WhatsApp 

            www.whatsapp.com
            web.whatsapp.com

Facebook

           www.facebook.com
           mbasic.facebook.com

Youtube

            www.youtube.com

Zoom.us 

           zoom.us
           st1.zoom.us
           st2.zoom.us
           st3.zoom.us     


peace  :)