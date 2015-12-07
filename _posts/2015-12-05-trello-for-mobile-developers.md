---
title: "Trello for Mobile developers"
date: 2015-12-05 21:41:06
description: "An alternative solution that relies on using Trello vertically with special lists convention"
---
Trello, as everybody know, is a great project management tool, it's really easy and extremely flexible to fit many needs from the digital work to the real life.

Today, I want to expand that flexibility in the way to make it more gratefully for mobile developers Android and iOS.
The normal use case consists on using 3 default lists: `to-do`, `doing`, `done` which are correct and let us manage our tasks gratefully. 

<img src="https://d2k1ftgv7pobq7.cloudfront.net/meta/u/res/images/d1e04e4b8e9f93a9671be5dc719b4f79/guide-board.png" alt="Trello" width="100%"/>

However on the mobile development field, doing this same manipulation will make us lose tracking of changes from a version to another. I mean what you're working on in this version, what was already shipped and what it's planned for later.
 
 For theses needs, I've opted for an **alternative solution** that relies on using Trello vertically, I resume it in 3 processes:  

- Creating new lists as many as our app versions  
- Renaming these lists according to a specific convention 
- Applying labels for each card according to the work status or type (working on, done, UI, bug ...)  


Let's see it in pictures:

<img src="/assets/images/trello_for_mobiledev.png" alt="Trello for mobile developers" />

As you saw, each list is versioned, named according to app version, respecting the following convention: `version name` - `version code` - `Shared + date of sharing`  
eg: `Beta - v0.4 (Shared on 01/01/2016)`  
The last `Shared on` item expresses if app was shared with client or even deployed on the store with the specified date of this action.
That's a basic convention that I'd recommend, but of course, you could tweak it as you like to match your needs.

Let's see labels:  
<img src="/assets/images/trello_labels_for_mobiledev.png" alt="Trello Labels" width="200"/>  
These ones are basic, add new labels as many as you need `UI`, `UX` or even `Bug` ...


### Bonus  

One more great thing, that's this new way of managing my Trello saved me time to mark which changes are made in each version, So no more worries about Change logs on Google Play or AppStore. Here is a sample taken from *Clean Master* app.

<img src="/assets/images/cleanmaster_changelog.png" alt="Clean Master" width="300"/>  

Hope this technique could improve your development workflow.
Let me know what's your favorite way of managing such projects
