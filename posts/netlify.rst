.. title: Netlify Exercise
.. slug: netlify
.. date: 2018-06-18 17:10:16 UTC-04:00
.. tags: 
.. category: win
.. link: 
.. description: Never do in ten blog posts what you can do in one.
.. type: text

**Rank your 5 favorite, and 5 least favorite, activities from this list: Here are things a support engineer at Netlify might do in no particular order. List 5 things that are your most favorite to do and 5 things that are least favorite.**

	Favorites:

	* Debug a customer's build using a programming language and framework that you've never seen before (this is right up there with deciphering the language of a hitherto undiscovered tribe in the Amazon)

	* Spot trends across many cases to improve Netlify's product and service (high-level analysis, yes!)

	* Help train and onboard new support teammates

	* Work with the development team to help design a new feature based on feedback from customers

	* Deliver a talk to many people you don't know at a conference or meetup


	Not favorites (nothing I’m morally opposed to, I’m just not itching to volunteer):

	* Respond to Netlify customers on Twitter

	* Dig through server logs to troubleshoot a customer's website behavior

	* Manage a Support team

	* Create video tutorials to help teach users a specific feature or use case

	* Receive occasional phone calls requesting support from our highest-value customers


**What is your favorite thing about providing technical support?**

	I love when support ends with a handshake of mutual benefit. Of course we all want that “aha!” moment of finding the bug and fixing the thing, but the best conversations are an exchange of knowledge. I like learning new ways of doing things, and seeing how people run their business and create inspiring projects. I imagine it’s kind of like being an auto mechanic; most of your conversation is about the maintenance or broken part, but you get to admire the rest of the car while you’re at it, and maybe get a snapshot of the person’s life and personality too.

**What did you think of our service during the time you used it?  Provide either some constructive criticism or some points that impressed you.  Be honest!  “It sucked” isn’t a wrong answer unless you don’t elaborate and provide some constructive criticism ;)**

	I was a little overwhelmed initially at the number of site generation tools to pick from, but of course if you have a particular filter in mind, it pares down pretty quickly. At any rate the volume is impressive. I also appreciated the dead-simple step by step instructions for installation and the thorough Getting Started guide. And it's *fast!*

**Talk about how you made your site and why you chose the tools you did.  Briefly explain a challenge you experienced in setting up this site and how you solved it.**

	I picked Nikola more or less at random from the middle of the pile. I didn’t want to use the most popular or least popular tool, and wanted to see the blog format.

	I experienced a few configuration errors along the way. I referred to GitHub’s docs to generate a new SSH key so I could deploy to my repository, and then used Netlify’s logs to rectify an incorrect assumption in my Deploy settings.

**Provide a link to documentation for a technical/developer-focused product, which you think are well done, and briefly explain why you think they are well done.**

	I think the documentation for JIRA is generally very well done. For example, `this article <https://confluence.atlassian.com/jirasoftwarecloud/processing-issues-with-smart-commits-788960027.html>`_ starts with brief high-level context, then goes into the details, and then provides specific examples for different use cases, including some edge cases. It’s concise, has exceptionally clean formatting, and includes relevant hyperlinks. I like how the navigation remains visible at the top, and there are clear paths to provide feedback or ask for more help.

**Why do you think SSL/HTTPS is important?**

	I think it’s best to operate under the assumption that any unprotected resource online can and will be exploited. This is crucial for the delivery of sensitive information of course, but also for “mundane” data, which can still be used in aggregate to profile and identify users.

**Explain, in a couple of paragraphs, what you think 2 major challenges around DNS configuration are for less-technical internet end-users.**

	I think DNS configuration can be challenging because (1) it’s not something most end-users deal with on a regular basis, if at all and (2) the details are much more opaque than “match the domain name to the server.” The horde of acronyms is intimidating, it’s easy to lose track of records, you don’t know that updating one protocol might mean you have to update others, and so on. Furthermore, the introduction for many people into DNS config is an error message, and that’s never an encouraging place to start.

**A customer writes in saying their “site won’t build”.  Compose your best short (2-paragraph) customer-facing answer, without any additional data, that could be useful in the generic case, but would also lead to a customer providing a more actionable response.**

	Hey John, thanks for reaching out! I’m sorry to hear you’re having trouble. Let’s see what we can do to get you up and running! First, if you haven’t already, I would check out our troubleshooting guide right here: https://www.netlify.com/docs/build-gotchas/. That addresses some of the more common build errors and settings to check. It may be an easy tweak.

	If that doesn’t seem to cover it, I’d be happy to take a look at your logs. On the Deploys tab in your Netlify account, just click into the log for your most recent attempt, hit Copy to Clipboard on the right, and drop that text into your reply. We’ll take it from there!

	Cheers,
	Joe

