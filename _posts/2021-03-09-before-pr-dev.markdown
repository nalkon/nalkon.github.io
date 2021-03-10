---
title:  "What Do You Need To Know Before You Start Developing Your Product"
toc: true
excerpt: "In this blog series we’ll talk about the not-so-simple world of technical product development. Our hope is that it will help founders gain some understanding about what needs to be done and maximize their chances of success."

---
# Why Product Development Cannot Be Done As An  Afterthought
<!--more-->
Starting a new business is overwhelming. There are a lot of problems to solve: how to fund your startup; how to market your product effectively and within budget; how to attract customers; how to build your team when your resources are very limited, etc. etc. etc. It’s not a surprise then that many non-technical founders decide to outsource product development completely in hopes of unloading some of the burden to those who supposedly has the right expertise and credentials.<br>
<br>
Here is the thing, though… Your product is the heart that will pump blood into your startup. Every decision you make about product development affects your business directly and immediately from development and maintenance costs, to your capital raising ability. It affects marketing appeal and usability of your product, as well as your time and money. These are your most valuable resources, which you don’t have in abundance. You don’t want to waste them by getting scammed if the developers or agency you hired won’t deliver. What you want is for your product to be built on time and within budget in the right way that will allow for scalability and easy maintenance. That’s why you can’t fully entrust the development of your product to a third party. You have to, so to speak, keep the reins in your own hands.<br>
<br>
In this blog series we’ll talk about the not-so-simple world of technical product development. Our hope is that it will help founders gain some understanding about what needs to be done and maximize their chances of success.<br>
<br>
Let’s start...

# Before Product Development
These are necessary steps that need to be taken before you start product development, engage with an agency, or hire developers.

## Step 1: Translate Your Idea And Business Goals Into Technical Needs
**Technical requirements** document is the foundation of your product. It describes what the finished product will be like and how it will be built.
Why would you want to spend your time on creating technical requirements though? Because creating technical requirements forces you to analyze your idea and make sure:
* your product fills a real need
* features don’t pile up to create “feature monstrosity”
* product development is carefully phased out and prioritized in accordance with your business goals, marketing pace and funding
* product is robust and scalable

This way, when it will come to real coding, the development team will know exactly what they are building. It happens  often that the development team or agency does not deliver a product at all or delivers a product that is completely different from what was intended originally.  If this happens, it will be a waste of time and money for you. You want to avoid it. In addition, technical requirements provide you with information necessary to determine the scope of work, timelines, and budget.
<br>
<br>
Technical requirements document usually consists of  functional, non-functional and system requirements, as well as product architecture, and technological stack list.  The following sections describe each one of them shortly with a couple of examples, just to give you a general idea.

### Functional Requirements
Functional requirements describe how the product will work entirely from the user’s perspective. It doesn’t care how the thing is implemented. It talks about features. It specifies screens, menus, dialogs. Examples of functional requirements:
    * User can sign up by creating a new account
    * User can login to an existing account
    * User profile includes first name, last name, and address
    * User can edit user profile

### Non-Functional Requirements
​**Performance Requirements** <br>
Performance requirements describe how the product should behave under different conditions. Some typical performance requirements are:  response time, throughput, resources utilization, scalability, availability. Examples of performance requirements:
+ The page should load in no more than 2 seconds when the number of simultaneous users is more than 1000
+ The payment system should be available 99% of the time
<br>
<br>
<div>
  ​<b>Security Requirements</b><br>
  Security requirements describe a set of features to ensure your system, including your customers’ confidential information, is protected from unauthorized access and security breaches.
  Examples of security requirements:
  <ul>
    <li>User must change the initially assigned login password immediately after the first successful login</li>
    <li>Password must be encrypted and not visible by anyone except for the account owner</li>
    <li>The server must authenticate every request accessing restricted Web pages</li>
  </ul>
