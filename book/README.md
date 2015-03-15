SaaS Questions
==============

All businesses are now SaaS / PaaS businesses, whether they know it yet or not. Any business could benefit dramatically from a SaaS product. Companies that don't know how to leverage them, and don't make it a core competency will constantly struggle to compete with those that do.

Starting around 2004, companies who recognized this fact have had an ongoing compounding advantage over those who fail to. That doesn't mean a little mom and pop restaurant can't survive without a SaaS strategy, but it does mean that a restaurant who launches an innovative app or platform will be able to build brand recognition and grow customers & locations faster. The PaaS could be location / meetups, recipes, gamified visit incentives / loyalty programs, you name it. Be creative! Whatever moves your KPI needles.


Says Who?
---------

Hi, my name is Eric Elliott, and I've been in the SaaS business since before the term was coined. Pre-Y2k, a friend and I set out to build a new software business. Boxed software was still commonplace, and we thought we could leverage the power of the internet and a large collection of usage data to do more than traditional boxed software could do.

We set out to build a serious user-customizable sales compensation processing service that could be whiteboxed and hosted online for B2B customers. We made the choice to let our first big customer have a lot of access and influence, which turned out to be a bad thing. Lesson learned.

A short while later, I started a consulting business. I set out to teach other companies how to build software products that could be hosted online.

My first idea for a consulting business was SEO. It was hot at the time. Google emerged out of nowhere, and was giving AltaVista a serious run for their money. Around that time, articles questioning the ROI of SEO started appearing on UseNet (this was before the term "blog" was coined). Of course it's common knowledge now that SEO has really serious ROI, but back then, many businesses were still figuring out how to monetize their online properties. I kid you not, companies were putting product catalogs online with phone numbers in them to try to sell products, and there was serious speculation about whether or not consumers would ever trust credit card processing online. Amazon was still a new, young startup selling only books, and eCommerce was just beginning to be taken seriously.

> AltaVista was the first dominant search engine, and it seemed impossible that Google would ever catch up. No matter how dominant you are now, the first hard lesson in SaaS was taught by Google: *never stop innovating.* You'll never be too big to take down.

I realized my competitive advantage: I grew up in a family owned business. By the time I was 8 years old, I knew I wanted to run my own business someday, and I devoured business books and magazines every chance I got. I knew the fundamentals of business, and most SEO consultants only knew a few common tricks for keyword stuffing and programmatic link-spamming (both tactics that Google quickly caught onto and penalized for).

While most SEO companies could only make vague hand-wavy promises about ranking #1 on DogPile.com (yeah, that was a real search engine), I promised to look at the company's own profile of custom key performance indicators. I would not charge an arbitrary number, or based on rankings. I would charge based on setting measurable business goals. If I couldn't move the KPI dashboard needles, the customer didn't pay.

That wasn't such a tough sales pitch, even after SEO fell into controversy. Yes, I did SEO, but in order to move those needles, I had to do much more. I had to make sure that the clients were selling something, engaging visitors, and growing online business month over month.


The Customer Feedback Cycle
---------------------------

My first client had products to sell. I helped them build a shopping cart, I helped them drive traffic with SEO, content marketing, and email marketing, and then we got ready to count the sales. There was just one problem: There were no sales to count, and we had no visibility into the problem. We had web server log files, but back then, they didn't tell us much. Not how long they stayed, not where most users were coming from in any readable way, nothing really vital. We needed more. Then I had an idea: What if my client had some JavaScript on the page and we could tell what users were clicking on -- or if they clicked on anything at all before they left?

Over the next couple of years, I spent a lot of time figuring out better ways to capture user data. Before Google Analytics, before Optimizely, before plug-n-play click heatmap services, we needed to know. So I recorded data and played with different weightings.

What's important to track? What is just noise with no predictive value? Hypothesis, test, refine, over and over again until I'd gathered enough automated customer feedback from all of my clients to plug that data into a machine-learning engine to build one of the first automated software usability hueuristics testing tools... and it worked. Brillaintly. Some of my clients went from mom and pop shops to millionaires in such a short time, I kicked myself repeatedly for charging way too little.

