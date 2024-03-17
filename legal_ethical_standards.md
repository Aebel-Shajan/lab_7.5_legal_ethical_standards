# Legal and Ethical Standards

## Learning objectives

- Appreciate the importance of legal and ethical standards relating to the application of digital technology in business
- Be able to explain how regulatory and compliance frameworks, international standards, codes of practice and protocols apply to digital technologies in business.

## Intro

For better or worse, everything in our day-to-day lives is governed by legal frameworks. We may follow some without question and others may frustrate us, but we still need to follow them. The software we interact with is goverened by these frameworks too, but beyond that there are ethical factors for developers to consider - morality and legality don't always go hand-in-hand. In this session we will investigate some of these considerations and consider them in teh context of some case studies.

## Background

We've all dealt with the annoying popups telling us about cookies whenever we enter a new website, even if it has become second nature to click accept/deny. Cookies are small files that save information about a user's time on a website. Sometimes they can be useful, for example saving you the need to log back in every time, but they can often have less benevolent purposes. They are one of the most effective tools for harvesting data from a user, often in ways that may not be immediately obvious.

The use of cookies is governed by the [General Data Protection Regulation](https://gdpr-info.eu/) (GDPR). It was passed into law by the European Union in May 2018 however it has broader reaching implications. Although countries like the UK and the USA are not part of the EU they must abide by GDPR in order to operate in Europe, meaning _every_ site accessible in the EU must display a prompt informing users about cookies used and allow them to opt-out of their use regardless of the site's country of origin.

GDPR goes way beyond just enforcing a popup though. As the name suggests it deals with anything involving a user's personal information, how it is stored and what can be done with it. We've all seen the boxes asking us to "tick here if you'd like to receive marketing emails" - that used to happen automatically before GDPR. It's not the only law affecting software either. Every locality has different interpretations of those laws - for example different age restrictions to access gambling content - and an application needs to satisfy all of them.

Those legal concerns often morph into ethical concerns once the regulatory boxes have been ticked. We may well tick the box saying we accept cookies and from a legal perspective the company can go on to do whatever they said they were going to do with our data. After all, we ticked the box didn't we? Many companies obfuscate the purpose of some cookies though, hiding the fact that the data they gather will be sold on to a third party behind a wall of legal text. It may be fine from a legal perspective, but what about morally?

Once we are over the hurdle of data-stealing cookies the ethical dilemmas continue. The content of a website may be the subject of an ethical debate itself (gambling sites are another example here) but design is a factor here too. Of course developers want to keep us interested in their content, but many sites are [designed specifically to be addictive](https://www.komododigital.co.uk/insights/how-social-media-apps-ux-ui-are-designed-to-engage-and-be-addictive/). Once they have us hooked the emphasis switches to making us want things by preying on our insecurities, amplifying our worries or simply by wearing us down with adverts.

Things are moving in the right direction though. [Hundreds of fines](https://www.enforcementtracker.com/) have been issued for GDPR violations and there are motions to [legislate against addictive design patterns](https://www.socialmediatoday.com/news/social-platforms-could-face-legal-action-for-addictive-algorithms-under-pro/626233/). Ultimately though it is societal changes and awareness of the issues inherent in modern technology which will drive change.


## Task

Each of the three scenarios below describes a fictional company's proposal for adding new features to their application. Read each scenario and consider the following questions:

- Is the company breaking any laws with their proposal?
- What are the ethical concerns with the company's proposal?
- What could the company do to address these issues?

Collate your answers in a markdown file, push it to GitHub and submit the link using the lab submission form as normal.

### Scenario 1

BankingCorp are one of the leading retail banks in the country, offering a full range of products including current accounts, savings products, credit cards and loans. They have in-depth knowledge of their customers' income, financial commitments and spending habits. They already offer some products where customers can pay a monthly fee and receive benefits in return. Some of these benefits include special offers from a curated list of third-party partners which customers can opt-in to receiving.

They have recently been approached by a payday loan company who want to send direct marketing to users struggling to pay their credit card bills. The loan company want to email the customers they feel would be most likely to use their services but acknowledge that manually identifying targets would be time-consuming and want to develop an algorithm to automate this. BankingCorp have given them access to their systems to test this algorithm, ensuring it works with real customer data. The loan company have had some negative publicity recently and so BankingCorp will not be announcing this new partnership publicly. Instead they will inform customers in an email explaining the changes to their terms and conditions.

### Scenario 2

The new mobile game Treasure Hunters has been taking the country by storm. Players are shown an illustrated map and must find the hidden treasure by following clues and solving puzzles. The quicker a player finds the treasure the more points they score and they can compare their scores with their friends. Five new maps are added every day and each map can be completed in a few minutes, with the low time commitment making the game a huge hit with casual players. There are many players who would like more puzzles, though.

The developers have been taken aback by the success of the game and are struggling to keep up with demand. They have had to spin up more servers and are looking to hire more engineers to keep working on content. That costs money though, and they are looking to monetise the game. Instead of adding new maps daily they will continually be adding more which players can unlock by completing existing maps. Players will be able to spend their points to unlock hints which will help them progress faster. Hints will also be available to purchase using real-world money, with the possibility of offering multi-buy discounts at a later date.

### Scenario 3

`friends.com` is a new match-making service to help people socialise when they move to a new area. Users enter their area and a list of their interests before being shown a list of people with similar interests in the area. There's no guarantee of an exact match in interests and the suggested friend could be on the opposite side of the city. Users can freely view each others' profiles and message each other, but the matching service will speed up the process of making new contacts. The site is free with revenue coming from generic banner ads on the page.

Their development plans involve adding a premium membership which will lock many of the existing features behind a paywall. Free users will only be able to view limited versions of profiles and have a daily cap on the number of matches which can be made. Premium users, on the other hand, will now have more specific location settings and be able to filter their matches. To advertise the premium service the free-tier users will be given occasional "trial periods" of the premium tier followed by adverts showing them what they could unlock by subscribing. Additionally the generic banner ads will be replaced by more targeted advertising for local businesses. Users' location data will be shared in order to ensure relevant businesses are being advertised.


## Additional Resources

- [Ten legal issues in software development](https://www.lawdonut.co.uk/business/blog/24/01/ten-legal-issues-software-development#:~:text=Which%20are%20the%20legal%20issues,%2Dinfringement%20of%20others'%20rights.)
- [Examples of ethical issues in software development](https://www.techtarget.com/searchsoftwarequality/tip/5-examples-of-ethical-issues-in-software-development)
- [The case of the killer robot](https://onlineethics.org/cases/case-killer-robot)