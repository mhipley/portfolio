---
layout: default
title:  "Onboarding"
categories: [ux, ui, branding, graphic-design]
time: "Q1 2019"
client: "Withfriends"
tags: [sales, research, onboarding, wireframing, Sketch, Balsamiq, front end, growth hacks]
glance: ["875% increase in new accounts per month", "average onboarding time reduced to less than 4 days from 12 weeks", "70 new clients generating revenue in first full month after launch"]
slug: withfriends-onboarding
permalink: /work-samples/:slug/
summary: "Withfriends is a platform that allows cultural businesses and organizations to sell memberships. I redesigned the onboarding process to drastically reduce the volume of new clients generating revenue."
---
[Withfriends](https://withfriends.co) is a platform that allows cultural businesses and organizations to sell memberships. The key mechanic for this is a ticketing upsell, and our go-to-market niche was small music venues in New York. Ideally, small businesses would be able to quickly make an account, list and promote their events, and begin effortlessly selling monthly memberships to their fans. In reality, it was anything but easy for our leads.

From the initial prototype of the product until January 2019, the Withfriends platform was limited to a private beta, where all accounts were manually onboarded. The process of account activation, from initial sales call to first revenue, took an average of 12 weeks, sometimes as long as a year. After extensive research and a redesign of the entire onboarding experience, this was **reduced to less than 4 days** on average. Additionally, this resulted in **an 875% increase in new accounts per month**, between December 2018 (8 new accounts) and February 2019 (70).

I began the research process by working closely with the sales team to identify the most common personas found in our accounts. A typical problem of onboarding was that often, the user who created the Withfriends account wouldn’t have enough power within a given business to make all of the onboarding decisions. So, accounts would linger on one step or another until a consensus was reached or the responsible party was able to make a decision. Some accounts included decision-makers who made decisions on a monthly or quarterly basis, further roadblocking the process.

<div class="device border-frame"><a href="#" data-featherlight="/assets/images/posts/onboarding-mindmap.jpg"><img src="/assets/images/posts/onboarding-mindmap.jpg" alt="Personas mindmap, made in collaboration with the sales team." title="Personas mindmap, made in collaboration with the sales team." class="device-interior"></a></div>

##### Personas mindmap, made in collaboration with the sales team.

The sales team identified specific users who matched key personas, and I was able to conduct one-on-one interviews with these users to better understand their roadblocks. I also went on site visits to existing accounts and prospective leads to better understand the day to day operations of the businesses. These site visits often provided valuable insight. For example, a number of users rarely had time in front of a laptop or desktop computer, so it was clear that the new process needed to be mobile-first.

I then worked with the sales team and engineering to determine the bare-minimum amount of information and content needed to successfully run an account to better identify roadblocks. These roadblocks fell into 3 main categories:

1. **Content roadblocks.** Most accounts had never run a membership program before, and it was overwhelming to design one from scratch. Additionally, when trying to help clients, the sales team was often asking questions that were difficult to answer. Ex., organizers had trouble estimating how many events they ran per year even though they could easily list off their upcoming events for the following month.
2. **Ownership roadblocks.** Often the user who created the account wouldn’t have access to the business’s bank accounts, and couldn’t directly connect Stripe. The account would be stuck in setup until another user joined the process to connect the account to Stripe.
3. **Technical roadblocks.** The purchase flow for tickets included a mandatory video placement because early accounts had promotional videos. Most new accounts didn’t have a promotional video, and the engineering cost of removing this mandatory field was high. Accounts would be stuck in setup because the purchase flow couldn’t go live without a video. There was also no means of quantifiable bug tracking.
4. **Sales roadblocks**. The sales team would spend months courting an account that ultimately needed features Withfriends could not provide. There was a bad cycle of promising features to open a conversation that the engineering team ultimately couldn’t deliver. After several months of costly sales work, the potential account would move on.

Each of these roadblocks needed a strategic removal or circumvention. Some of my solutions included:

1. I designed a default membership program, with pricing based on qualifications that we could ask the user during account creation. The qualification questions were designed to be effortless for potential users, in place of the previously confusing and involved conversations with the sales team that might take weeks. Users were more likely to edit and promote a default program than they were to create one from scratch.
2. The engineering team updated the platform so that it automatically creates Stripe accounts for all Withfriends accounts that could immediately collect revenue. Users were more likely to go to the trouble of connecting a Stripe account to their bank account if it was already collecting revenue from memberships and events tickets.
3. Since the engineering cost of removing the mandatory video placement was high, I commissioned an artist to make a generic promotional video to be the default for all accounts. The video cheaply solved the technical problem and was also usable as social media content for Withfriends. We also implemented user tracking with FullStory, which gave us immediate insight into bugs and roadblocks.
4. I redesigned the landing page for Withfriends to better prime the right kind of user for signing up for an account. We could cut back on bad leads by clarifying who should be using Withfriends and find the right kind of user by emphasizing existing features. Additional documentation of the lead page process is available [here](/work-samples/withfriends-lead/).

I was able to redesign the onboarding process into a series of steps that any lead could complete in minutes: 

<div class="device border-frame"><a href="#" data-featherlight="/assets/images/posts/onboarding-flow.png"><img src="/assets/images/posts/onboarding-flow.png" alt="Brainstorming: the new steps in the onboarding process." title="Brainstorming: the new steps in the onboarding process." class="device-interior"></a></div>

##### Brainstorming: the new steps in the onboarding process.

And turn those steps into wireframes and visual mockups to guide engineering:

<div class="device border-frame"><a href="#" data-featherlight="/assets/images/posts/onboarding-primer-wireframe.jpg"><img src="/assets/images/posts/onboarding-primer-wireframe.jpg" alt="Wireframe: a new primer page design clarifies what Withfriends does and gives examples of businesses who use the platform." title="Wireframe: a new primer page design clarifies what Withfriends does and gives examples of businesses who use the platform." class="device-interior"></a></div>

##### Wireframe: a new primer page design clarifies what Withfriends does and gives examples of businesses who use the platform.

<div class="device border-frame"><a href="#" data-featherlight="/assets/images/posts/onboarding-ui.jpg"><img src="/assets/images/posts/onboarding-ui.jpg" alt="Sketch mockup: the new onboarding flow was also an opportunity to roll out a new UI, designed for better clarity, trust, and accessibility. " title="Sketch mockup: the new onboarding flow was also an opportunity to roll out a new UI, designed for better clarity, trust, and accessibility. " class="device-interior"></a></div>

##### Sketch mockup: the new onboarding flow was also an opportunity to roll out a new UI, designed for better clarity, trust, and accessibility. 

<div class="device border-frame"><a href="#" data-featherlight="/assets/images/posts/onboarding-questions1.jpg"><img src="/assets/images/posts/onboarding-questions.jpg" alt="Wireframe: an early version of qualification questions, with additional notes for the engineering team w/r/t intent." title="Wireframe: an early version of qualification questions, with additional notes for the engineering team w/r/t intent." class="device-interior"></a></div>

##### Wireframe: an early version of qualification questions, with additional notes for the engineering team w/r/t intent.

<div class="device border-frame"><a href="#" data-featherlight="/assets/images/posts/onboarding-liveqs.png"><img src="/assets/images/posts/onboarding-liveqs.png" alt="Screenshot: qualifications used to segment accounts and set pricing for the default program." title="Screenshot: qualifications used to segment accounts and set pricing for the default program." class="device-interior"></a></div>

##### Screenshot: qualifications used to segment accounts and set pricing for the default program.

After a 3-step sign up, users are sent to a dashboard that is already ready to generate revenue. Users can immediately promote their membership program and begin listing events and selling tickets.

<div class="device border-frame"><a href="#" data-featherlight="/assets/images/posts/onboarding-dash-wireframe.jpg"><img src="/assets/images/posts/onboarding-dash-wireframe.jpg" alt="Wireframe: the new accounts dashboard, with notes about some concerns around UI behavior." title="Wireframe: the new accounts dashboard, with notes about some concerns around UI behavior." class="device-interior"></a></div>

##### Wireframe: the new accounts dashboard, with notes about some concerns around UI behavior.

<div class="device border-frame"><a href="#" data-featherlight="/assets/images/posts/onboarding-membership.png"><img src="/assets/images/posts/onboarding-membership.png" alt="Sketch mockup: a sample account with an automatically generated membership program." title="Sketch mockup: a sample account with an automatically generated membership program." class="device-interior"></a></div>

##### Sketch mockup: a sample account with an automatically generated membership program.

In addition to redesigning the primary onboarding experience, I also designed a system of smart alerts to keep users engaged with the platform and reduce support and sales labor. Documentation of the smart alerts system is available [here](/work-samples/smart-alerts/).