Eventually, I took what I learned about user experience optimization to a little fitness startup in Miami called Zumba Fitness. They were well into a very healthy growth stage. This company didn't exist five years before, and it was doing millions in sales at a pretty good clip. From the outside, Zumba is a network of fitness classes that shares latin-flavored music and dance moves with local groups all over the world. From the inside, Zumba Fitness is part fashion design shop, part exercise program development, but fundamentally a software development company. They had a homebrewed, highly custom shopping cart, an instructor dashboard, a class search, even video games.

I was in charge of their in-browser architecture, which is over-stating things a bit, because when I got there, it was more like a random jumble of half-legible error-ridden jQuery and there was no architecture to speak of at all on the client side. Few people in the company took JavaScript seriously.

> JavaScript is the standard programming language of the web, and the only programming language supported by all popular web browsers. In other words, if you develop web hosted software, **JavaScript must be a first-class citizen in your tech stack.**

My job was to clean things up, help grow a team who could help on the client side, write a style guide for developers, mentor developers, and generally lay the groundwork for architecture to come.

We had a population of Zumba customers who got a sneak peek at the rewrite, and we got some great feedback. Luckily, I decided to run some in-person user studies. I pulled people into a conference room, sat them in front of a computer with a list of tasks, and recorded video, asking them to think out-loud. I didn't help or instruct them, I just let them go, watched, and listened.

Those kinds of usability studies only take a few participants to spot glaring issues. Between the automated measurements, the surveys, and the in-person user studies, we were able to identify some important things. The logs were showing shockingly high cart abandonment rates. That means people loaded a bunch of items into their carts, clicked the checkout button, tried to enter payment information, but gave up before ever completing the checkout process.

The in-person studies revealed why: Users were getting stuck on the form validation. It wasn't obvious enough which fields were invalid, or how to correct invalid fields. Based on that, I was able to fine-tune the user experience so that the forms were more user-friendly and helpful, with inline errors that described in simple terms how to correct the error, and realtime error status display that updates with every keypress.

After a few days of work collaborating with a brilliant CakePHP developer, cart abandonment rates improved by double digits: a difference worth millions of dollars to the company. Best. ROI. Ever.


The Only Thing That Matters
---------------------------

**Make your customers fall in love with your software.** If your users love what you do, you can figure out how to make a lot of money. Make them so happy and excited to use the product that they'll recommend you every chance they get.

You make a good enough product to attract a few thousand die-hard evangelists trumpeting your genius for free, and you will make a lot of money. Being selflessly committed to your users is rewarding work. You get the pleasure of knowing that you're making people happy, and you get financially compensated, too. Making your customers happy -- no, I don't mean happy -- I mean crank up the Daft Punk and have a robot rock party on the moon happy. You make your customers happy, and you can write your own ticket. You can do anything you want.

Until you have an army of work-for-free die-hard evangelistic fans, **nothing else matters**. Not your schedule. Not marketing hype. Not your dream features. Not the tool chain you're using, or whether or not you have free lunch for the employees.

**The only thing that matters in software development is that your users love your software.**


The Questions
-------------

I spent the first half of a long career learning how to make online properties move the KPI's of countless businesses. From tiny mom and pop companies trying to make an extra $10k/month, to enterprise scale companies trying to make an extra $1,000,000/month on a new product, and companies trying to grow from the former to the latter.

In my experience, every SaaS business needs to ask itself these questions. You'd better have good answers to most of them. If you don't, your competition will catch you and crush you, or you'll have a hard time gaining enough momentum or utilizing your resources enough to get through critical phases in your company's evolution.

Not all of these questions have equal value, and with so many things to consider and limited resources, it's important to look at priorities. Find your biggest pain points. What's hindering your progress the most right now? What would you gain by fixing that problem?

Chances are, you can identify 2-3 problems to focus on this week that will move those KPI needles in significant ways. Keep in mind, if you boost the creative productivity of your development staff, that brings compounding ROIs for the life of your business. Now is the time to pluck that low hanging fruit.

