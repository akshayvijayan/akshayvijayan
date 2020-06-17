---
title: "How to map custom domain to Blogger"
date: 2020-06-16T12:13:30+05:30
tags: [Space]
---

Blogger is a easy platform for blogging which doesn't requires any technical skill. Usually a blog started in blogger will have an address which ends with .blogspot.com. We can change this domain to a custom domain which we like to use for the blog(We need to purchase domain from any of the service provider. Google also provides domain service)

After buying a domain, log into blogger.com using profile. Navigate to settings which is seen on the left menu bar. 

Click on the option "Custom Domain"
![Custom Domain](/img/blogger_custom_domain.png)

Now enter your domain & click on save. Most probabily the following error(Error image 1) will come.

![Custom Domain](/img/blogger_domain_mapping.png)
				

Log into the domain service provider's website, and move to DNS settings.
![DNS settings](/img/cname_blogger.png)

Add the following A records as shown below:


| Type	| Name  | Value 		 |
| ------|:-----:| --------------:|
| A     | @ 	|  216.239.32.21 |
| A     | @     |  216.239.34.21 |
| A     | @     |  216.239.36.21 |
| A     | @     |  216.239.38.21 |


Now add CNAME as shown in error image (1):

For example

| Type	| Name  		  | Value 		                            |
| ------|:---------------:| ---------------------------------------:|
| CNAME | www 			  |  ghs.google.com                         |
| CANME | hhgnqw2o63c3    |  gv-jorkv3bpltbxs3.dv2.googlehosted.com |

>Don't add the value displayed here. It will be different for different sites. Add the value displayed in your blogger platform (Refer error image 1)


And who would we be if we didn’t have that fear?

We’re afraid of space and stillness and silence because it highlights the uncertainty, instability, groundlessness, insecurity, shakiness that lie underneath every second of our lives. We’re afraid of having to face this instability and uncertainty, of having to feel the fear of it.

Without the fear of all of the uncertainty that is highlighted by space … we become free.

I know in my life, when I allow myself to have stillness, silence, solitude, simplicity and space … it leaves room to face whatever is coming up for me. It gives me room to fully feel any feelings that I’ve been avoiding. It allows me to be more honest with myself, instead of using distractions and busyness to cover up what I don’t want to see.

And in the end, I develop trust that the space is not something to be feared, but rather something to be treasured. A gift, filled with learning and not knowing and shakiness and beauty.

You might try allowing more space to be in your day, without filling it:

* Take some time between tasks for stillness.
* Sit out in nature, in silence, without technology.
* When you notice yourself reaching for your phone, pause. See if you can just be still, just savor some space.
* When you feel uncertainty or instability in your life (hint: it’s always there), let yourself feel it. Be present with it, without needing to run or avoid.
* When you feel fear, be open-hearted with it and allow yourself fully feel it, being friendly with it. Your relationship with fear will change if you become friendly with it.
* Do less, and trust that things won’t fall apart. Or if they do fall apart, you can be present with that instability.
* When you’re in line, driving, eating, walking, exercising … see if you can do those things in silence, without technology, without needing to do something “useful.” Find the value in these spaces.
* Notice who you are without the fear of space.

Savor these spaces, their deliciousness. Savor the groundlessness, as something filled with freedom if we learn not to fear it. Be present with the fear and uncertainty, as good friends not as enemies.

Let your heart be open raw tender and vulnerable, and your mind embracing the spaciousness of the vast blue sky of open awareness.