</div>
<br>
**Technological Stack**<br>
Decision about what technologies will be used to build your product is one of the most crucial ones. It will affect many things in your business: development and maintenance costs, skill set of the developers you hire, timelines, as well as performance and scalability of your product.  The reason it’s so crucial is because it is  hard and costly to change your technological stack later. The decision you make at this point will stay with you for a very long time.
<br>
<br>
**Product architecture**<br>
Software architecture is an equivalent of an architectural plan in construction. You can’t build a house without carefully planning it first.
Any product consists of a number of components. Product architecture describes each one of these components, and the relations and connectivity between them.
<br>
<br>
Let’s take a mobile app as an example. One component is the app itself that will run on a mobile device (front end). How do you build it in such a way that it runs seamlessly on any device and doesn’t drain battery? If you want every user that installs the app to create an account, you will need a database to store information about all these accounts. You might also need a database to store some elements of your app, like images . Should you use the same database to store images and accounts? Or two different databases? Or maybe you would want to use a CDN (Content Delivery Network)? How do you keep personal info you collect from your users secure? How do you build your system in a way that satisfies your performance and scalability requirements?
<br>
<br>
All these and many other questions will be answered by building the product architecture, a high level plan detailing how your product will be built. As your product evolves, the architecture will evolve too. New components might be added, 3rd party tools replaced by others, better hardware might become available, etc. But your product architecture always will be the foundation your product is built upon.
<br>
<br>
**System Requirements**<br>
After you have your architecture in place, you can identify what hardware configuration will be needed to build your product’s back-end infrastructure, i.e. what machines will be needed to host your web server, database server, and other components included in the product architecture.
One of the most important questions in regard with system requirements is whether you are going to host your back-end in a private cloud or use one of the commercial alternatives, and, if you are going to use one of the commercial clouds, which one is it going to be. There are pros and cons to each alternative, but here are several considerations to take into account:
* Commitment to use a commercial cloud provider is going to be a long term commitment. It’s not impossible to change cloud service provider, but it’s complicated and expensive to do so.
* The cost of cloud services will change tremendously as your business grows. What might look as insignificant amount to pay for your back end hosting at the beginning will become a huge expense as you scale. It is likely to become a huge expense even before your business is profitable.*(More detailed blog post coming soon. Stay tuned!)*

## Step 2: Build a Roadmap
Now, that you have your technical requirements and you know exactly how your product will be built, you can create your product **roadmap**. A **roadmap** is exactly what it sounds like: it is a document that will map development phases with scope for each phase (for example, MVP), timelines, and milestones. It is going to be one of your most frequently used documents once you start product development. This document will be updated frequently as you add or remove features, move them around from one version to another, or change timelines.

## Step 3: Estimate Cost Of Product Development
When you have your roadmap and product architecture in place, you can estimate how long it will take and how many people you will need to build every version of your product. Cost of development will vary greatly depending on the engagement model with developers. Your options are freelancers, dev shops, or full time employees, with freelancers being the cheapest option and full time employees the most expensive one. Don’t jump to the conclusions though. Every option has its pros and cons, and long term consequences should be carefully weighed against other factors *(More detailed blog post coming soon. Stay tuned!)*
<br>
<br>
On top of development costs, you have to take into account deployment and operations costs, namely building and maintaining your back-end infrastructure.


## Step 4: Hire Developers
After putting all pieces of the “puzzle” in place, namely knowing what you want to build, how long it will take, how much it will cost, and who you want to hire for the job, it’s time to hire developers. Regardless of what option you choose – freelancers, dev shops, or employees – you have to figure out a way to vet them properly, to make sure you hire the right people for the job. The cost of hiring the wrong people is very expensive.

# During Development
## Closely Monitor Development Process
Finally, after doing all the preparation work, you have a development team in place and they can start the development process. So, you can sit back, breathe easily and wait until they deliver a fully functioning product on time and within budget. <br>
<br>
Well… Not exactly.<br>
<br>
Here is the thing: timelines and scope of development are never set in stone. Even with the most careful and detailed planning, contrary to many other disciplines (e.g. house construction) variability of complexity in software development is extremely high. Always. There are always roadblocks that will be uncovered only during the development cycle, and these roadblocks will require deviation from timelines and scope of development.  These deviations could result in 20x time from initial estimate if not handled properly. Same goes for the scope of development. And therefore costs of development. To avoid this, to keep the delay and scope changes within reasonable boundaries, you have to monitor the development progress constantly.

# After Product’s Development
## When Does Product Development End
Never.<br>
<br>
After the launch of every version comes bug fixes, development of new features for the next version, new challenges related to scaling, keeping up with the technology race, etc. This means you need your developers around all the time and you need to manage the process.

# Dangers Of Product Development
Product development is expensive and time sensitive. You do not want to throw away $100K-$200K of your or your investors’ money on the wrong thing, done incorrectly or ineffectively. You don’t want to spend resources and time (your most important resource, together with funds) on something you do not need. To avoid this, you need to bring on board somebody with relevant expertise and experience. (see our blog on the matter here). This person should plan your project carefully, include all of the above steps, hire developers, monitor product development, making sure it is done on time and on budget, making adjustments when necessary. They must be knowledgeable, experienced, and competent to assess the situation and recommend a course of action at any stage of development. In short you need somebody to act as your CTO. It may seem like a very high investment upfront, but it will definitely save you money and a lot of headache in the long run.