You can't do everything right now, but there's always something you can do that will have a great ROI.


### Business Fundamentals

**What is your mission?**

I'm not talking about lofty, mostly ignored mission statements, I mean what motivates you fundamentally? What are you really passionate about? When there are choices to make, do you have a beacon ahead -- a long-term goal that can keep you heading in the right direction every day? Each individual should have a mission, and the organization should have a mission. Those missions should be compatible.

**What customer need are you filling? (Read: What is your product / market fit?)**

**Why are you the right team for this?**

**What is your advantage over competitors?**

**Why would it be hard for somebody else to copy you?**

**Is there enough money in the business to keep the company stable for the next year and a half or two?**

**What's your biggest challenge?**

**How do you make money?**

**How do customers find you?**


**Is your app beautiful?**

You should guage user sentiment about the design of the app periodically. Second to app performance, no other metric can match the ROI of beautiful design. Great design easily trumped fancy features in every usability analysis I have ever conducted over a career spanning more than 15 years. If your app has only one great technical feature, in almost all cases, improving the app's design will have a larger impact than adding another great feature.


**Are you tracking KPI's? (What gets measured gets managed!)**

**Are your KPIs on a dedicated always-visible dashboard?**

I like to make sure KPIs are posted somewhere that the whole staff can see them. They don't have to have specific numbers listed. It's typically good enough to have guage needles with red / yellow / green zones. Here are some metrics I like to always display:

  - Net promoter score / customer sentiment (weight actual share rates more than survey responses as the business data grows. The open-ended "why" question from NPS will always be valuable, though, so don't abandon NPS surveys entirely.)
  - k-factor / viral factor ( k = i * c )
    + i = invites (shares / recommendations) sent per user
    + c = invite conversion rate
  - Month over Month growth (segment end users, paying users, B2B / enterprise)
    + Number of users at the beginning of each month
    + Number of new users
    + Number of lost / inactive users
    + Churn rate
    + New user activation rate (% customers who completed first important activity)
  - Customer Lifetime Value (CLV)
  - Cost Per Acquisition (CPA)
  - MRR
  - Sales pipeline (track and capture each step in sales pipeline)
    + Leads / Appointment Bookings / Appointment booking rate (Repeat for each sales funnel transition, display as new leads / converted leads)

It should be clear to all employees that their primary responsibility is to help move those needles, with a focus on customer happiness.


### Development process

Unless you're still at the stage where you're banging out a one-weekend proof of concept prototype, your next goalpost should be reaping the compounding returns you'll gain by getting this stuff done sooner, rather than later. Hire a good dev/ops team *early* so you can start experimenting and iterating *quickly*. The faster you can iterate, the faster you can validate.

Until all of this stuff is handled, it should be second priority only to producing a Minimal Valuable Product.

* Do you have a good suite of happy path delpoy smoke tests and functional tests?
* Do all your modules have API surface area unit tests?
* Do you have server load tests set up?
* Do you use automated continuous integration tools, e.g., Jenkins, TravisCI, CircleCI, etc...?
* Do you validate each build with all of the above mentioned test suites automatically?
* Do you have a feature toggle system?
* Do you practice continuous deployment?
* Analytics
  * Are you collecting the appropriate amount of data from your user interactions?
  * Are you mining that data to deliver important insights that could potentially move the needle on your KPIs?
* Are all of these things automated?


### Technology Goal Posts

App startup & web page load times have a huge impact on abandonment rates. The faster you can deliver your UI, the better your user experience (UX) will be.

**Are your average client -> server -> client round trip latencies under 100ms?**

**Are your server response times under 30ms?**



### Culture and knowledge sharing

**Is your company friendly to remote work?**

I have a whole article on why you should be coming soon.

**Do you set aside time for learning and invite experts to come speak at your company learning events?**

**Do you have a culture of peer review?**

Knowledge sharing encourages cross polination. Mistakes can be quickly caught and improved on. Even junior engineers can bring fresh ideas and innovation to a business. Code reviews give everybody a chance to communicate, quality check, and appreciate each other on a regular, ongoing basis.
