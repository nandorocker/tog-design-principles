# First Principles of Interaction Design (Revised & Expanded)

The following principles are fundamental to the design and implementation of effective interfaces, whether for traditional GUI environments, the web, mobile devices, wearables, or Internet-connected smart devices.

## Help!

This is a huge revision. I expect I have made mistakes. Please leave corrections and suggestions in the Comments at the end. If you have better examples than I’m using, please include them as well, but give me enough information about them, including links or cites, that I can make use of them.

This revision features new examples and discussion involving mobile, wearables, and Internet-connected smart devices. However, the naming and organization remains the same except for three changes: I have shortened the name of one principle to extend its reach: “Color Blindness” is now simply [Color](#color) and includes more than just color blindness. I’ve added one new principle, [Aesthetics](#aesthetics), and brought back two old principles, [Discoverability](#discoverability) and [Simplicity](#simplicity). I dropped them from the list more than a decade ago when they had ceased to be a problem. Problems with Discoverability, in particular, have come roaring back.

What has changed greatly is the level of detail: You will find many new sub-principles within each category, along with far more explanation, case studies, and examples.

---

**Previous Version & Its Translations.** (Google’s machine translator for the latest edition, to your right). I’m continuing access to the original version of First Principles because it is cited in many scientific papers.

*   [Belarusian](http://www.fatcow.com/edu/designedtogivefitts-be/)
*   [Dutch](http://aifia.org/nl/translations/000187.html)
*   [English](http://asktog.com/basics/firstPrinciplesOldEdition.html)
*   [German](http://meiert.com/de/publications/translations/asktog.com/firstprinciples/)
*   [Italian](http://www.10people.net/tutorial/interaction_design-ask_tog/pricipi_di_interaction_design.html)
*   [Portuguese](http://userdesign.org/principios.html)
*   [Spanish](http://galinus.com/es/articulos/principios-diseno-de-interaccion.html)
*   [Russian](http://ashapiro.ru/translations/tog-first-principles/)
*   [Ukrainian](http://www.portablecomponentsforall.com/edu/designedtogivefitts-uk/)

---

## Introduction

Effective interfaces are visually apparent and forgiving, instilling in their users a sense of control. Users quickly see the breadth of their options, grasp how to achieve their goals, and can settle down to do their work. Effective interfaces do not concern the user with the inner workings of the system. Work is carefully and continuously saved, with full option for the user to undo any activity at any time. Effective applications and services perform a maximum of work, while requiring a minimum of information from users.

Because an application or service appears on the web or mobile device, the principles do not change. If anything, applying these principles—all these principles—becomes even more important.



### I Love Apple, But It’s Not Perfect

I’ve used many example drawn from Apple products here, often as examples of bad interface practices. Apple has made many revolutionary breakthroughs in interaction technology, a trend I fully expect will continue. They also make mistakes, fewer than most, but because I use Apple products almost exclusively, I suffer from them daily. While composing this document on my various Apple devices, it’s only natural that I extract examples from what I see here and now.

Please do not take from this document that I am somehow an Apple hater. In 1978, I designed Apple’s first human interface after being recruited by Steve Jobs. I spent more than 14 years with the company. I buy most every new major product Apple releases on Day One and have much of my retirement invested in Apple stock. I love Apple, support Apple, but would like it to do even better.



---

## Aesthetics

*   **Principle: Aesthetic design should be left to those schooled and skilled in its application: Graphic/visual designers**

*   **Principle: Fashion should never trump usability**

Generating artificial obsolescence through fashion is a time-honored and effective way to sell everything from clothing to cars. A new fashion should not and need not detract from user-performance: Enormous visual and even behavioral changes can be carried out that either do not hurt productivity or markedly increase it.

*   **Principle: User test the visual design as thoroughly as the behavioral design**

User test after aesthetic changes have been made, benchmarking, where applicable, the new design against the old. Ensure that learnability, satisfaction, and productivity have been improved or at least have stayed the same. If not, newly-added aesthetics that are causing a problem need to be rethought.



---

## Anticipation

*   **Principle: Bring to the user all the information and tools needed for each step of the process**

Software and hardware systems should attempt to anticipate the user’s wants and needs. Do not expect users to leave the current screen to search for and collect necessary information. Information must be in place and necessary tools present and visible.

Anticipation requires that designers have a deep understanding of both the task domain and the users in order to predict what will be needed. It also requires sufficient usability testing to ensure the goal has been met: If a tool or source for information is there on the screen, but users can’t find it, it may as well not even be present.

The penalty for failing to anticipate is often swift and permanent, particularly if you do not have a captive user, as is the case with public websites and apps, for example. Those users will probably never return from their search. Even if you do have a captive user, you probably don’t have a captive client, and if the client’s employees are wasting time trying to find required resources, your competitors will have a good story to tell when it is time to make their next pitch.

---

## Autonomy

*   **Principle: The computer, interface, and task environment all “belong” to the user, but user-autonomy doesn’t mean we abandon rules**

Give users some breathing room. Users learn quickly and gain a fast sense of mastery when they are placed “in charge.” Paradoxically, however, people do not feel free in the absence of all boundaries (Yallum, 1980). A little child will cry equally when confined in too small a space or left to wander in a large and empty warehouse. Adults, too, feel most comfortable in an environment that is neither confining nor infinite, an environment explorable, but not hazardous.

*   **Principle: Enable users to make their own decisions, even ones aesthetically poor or behaviorally less efficient**

Autonomy means users get to decide what keyboard they want to use, how they want their desktops to look (even if they like clutter), and what kind of apps they want to run. When developers take that kind of control away, users can be left frustrated and angry.

*   **Principle: Exercise responsible control**

Allowing users latitude does not mean developers should abandon all control. On the contrary, developers must exercise necessary control. Users should not be given so much rope they hang themselves. However, some developers today are not only taking excessive control, but making huge HCI errors in the process, like restricting text to fonts and sizes that people with ordinary eyesight can’t read. They offer editing schemes that require the user to use their fat finger to place the text cursor with pixel-precision accuracy just to avoid adding the necessary arrow keys to their aesthetically perfect, but functionally crippled, keyboard.

They also set an arbitrary timing and movement threshold for determining whether a user is or is not pressing a link on purpose, rather than her just pausing for an instant at the start of an upward swipe for scroll, for example. They then offer the user no way to alter that threshold, so many users find themselves triggering links to unwanted pages many, many times per day. That is an irresponsible application of control. We learned 30 years ago that users needed access to a slider for mouse double-clicking. Touch users need the same thing for link timing.

### Perfect Link Triggering, Every Time

In thinking about solutions to problems like accidental link triggering, you have to consider the difference between a user who is accidentally triggering a link and a user who intends to trigger it.

The difference is easy when you think about it: I look at a link when I’m trying to trigger it. I’m not looking at the ones that I trigger by accident. Turn on the camera or use a built-in dedicated eye-tracker to look at the user’s eyes. If he looks right at the link for long enough for it to register in his mind that he’s touching it, he’s trying to follow the link. If he’s not looking at it, he’s accidentally touching it. When you have determined purposeful touching, trigger the link. If you determine the user is not purposely touching, ignore the fact that the user is touching it.

To save energy, to carry out this method, the camera or eye tracker need not be turned on until the user is hovering over or pressing a link. The method and algorithm may require minor tweaks in timing, but it should prove quite accurate.

This may have already been invented, but, if not, it’s called, “Accidental Link Triggering Error-Reduction Method Using Eye Tracking,” and I hereby put it in the public domain.

*   **Principle: Use status mechanisms to keep users aware and informed**

No autonomy can exist in the absence of control, and control cannot be exerted in the absence of sufficient information. Status mechanisms are vital to supplying the information necessary for users to respond appropriately to changing conditions.

*   **Principle: Keep status information up to date and within easy view**

Users should not have to seek out status information. Rather, they should be able to glance at their work environment and be able to gather at least a first approximation of state and workload.

*   **Principle: Ensure status information is accurate**

Status information can be up to date, yet inaccurate. At the time of this writing, when a user updated an iPhone or iPad to a new generation of system software, a progress indicator would appear showing that it will take approximately five minutes to complete the task. Actually, it typically takes an hour or more. (The new system itself would update in five minutes, but then all the other tens or hundreds of megabytes of information on the phone had to be re-uploaded.) The user, having been lied to, was left with no way to predict when she might actually get her device back. Such a user is not feeling autonomous.



---

## Color

### Color blindness

*   **Principle: Any time you use color to convey information in the interface, you should also use clear, secondary cues to convey the information to those who cannot see the colors presented.**

Most people have color displays nowadays. However, approximately 10% of human males, along with fewer than 1% of females, have some form of color blindness.

*   **Principle: Test your site to see what color-blind individuals see**

*Search Google for simulation tools. For example, for websites, you might try [http://enably.com/chrometric/](http://enably.com/chrometric/). For images, [http://www.colblindor.com/coblis-color-blindness-simulator/](http://www.colblindor.com/coblis-color-blindness-simulator/).*

### Color as a vital interface element

*   **Principle: Do not avoid color in the interface just because not every user can see every color.**

Color is a vital dimension of our limited communication abilities. Stripping away colors that a person who is color blind can’t see does no more for that person than turning off the entire picture does for a person who is completely without sight. It’s the presence of an alternate set of cues for that person that is important.

*   **Principle: Do not strip away or overwhelm color cues in the interface because of a passing graphic-design fad.**

Generating artificial obsolescence through fashion is a time-honored and effective way to move products from clothing to cars. A new fashion should not and need not, however, detract from user-performance. User test after making aesthetic changes, benchmarking the new design against the old. Ensure that learnability, satisfaction, and productivity have improved or at least stayed the same. If not, newly added aesthetics that are causing a problem need to be rethought.



---

## Consistency

The following four consistency principles, taken together, offer the interaction designer tremendous latitude in the evolution of a product without seriously disrupting those areas of consistency most important to the user.

### 1) Levels of Consistency

*   **Principle: The importance of maintaining strict consistency varies by level.**

The following list is ordered from those interface elements demanding the _least_ faithful consistency effort to those demanding the _most_. (Many people assume that the order of items one through six should be exactly the reverse. This can lead to real confusion as users confront pages that look familiar, but act completely different.)

**1\. Top level consistency**

• **Platform consistency:** Be generally consistent with _de jure_\* & _de facto\*\*_ standards

*\* as dictated by guidelines and standards*
*\*\* the unwritten rules to which the community adheres*

• **In-house consistency:** Maintain a general look & feel across your products/services

Communicates brand and makes adoption of your other products and services easier and faster

**2\. Consistency across a suite of products, e. g., Microsoft Office**

General look & feel communicates family

**3\. The overall look & feel of a single app, application or service–splash screens, design elements, etc.**

A visual designer should establish a purposeful & well thought-through visual language, shaped by usability testing. User behaviors should be fully transferable throughout the product.

**4\. Small visible structures, such as icons, symbols, buttons, scroll bars, etc.**

The appearance of such objects needs to be strictly controlled if people are not to spend half their time trying to figure out how to scroll or print. Their location is only just slightly less important than their appearance. Where it makes sense to standardize their location, do so.

**5\. Invisible structures**

Invisible structures refers to such invisible objects as Microsoft Word’s clever little left border that has all kinds of magical properties, if you ever discover it is there. It may or may not appear in your version of Word. And if it doesn’t, you’ll never know for sure that it isn’t really there, on account of it’s invisible. That is exactly what is wrong with invisible objects and why, if you insist on using them, rigid consistency becomes so important.

Apple apparently thought this was a good idea and started copying Microsoft by adding invisible controls from scroll bars to buttons everywhere. The situation on the Mac got so bad that, by the early 2010s, the only way a user could discover how to use many of the most fundamental features of the computer was to use Google to search for help. *(For more, see: [Discoverability](#discoverability))*

Some objects while, strictly speaking, visible, do not appear to be controls, so users, left to their own devices, might never discover their ability to be manipulated. If you absolutely insist on disguising a control, the secret rule should be crisp and clean, for example, “you can click and drag the edges of current Macintosh windows to resize them,” not, “You can click and drag various things sometimes, but not other things other times, so just try a lot of stuff and see what happens.”

Objects that convey information, rather than being used to generate information, should rarely, if ever, be made invisible. Apple has violated this in making the scroll bars on the Macintosh invisible until a user passes over them.

**6\. Interpretation of user behavior**

Changing your interpretation of a user’s habitual action is one of the the worst things you can do to a user. Shortcut keys must maintain their meanings. A learned gesture must be interpreted in the standard way. If the button that carries the user to the next page or screen has been located at the bottom right for the last 30 years, don’t move it to the top right. Changes that require a user to unlearn a subconscious action and learn a new one are extremely frustrating to users. Users may not even realize what has happened and assume that something has failed in their hardware or software.

If you want to attract existing users of someone else’s product to your product, you should try to interpret your new user’s commands in the same way by, for example, allowing them to reuse the same shortcut keys they’ve grown used to.

**Case Study: Apple “Command” Modifier Key**

It was years before Apple finally gave Windows users a simple way to continue to use the Control key, rather than the Command key, for their keyboard shortcuts. Windows users new to Mac faced great difficulty in unlearning/relearning such an ingrained habit. Users having to switch between the two operating system as they moved between office and home had to unlearn/relearn twice a day and would end up constantly making errors as well as having to set aside their task to consciously consider what modifier key to press each and every time they wanted to make use of “shortcut” keys that were shortcuts no more. A large percentage of the difficulty in switching or using dual operating systems was due to this one missing capability, and it was a completely unnecessary hindrance from the start.



### 2) Induced Inconsistency

---

* **Principle: It is just important to be visually inconsistent when things act differently as it is to be visually consistent when things act the same**

Make objects that act differently look different. For example, a trash can is an object into which a user may place trash and later pull it back out. If you want to skip the “and pull it back out” functionality, that’s fine. Just make it look like an incinerator or shredder or anything other than a trash can.

Make pages that have changed look changed. If someone encounters an unfamiliar page on an updated website or in a revised app, they know to look around and figure out what’s different. In the absence of such a cue, they will attempt to use the page exactly as they have always done, and it won’t work.

### 3) Continuity

*   **Principle: Over time, strive for continuity, not consistency**

If you come out with a completely re-worked area of your product or even a completely new product, it is important that people instantly recognize that something big has changed. Otherwise, they will jump into trying to use it exactly the way they always have and it just isn’t going to work. “Uniformity” would mean that your next product would be identical to your last, clearly wrong, but “consistency” is little better in a field where so much growth will continue to take place. Our goal is continuity, where there is a thread that weaves through our various products and releases, guiding our users, but not tying us to the past.

### 4) Consistency with User Expectation

*   **Principle: “The most important consistency is consistency with user expectations”—William Buxton**

It doesn’t matter how fine a logical argument you can put together for how something should work. If users expect it to work a different way, you will be facing an uphill and often unwinnable battle to change those expectations. If your way offers no clear advantage, go with what your users expect.

**Case Study: The Xerox Star Drag Rule,**

The rule proposed for dragging icons in the Xerox Star Finder was a paragon of elegance:

*   **Proposed Rule: Dragging a document icon from one object (e. g., a folder or disk) to another on the desktop will move the document**

Easy to learn. Easy to understand. Logical. Teachable. Terrible. The rule, to be fair, worked well most of the time. It even worked better in some circumstances than the far more complex rule we use today. For example, if you dragged a document from the folder on your desktop to a floppy disk, it moved the document, rather than making a copy on the floppy. If you then made changes to the document at home, using the document now on the floppy, when you slid the document back onto your desktop at work the next morning, you didn’t have the new version as well as an obsolete version left there the day before. You just had the one true version.

Everything worked well until it was time to print on the Xerox Star. At that a point, you would grab the document and drag it onto the printer icon. The document was transferred to the printer _and erased forever from the desktop._ A two-week war erupted between the engineers and the designers. The designers won, putting in place the rule we have today:

*   **Final Rule: Dragging a document within a logical volume will move it. Dragging it from one logical volume to another will copy it**

99+% of our users could not possibly tell you what a “logical volume” is, yet they understand the rule without our having to explicitly teach them. Why? Because it is _consistent with user expectations,_ part of which is a very strong expectation that carrying out a routine activity will not result in the destruction of their work.



---

## Defaults

*   **Principle: Defaults within fields should be easy to “blow away”**

When a user activates a field, the current entry should be auto-selected so that pressing Backspace/Delete or starting to type will eliminate the current entry. Users can click within the field to deselect the whole, dropping the text pointer exactly where the user has clicked. The select-on-entry rule is generally followed today. (Sloppy coding, however, has resulted in the text cursor dropping at various unpredictable locations. )

*   **Principle: Defaults should be “intelligent” and responsive**

Not everything should have a default. If there isn’t a predictable winner, consider not offering any default. It takes precious cognitive cycles to look at a default that covers maybe 25% of the cases and make the decision not use it. That same time could be spent entering the choice actually desired.

*   **Principle: Replace the word “default” with a more meaningful and responsive term  **

Users rarely have any idea of what “Default,” in a given situation means. (They do know its literal meaning, of course, which is that the bank is going to take away the user’s house. That always cheers them up.) Replace “Default” with “Revert to Standard Settings,” “Use Customary Settings,” “Restore Initial Settings,” or some other more specific terminology describing what will actually happen. User test to find out what terms enable your users to accurately predict what your software will actually do.

*   **Principle: Both your vocabulary and visual design must communicate the scope of a reversion**

Make sure, through user testing, that users understand the extent of the restoration: Are they signing up to a benign restoration of just a few recent and localized items, or are they about to spend the next four days re-entering usernames and passwords in every app they own?

User-test your restoration options to find out what users think the result of pressing the button will be. If you are going to do something benign, but they interpret it as potentially destructive, they won’t use the option, leaving them with the same broken or partially broken system that made them consider using it in the first place. Likewise, if you wipe out hours of careful customization without properly preparing them, they may not be nearly as grateful as you might expect. (I once had a young chap in India help me out with a minor problem on my DVR. When he was finished, he had led me to reinitialize the hard disk, erasing every single program on the machine. That was a bit more restoration than I was looking for. After that, I was able to carry out the rest of my conversation with him without even using the phone. I had no idea I could yell that loud.)

When designing tabbed objects, such as properties and preference windows, ensure that the visual design makes the scope of a restoration button clear. Individual tabbed “cards” should be visually separated from the surrounding window so that buttons may be placed either within the individual card or in the surrounding area, indicating whether the button action will apply only to the current tab or all tabs. There is never an excuse for leaving such a scope ambiguous. This is not a fashion decision.



---

## Discoverability

*   **Principle: Any attempt to hide complexity will serve to increase it**

Functional software does not have to look like a tractor; it can look like a Porsche. It cannot, however, look like a Porsche that’s missing its steering wheel, brake, and accelerator pedal. Yet many tech companies in the late 1990s began purposely hiding their most basic controls, often to the serious detriment of their users. Why? Because they found it more important to generate the [Illusion of Simplicity](#illusion-of-simplicity) for potential buyers than to reveal the extent of complexity to their actual users.

Businesses are driven to hide complexity from buyers because it can pay off in the short term: Most consumers who are potential buyers make judgements as to whether they can conquer a new machine not by sitting down and spending a day trying to learn it, but by gazing at the screen for ten minutes while the salesperson gives a demo. Stripping away scroll bars, hiding buttons, doing all the things that this section tells you not to do can all lead to increased profits, at least in the short term.

**Case Study: The Invisible Mac Scroll Bars**

Scroll bars are used to generate information, as a user clicks or drags within them to inform the software that the user wishes to move to a different position within the page or document. However, just as often, users will glance at the scroll bar just to see where they are in a page.Users try to maintain a sense of place on two different levels: First, their location right now within the visible part of the page; second, their location within the entire document. By forcing the user to move the mouse away from their current center of interest in order to scrub the scroll bar to make it appear, they lose a primary cue as to their current position within the visible page, namely, the current location of the mouse pointer.

Making a complex control like the scroll bar invisible likewise slows the user attempting to actually scroll: With the scroll invisible, the user can’t predict where in the blank space hiding the control she should scrub in order to find herself over the “elevator” she will use to do the scrolling. Instead, she first has to scrub somewhere in the scroll bar (target one) and then slide up or down to the elevator (target 2). (See [Fitts’s Law](#fittsLaw) for why this is bad.) Let’s assume that extra step would only require one extra second, a very conservative estimate. One second lost X ten scrolls per day per person X 66 million Mac users (at the time of this writing) = 21 person-years of wasted life and productivity per day, all to make a screen in a store look simpler.



*   **Principle: If you choose to hide complexity, do so in the showroom only**

You need never decide whether to support potential buyers or eventual users. We are not working with fixed pieces of hardware. We work with either pure software or hardware driven by software. A designer can easily create a system that will fully support both buyer and user, switching appearance depending on current need. You can design the software for an operating system, for example, that will present itself in a very simple form in the store only to slowly open up like a flower, offering the user more and more accessibility and functionality as the user becomes progressively more skilled and more comfortable.

Crippling an interface might help make the initial sale, but in the long run, it can lead to having your most important “sales force,” your existing customer base, not only leave you, but tell your potential buyers to stay away as well.



*   **Principle: If the user cannot find it, it does not exist**

Not all buyers are naive. Even those that are don’t stay that way long. Only the most persistent buyers/users will travel the web searching for a treasure map to features that you choose to hide from them. Most will simply turn to your competitors, taking you at your word that you just don’t offer whatever they were after.

**Case Study: Safari for the Mac**

I abandoned the Safari browser for Firefox after I found that Safari for the Mac had started corrupting PDF files when doing a Save As. Two years later, I tried Safari again, assuming Apple had by now fixed the bug. The bug persisted, but I persisted this time, too, spending 20 minutes Googling for a work-around. The solution I discovered? Never use Save As to save a PDF file. Instead, mouse away from the top of the display, where 100% of the file-manipulation controls are, toward the bottom of the window, where nothing but content exists. Suddenly, a gray box with a floppy-disk icon will start fading into view _inside the content region_. Click the icon, and Safari will save your PDF.

*   **Use Active Discovery to guide people to more advanced features**

With Active Discovery, you cease waiting for people to find something and, instead, offer it to them. In its ideal form, your system “realizes” they now need it and offers it to them. In most instances, we are far from being able to do that. A workable compromise:

1.  Mention to a user that a feature exists about the earliest he might need it
2.  Repeat the message at intelligently spaced intervals. Not over and over again.
3.  Stop mentioning it once either explored or adopted

The messaging might take the form of a “Did you know…” hint that you show during startup. (If you see a large percentage of your users are turning off these hints, it reflects that you are prematurely mentioning features, are giving them too many hints too often, or continue to tell them about features they have adopted. It is not necessary to give a helpful hint each and every time the user starts up your app. They are more likely to be read and appreciated if they occur on occasion.

**Case Study: GroceryIQ app for the iPhone**

GroceryIQ enabled the user to scan the bar codes of rapidly-emptying containers in the user’s kitchen or to type in a few leading words to any product they might find in a grocery store. Armed with the resulting list, they could walk through their neighborhood market, marking off items as they came across them. It was quick, efficient, and, in general, designed competently. The developers had made no effort to hide complexity. However, the user could make good use of the app within a couple minutes, discovering further complexity when and if their wants and needs expanded.GroceryIQ had no real competition in this rather narrow sector for several years. When a new app was released that also enabled the user to sync between devices, so that, for example, a wife could enter an item, such as a quart of milk, and it would show up in the husband’s shopping list a few seconds later, many people jumped ship, moving to the new product.So why is this a case study of interest? Because GroceryIQ had had syncing between products for more than five years before the competing product was released. It was easy to set up and very reliable. It was not purposely hidden and its name, Sync, certainly was not open to misinterpretation. The problem was that it was on the More… submenu, rather than being constantly displayed at the bottom of the phone. An Active Discovery reminder, triggered on opening perhaps a few days after the app was installed, along with a follow-up even every three months thereafter until such time as Sync was set up would have prevented a loss of customers five years later when the new app, “featuring Sync!” showed up.



*   **Principle: Controls and other objects necessary for the successful use of software should be visibly accessible at all times**

The object itself should either be view or enclosed by an object or series of objects (documents within folders, menu items within a menu, for example) that, in turn, are visibly accessible at all times.

Exceptions can be made for systems that are used habitually, such as a mobile browser or reader, where:

1.  Screen size is so limited that it is impractical to display items not currently needed, and
2.  It would be difficult or impossible for the user to fail to trigger the appearance of the controls by accident, thus ensuring the user will discover their existence.

These exceptions cover standard and widely-used operating system objects and behaviors on mobile devices, as long as users are given simple and obvious access to a help guide for using them.

*   **Principle: There is no “elegance” exception to discoverability**

A few designers, having fallen in love with the clean lines of smartphone apps, thought it would be great to visit those same clean lines on giant-screen computers. Wrong! Hiding functionality to create the [Illusion of Simplicity](#illusion-of-simplicity) is an approach that saps user-efficiency and makes products an easy target for competitors.

*   **Principle: With the exception of small mobile devices, controls do not belong in the middle of the content area**

**Smartphone and tablet controls** are sometimes forced into the content area because the screens are so small, that’s the only area there is. Even there, you need to provide a standard trigger, such as a tap in the middle of the content area, that will simultaneously expose all the icons and buttons representing all the hidden controls so that users don’t have to carry out a treasure hunt.



### Web Pages & Cloud-based Applications

The first “inside-out” applications appeared inside web browsers as independent developers struggled to create complex sites and apps within the confines of a simple window in a simple tool designed for simple browsing of static pages. Even though the basic paradigm was shown inadequate by 1996, nothing at all has been done by standards committees to address the needs of these developers.

Developers working on complex sites and cloud-based web applications deserve access to the browser’s menu bar. That they don’t already have it is a continuing scandal. Imagine your boss telling you to whip up a competitor to Photoshop that uses Microsoft Word’s menu bar. The first words out of your mouth would be, “but that would mean I’d have to put all my menus in the content area of the window where the user’s image needs to be!” Insane, right? Yet that’s just what we do every time we create a web page.

**On laptop and desktop computers**, controls, and, in particular, hidden controls have no place inside the content area.

**Case Study: Apple’s Inverted Applications**

Apple, as of the early 2010s, began migrating controls from the area surrounding the content region of their Macintosh applications into the content region itself. The controls popped up in locations that would obscure the very content the user was attempting to affect. The user was often unable to move the controls far enough out of the way to be able to see what they were doing. Even when a control panel could be moved beyond the edges of the content window, it would revert to its original obscuring position the next time it was invoked. While this approach was sometimes a necessity for apps designed for phones, it made no practical sense for apps designed for the large screens found on traditional computers. Some of the affected apps would take up as little as 10% or 20% of the user’s screen, providing huge amounts of room for the controls suddenly being forced into the even smaller content region. It resulted in serious degradation of the user’s satisfaction and productivity.



*   **Principle: Communicate your gestural vocabulary with visual diagrams**

Include a help page that shows the gestures your app can understand. Present the page when the user first opens the app and make it clear where the user will find this help page after that. In a mobile app, make the icon representing the page constantly visible or have it form part of the standard set that appears around the periphery when the user touches the triggering area of the mobile screen. For a magazines and similar media objects, make it the first open page (after the cover) of each and every issue, always there and available.

[![Instructions for Popular Photography for iPad, an interface worth exploring](http://asktog.com/atc/wp-content/uploads/PopPhotogInstr2013Cropped.jpg)](http://asktog.com/atc/first-principles-of-interaction-design/popphotoginstr2013/)

*Instructions for Popular Photography for iPad, an interface worth exploring*




*   **Principle: Strive for Balance**

It is not 1980, when most people had never seen a computer, and we necessarily made everything highly visible. You can use subtly in design: Don’t put an info icon next to every single item on the page. Instead, use overlays like this one from Google+ Snapseed that explain every symbol and every gesture at once:

[![Google+ Snapseed help overlay showing meaning of symbols as well as gestures](http://asktog.com/atc/wp-content/uploads/SnapseedHelpOverlay.jpg)](http://asktog.com/atc/wp-content/uploads/SnapseedHelpOverlay.jpg)

*Google+ Snapseed help overlay showing meaning of symbols as well as gestures*



It is difficult to see with the overlay in place, but the developers have reinforced their Cancel and Apply arrows with permanent, written labels. How do you find out if such reinforcement is necessary? How do you find out whether the user can figure out what to press (in this case, an always-visible question mark at the extreme top right) to get help to begin with? Follow the next principle and apply the results.



*   **Principle: User-test for discoverability**

To discover what information you need to communicate and to ensure you’re successfully communicating it, you must do routine usability tests throughout a project. Test using a population that has your expected level of experience with the system and task domain. See if they can locate, identify, learn, and use the tools they need to perform the tasks you expect your users to perform. If they cannot, iterate the design until they can. Make use of Active Discovery, Dealer Modes, whatever you need to to ensure your users can discover and learn the features of your product.

Not one of the errors I’ve discussed above would ever make it into production were user-experience groups conducting usability studies and altering the design based on those results.



---

## Efficiency of the User

*   **Principle: Look at the user’s productivity, not the computer’s**

In judging the efficiency of a system, look beyond just the efficiency of the machine. People cost a lot more money than machines, and while it might appear that increasing machine productivity must result in increasing human productivity, the opposite is often true. As a single example, forcing customers to enter telephone numbers without normal spacing or punctuation saves a single line of code and a handful of machine cycles. It also results in a lot of incorrectly captured phone numbers as people cannot scan clusters of ten or more digits to discover errors. (That’s exactly why phone numbers are broken up into smaller pieces.) The amount of time wasted by just one person in your company trying to track down the correct version of an incorrectly entered phone number would sweep away the few minutes it would have taken to code the entry form so users could scan and correct their errors. Wrong numbers also can and do result in a lost sales. How many trillions of machine cycles would the profit from a single lost sale have covered?

*   **Principle: Keep the user occupied**

Typically, the highest expense by far in a business is labor cost. Any time an employee must wait for the system to respond before they can proceed, money is being lost.

*   **Principle: To maximize the efficiency of a business or other organization you must maximize everyone’s efficiency, not just the efficiency of the IT department or a similar group**

Large organizations tend to be compartmentalized, with each group looking out for its own interests, sometimes to the detriment of the organization as a whole. Information technology departments often fall into the trap of creating or adopting systems that result in increased efficiency and lowered costs for the information resources department, but at the cost of lowered productivity for the company as a whole. It is your job to run the studies that prove out whether new designs based on new, money-saving technologies will increase or decrease overall productivity among the affected workers and, if so, by how much and with what result to the corporation’s bottom line.

Work with HR or department heads to find out the average cost per hour of affected employees. (An honored rule of thumb is to take their hourly wage and multiply it by three to include all the other overhead associated with an employee, from rent to heat, lights, computer support, etc.) Multiply the overhead cost x the number of affected employees x the time an activity takes x the difference in productivity, positive or negative, in carrying out the activity to find the actual cost of a change. A positive number will help you sell your group and your design. A negative number will help your company from making a costly mistake.

*   **Principle: The great efficiency breakthroughs in software are to be found in the fundamental architecture of the system, not in the surface design of the interface**

This simple truth is why it is so important for everyone involved in a software project to appreciate the importance of making user productivity goal number one and to understand the vital difference between building an efficient system and empowering an efficient user. This truth is also key to the need for close and constant cooperation, communication, and conspiracy between engineers and human interface designers if this goal is to be achieved.

Look at the difference between the iPad and the netbook computers it crushed. The differences had nothing to do with what key you pressed to open an email. They had to do with things like not having to press any key at all.

*   **Principle: Error messages should actually help**

Error messages must be written by a skilled writer to:

1.  Explain what’s wrong
2.  Tell the user specifically what to do about it
3.  Leave open the possibility the message is improperly being generated by a deeper system malfunction

“Error -1264” doesn’t do any of these. Rare is the error message that covers even Point One well. Yours should cover all three. Your Quality Assurance group should be charged with the responsibility for reporting back to you any message that does not fulfill the criteria.

Many other principles in this list affect efficiency, [Latency Reduction](#latencyReduction) and [Readability](#readability) in particular.



---

## Explorable Interfaces

*   **Principle: Give users well-marked roads and landmarks, then let them shift into four-wheel drive**

Mimic the safety, consistency, visibility, and predictability of the natural landscape we’ve evolved to navigate successfully. Don’t trap users into a single path through a service, but do offer them a line of least resistance. This lets the new user and the user who just wants to get the job done in the quickest way possible a “no-brainer” way through, while still enabling those who want to explore and play what-if a means to wander farther afield.

*   **Principle: Sometimes you do have to provide deep ruts**

The earlier your users are on the experience curve, the more you need to guide them. A single-use application for accomplishing an unknown task requires a far more directive interface than a habitual-use interface for experts. The deepest ruts are wizards.

*   **Principle: Offer users stable perceptual cues for a sense of “home”**

Stable visual elements not only enable people to navigate fast, they act as dependable landmarks, giving people a sense of “home.” A company logo on every page of a website, including every page of checkout, all enabling the user to escape back to the home page, makes users feel safe and secure. Paradoxically, such cues make it more likely that people will not escape back to the home page, secure in the knowledge that they easily can.

*   **Principle: Make Actions reversible**

People explore in ways beyond navigation. Sometimes they want to find out what would happen if they carried out some potentially dangerous action. Sometimes they don’t intend to find out, but they do anyway by accident. By making actions reversible, users can both explore and can “get sloppy” with their work. A perfect user is a slow user.

*   **Principle: Always allow “Undo”**

The unavoidable result of not supporting undo is that you must then support a bunch of confirmation dialogs that say the equivalent of, “Are you really, really sure?” Needless to say, this slows people down.

If you fail to provide such dialogs, in the absence of undo, people slow down even further. A study a few years back showed that people in a hazardous environment make no more mistakes than people in a supportive and more visually obvious environment, but they work a lot slower, taking great care to avoid making errors. The result was a huge hit in productivity.

We usually think of the absence of Undo as being the sign of lazy programming, but sometimes people do it on purpose. For example, some ecommerce sites want to make it hard for you to take things back out of your shopping cart once you’ve put them in there. This turns out to be a backwards strategy: An ecommerce study we did at the Nielsen Norman Group looked at what happens when merchants make it really easy to take things out of shopping carts. As might be expected, people visiting these merchants were much more willing to throw things in, figuring, “oh, well, I can always take it back out later.” Except they didn’t take them back out, because the deletion rate was no different. These user just bought more stuff.

*   **Principle: Always allow a way out**

Users should never feel trapped inside a maze. They should have a clear path out.



### Cancel & Wizards

Cancel is particularly import in Wizards. Let people leave at any time, but make sure to tell them where they can finish the task later on. When you user-test, bring back two weeks later the same people whom you had cancel in the middle of a task and ask them to continue. Watch where they browse. If they browse to two different places in your menus, consider putting the function both places.



*   **Principle: Make it easy and attractive to stay in**

A clear, visible workflow that enables people to understand where they are and move either backward or forward in a process will encourage people to stick with a task. Consider, as an example, a multi-step checkout procedure. Making the navigation visible by putting each step on a clearly-labelled tab will let people know where they are in the process. Clicking an earlier tab should allow people to jump back to correct an error or just change their mind by, for example, selecting a different delivery address. They should then be able to click on the tab they were originally on and resume their forward movement. When you either forbid people to move back or destroy all subsequent data if they do, they will not be happy with you. Even if they decide to grit their teeth and continue with the current sale, they are unlikely to ever return.



---

## Fitts’s Law

*   **Principle: The time to acquire a target is a function of the distance to and size of the target**

Use large objects for important functions (Big buttons are faster). Use small objects for functions you would prefer users not perform.

Use the pinning actions of the sides, bottom, top, and corners of your display: A single-row toolbar with tool icons that “bleed” into the edges of the display will be significantly faster than a double row of icons with a carefully-applied one-pixel non-clickable edge between the closer tools and the side of the display. (Even a one-pixel boundary can result in a 20% to 30% slow-down for tools along the edge.)

While at first glance, this law might seem patently obvious, it is one of the most ignored principles in design. Fitts’s law (often improperly spelled “Fitts’ Law”) dictates the Macintosh pull-down menu acquisition should be approximately five times faster than Windows menu acquisition, and this is proven out.

Fitts’s law predicted that the Windows Start menu was built upside down, with the most used applications farthest from the entry point, and tests proved that out. Fitts’s law indicated that the most quickly accessed targets on any computer display are the four corners of the screen, because of their pinning action, and yet, for years, they seemed to be avoided at all costs by designers.

*   **Multiple Fitts: The time to acquire multiple targets is the sum of the time to acquire each**

In attempting to “Fittsize” a design, look to not only reduce distances and increase target sizes, but to reduce the total number of targets that must be acquired to carry out a given task. Remember that there are two classes of targets: Those found in the virtual world—buttons, slides, menus, drag drop-off points, etc., and those in the physical world—keyboards and the keys upon them, mice, physical locations on touch screens. All of these are targets.

*   **Principle: Fitts’s Law is in effect regardless of the kind of pointing device or the nature of the target**

Fitts’s Law was not repealed with the advent of smartphone or tablets. Paul Fitts, who first postulated the law in the 1940s, was working on aircraft cockpit design with physical controls, something much more akin to a touch interface rather than the indirect manipulation of a mouse. The pinning action of the sides and corners will be absent unless the screen itself is inset, but the distance to and size of the target continue to dictate acquisition times per Fitts’s law just as always.

*   **Principle: Fitts’s Law requires a stop watch test**

Like so much in the field of human-computer interaction, you must do a timed usability study to test for Fitts’s Law efficiency.

For more on Fitts’s Law, see my [A Quiz Designed to Give You Fitts](http://www.asktog.com/columns/022DesignedToGiveFitts.html)



---

## Human Interface Objects

Human-interface objects are separate and distinct from the objects found in object-oriented systems. Our objects include folders, documents, buttons, menus, and the trashcan. They appear within the user’s environment and may or may not map directly to an object-oriented program’s object. In fact, many early GUI’s were built entirely in non-object-oriented environments.

*   **Principle: Human-interface objects can be seen, heard, felt, or otherwise perceived**

Human interface objects that can be seen are quite familiar in graphic user interfaces. Objects that are perceived by another sense such as hearing or touch are less familiar or are not necessarily recognized by us as being objects. Ring tones are auditory objects, for example, but we tend to just think of them as ring tones, without assigning any higher-level category to them.

*   **Principle: Human-interface objects have a standard way of being manipulated**

Buttons are pressed, sliders are dragged, etc.

*   **Principle: Human-interface objects have standard resulting behaviors**

Dropping a document on a trash can does not delete it, it stores it in the trash can. Selecting “Empty Trash” is necessary to actually delete it.

*   **Principle: Human-interface objects should be understandable, self-consistent, and stable**
*   **Principle: Use a new object when you want a user to interact with it in a different way or when it will result in different behavior**

If dropping a document on your delete-document icon will destroy it instantly and permanently, do not make it look like a trash can. People come with expectations about previously encountered objects. It’s important not to confuse or water down such expectations. For example, if you use a trash can icon, but instantly destroy documents dropped into it, it broadens the rule for trash cans. Instead of the rule remaining: “Dropping a document on a trash can does not delete it. Rather, it stores it in the trash can. Selecting ‘Empty Trash’ is necessary to actually delete it,” it will shift to, “Dropping a document on a trash can will destroy it either right now or sometime in the next six months to a year.” That is not only confusing for your users, it is damaging to every other developer that uses the trash can icon in the proper way.



---

## Latency Reduction

*   Wherever possible, use multi-threading to push latency into the background

Latency can often be hidden from users through multi-tasking techniques, letting them continue with their work while transmission and computation take place in the background. Modern web browsers can pre-fetch data, reducing the dead time when the user reaches the end of a task and must wait for the next page to appear.



*   **Principle: Reduce the user’s experience of latency**
    *   Acknowledge all button clicks by visual or aural feedback within 50 milliseconds
    *   Trap multiple clicks of the same button or object.

Because the Internet is slow, people tend to press the same button repeatedly, causing things to be even slower.



*   **Principle: Keep users informed when they face delay**

[![Chart of Delay Feedback Times & Indicators](http://asktog.com/atc/wp-content/uploads/Screen-Shot-2014-03-01-at-2.12.57p-3-1-14.png)](http://asktog.com/atc/wp-content/uploads/Screen-Shot-2014-03-01-at-2.12.57p-3-1-14.png)

Delay Feedback Times & Indicators



*   **Principle: Make it faster to begin with**

Eliminate any element of the application that is not helping. Be ruthless.

The sluggish speed of the early web set users’s expectations extremely low. (It also burst the Internet bubble when people realized they could get in their car and drive round-trip to the shopping center in less time than it took to “trick” the website into selling them something.) They have become less forgiving as time has passed.

Mobile, which has an architecture more in keeping with traditional GUI applications than web browsing, has been reminding people that computers can be fast, and they are even more impatient with slow-downs. Wearables will come with an even higher level of expectation: No one waits to see what time it is, and they will not wait to see who is calling, what the temperature is outside, or any other information to be displayed.

Automotive applications today are oftentimes sluggish, suffering from a fatal cocktail of weak hardware, poor design/coding practices, and high latency. Consider the car hurtling down the road at 88 feet per second (27 meters per second) while the user, eyes fixed on the flat panel display, waits to learn which of ACDC’s many fine works he’s currently enjoying. Imagine the rich irony when the accident report reveals it was “Highway to Hell.”



---

## Learnability

Ideally, products would have no learning curve: Users would walk up to them for the very first time and achieve instant mastery. In practice, however, all applications and services, no matter how simple, will display a learning curve.

*   **Principle: Limit the Trade-Offs**

Learnability and usability are not mutually exclusive. First, decide which is the most important; then attack both with vigor. Ease of learning automatically coming at the expense of ease of use is a myth.

**Do-It-Yourself Case Study: Ashlar-Vellum Graphite**

Rent yourself a copy of the high-end CAD/CAM program from [Ashlar-Vellum](http://www.ashlar.com) called [Graphite](http://www.ashlar.com/2d-3d-drafting/2d-3d-cad-graphite.html). Notice how it took you less than 10 minutes to learn how to do productive work. Then try doing the same thing with the leading CAD/CAM brand. Notice how after six weeks you’re still just staring at the screen, wondering what to do. (You can skip the other leading brand, but do rent and learn from Graphite. It will change the way you design.)

How do you decide whether learnability or usability is most important? The first thing you must do is identify **frequency of use**: Are you working on a product or service that will be used only once or infrequently, or is it one that will be used habitually? If it’s single-use, the answer is clear: Learnability. If someone will use this every day, eight hours a day for the rest of his or her life, the answer is equally clear: Usability.

Next, **who is the buyer?** If the person who will use it habitually will also make the buying decision, a product’s reputation for learnability may be a key factor in making the sale. That’s why you want to identify the most important of the two, then attack both.

*   **Principle: Avoid only testing for learnability**

Much usability testing involves running a series of tests at regular intervals with your spending only 20 minutes to an hour with each subject you recruit. You end up knowing everything about the initial learning curve and nothing about either the long-term curve or the end-state level of productivity.

If you are working on an application that will be used habitually, go about it entirely differently: Work with HR to hire temporary workers. Then, have them spend a week or two coming up to speed on the interface, monitoring them with time tests to see what the overall learning curve and the eventual efficiency of your interface actually prove out to be.



---

## Metaphors, Use of

*   **Principle: Choose metaphors that will enable users to instantly grasp the finest details of the conceptual model**

Good metaphors generate in the users’ minds a strong series of connections to past experiences from the real world or from a previous cyberspace encounter, enabling users to form a fast and accurate sense of your system’s capabilities and limitations.

*   **Principle: Bring metaphors “alive” by appealing to people’s perceptions–sight, sound, touch, and [proprioception/kinesthesia](http://en.wikipedia.org/wiki/Proprioception#Proprioception_and_kinesthesia)–as well as triggering their memories**

Try making your concepts visually apparent in the software itself. If that proves impractical, make it visual apparent through an illustration. The illustration should be compact and meaningful. Test it to see if it works, then embed it in such a way that every user that needs to see it will see it.

**Case Study**

**Apple’s HyperCard browser:** This precursor to the web, had a three-layer structure, with a Background layer in common with all cards in a deck (equivalent to across all pages on a website), a Foreground “card” layer, with elements pertaining to an individual card (page), and a logical control layer for the individual card, with all the buttons, etc. If you didn’t understand this concept, you couldn’t author in Hypercard, and few understood it until the graphic designer, Kristee Kreitman, drew an exploded picture showing the three layers. When we tested that, everyone got it instantly. 20 pages of perfectly-accurate text drafted by its inventor? Nothing. One picture? Total success.

![structure-hypercard-objects](http://asktog.com/atc/wp-content/uploads/structure-hypercard-objects.gif)

*Hypercard Three-Layer Exploded Diagram*



*   **Principle: Expand beyond literal interpretation of real-world counterparts**

Most metaphors evoke the familiar, but can and usually should add a new twist. For example, an electronic newspaper might bear a strong resemblance to a traditional paper, but with hyperlinks than enable users to quickly dive as far into articles as their interest drives them, something quite impossible with their paper counterparts. Not only is there no need to slavishly copy a real-world object (skeuomorphism), but unnecessarily limiting the functionality of a software counterpart just to “perfect” the imitation is most often bad design.

The inverse of skeuomorphism is abstraction, a prominent feature in so-called flat design, a fashion that took hold in 2013, turning once well-understood icons and other elements into meaningless abstractions and even false symbols. (For example, the icon for the browser on the iPhone became a compass, only connected to the concept of the web through the vaguest of abstractions. The iPhone has an actual compass, so they turned its icon into… another compass! Two compass icons: One tells you which way is north and the other connects you to your bank account. The Settings icon had originally looked like the inner workings of a clock, clearly carrying the message that this is an app that will let you see and affect the inside workings of the iPhone. That was abstracted to the point that it looks exactly like a large industrial fan.)

*   **Principle: If a metaphor is holding you back, abandon it**

A metaphor is intended to empower your user. However, there are times when it can also hold back your design.

**Case Study: Dish Pointer Maps**

DP Maps, as originally released in 2009 for the iPhone, used the time-honored map metaphor to enable people to aim TV satellite dishes.

![DPMaps](http://asktog.com/atc/wp-content/uploads/DPMaps_teaser.jpg)

It would superimpose TV satellite aiming information, including the direction to the satellite (the green line) on Google mapping data. Sometimes location and direction were fairly easy to interpret as in this case, where the user is standing in the parking lot of 1 Infinite Loop, Apple’s then-current headquarters. With such a unique location, surrounded by distinct landmarks, locating what building the green line should just miss when aimed correctly was pretty simple. It was not so simple when the user was standing in a wooded area surrounded by tens of thousands of trees, all of which look remarkably alike when viewed from outer space. That map metaphor had been best the developer could do for the original desktop version, when installers would look at locations on their computers at their office before going out to worksites. The iPhone, however, offered a new opportunity.

### A new pair of glasses

Often times, in reworking an old idea, you will want to “put on a new pair of glasses” as a way of looking at the old problem from an entirely different angle. In this case, my recommendation to the developer was that he do that quite literally, scrapping the map metaphor entirely in favor of giving people magical sight, so they could simply look up and see the communications satellites orbiting 22,000 miles in space. That’s exactly what he did:

![DPARPro](http://asktog.com/atc/wp-content/uploads/DPARPro.jpg)

*DP AR Pro*



To use the replacement app, you walk around outside or scramble around on the roof until you can see the satellite(s) you need against clear sky without anything in the way. Mount the dish there, and you’re done. No map interpretation skills are needed.



---

## Protect Users’ Work

*   **Principle: Ensure that users never lose their work**

This principle is all but absolute. Users should not lose their work as a result of error on their part, the vagaries of Internet transmission, or any other reason other than the completely unavoidable, such as sudden loss of power to a client computer without proper power protection. We’ve gotten so used to being the victim of data loss that we often don’t even notice it. So consider if what happens routinely on the web happened in real life:

You go into Harrod’s Department Store in London. After making your selections, you are asked to fill out a four-page form. A gentleman looks the form over, then points to the bottom of Page 3 at your phone number. “Excuse me,” he says, “Look there. See how you used spaces in your phone number?” When you nod, he continues, “We weren’t expecting you to do that,” at which point, he picks up the four-page form and rips it to shreds before handing you a new, blank form.

Of course, never in a thousand years would such an event take place at Harrod’s, but another venerated British institution did exactly that to me almost twenty years into the miracle of the world wide web when I was invited to give them my emergency contact information for an upcoming flight into London. Every time I would fill out all eight fields on the form, it would come back with an error message about at least one field, having destroyed the entire contents of all eight of them! I’m sure it was carrying out this wanton destruction for my own good, but I could not for the life of me figure out from the messages what it actually wanted. 20 minutes and two browsers later, I gave up. I’m sure other passengers are abandoning their effort far earlier.

Travel sites, in general, think nothing of repeatedly tossing all the information the user has entered about cities, times, days of travel, frequent flyer numbers, anything that takes time and trouble to type in. The user may attempt nothing more radical than leaving a half hour later, but that is apparently grounds to destroy their choice of departure city and date as well as arrival city and date. If the user is impolite enough to go to the bathroom, well, that sort of activity poses a significant security risk, so of course their entire evening’s work must be destroyed, with a message explaining its been done for their own good.

Travel sites may be the tip of the iceberg, but websites in general, are notorious for their cavalier attitude when it comes to their user’s hard work, and it doesn’t stop there: Traditional applications continue to crash and burn, and the excuses for entire computer systems crashing and burning are at an end. Small portables can survive a power outage. It’s no longer acceptable that many of today’s high-end desktop computers and operating systems still do not support and encourage continuous-save. That, coupled with a small amount of power-protected memory, could eliminate the embarrassment of $5000 machines offering less reliability than 10-cent toys.



---

## Readability

*   **Principle: Text that must be read should have high contrast**

Favor black text on white or pale yellow backgrounds. Avoid gray backgrounds.

*   **Principle: Use font sizes that are large enough to be readable on standard displays**

You must demand of your marketing people that they tell you what the expected range of your customer’s standard displays will be. You then need to work with your graphic design and engineering people to ensure that your code will show up in appropriate sizes across that range of displays. It need not be one-size-fits-all. For example, CSS can mold itself to the system in which it finds itself.

*   **Principle: Favor particularly large characters for the actual data you intend to display, as opposed to labels and instructions.**

For example, the label, “Last Name,” can afford to be somewhat small. Habitual users will learn that that two-word gray blob says “Last Name.” Even new users, based on the context of the form on which it appears, will have a pretty good guess that it says “Last Name.” The actual last name entered/displayed, however, must be clearly readable. This becomes even more important for numbers. Human languages are highly redundant, enabling people to “heal” garbled messages. Numbers, however, unless they follow a very strict protocol, have no redundancy, so people need the ability to examine and comprehend every single character.

*   **Principle: Menu and button labels should have the key word(s) first, forming unique labels**

Experienced users read only as much of an item name to differentiate among items. Highly experienced users actually trigger on the difference in the external shapes of the entire first word(s) without ever actually reading anything.

*   **Principle: Test all designs on your oldest expected user population**

Presbyopia, the condition of hardened, less flexible lenses, coupled with reduced light transmission into the eye, affects most people over age 45\. Do not trust your young eyes to make size and contrast decisions. You cannot.

*   Principle: There’s often an inverse relationship between the “prettiness” of a font and its readability.

Specifically, anti-aliasing softens the edges of a font, giving it a much smoother appearance on the digital page. The problem is that the human vision system responds to sharp edges, so, in smaller font sizes, an anti-aliased font, while often appearing more attractive, can be quite difficult to comprehend.There are anti-alias techniques that specifically increase the sharpness of the edges the eye is seeking, so this is not strictly a black and white issue (so to speak), but it is definitely something of which you should be aware and not something in which every graphic designer has been schooled. You will want to run some reading speed and comprehension tests on proposed font changes.



---

## Simplicity

*   **Principle: Balance ease of installation vs. ease of use **

As designers, we need to strive to simplify users’ lives. That often requires a delicate balance between our effort to make installation of a product easier and making subsequent use of that product easier or better.

Consider the autofill feature for browsers: The user is required to enter and maintain a database of information the browser can then drop into a form at the user’s command. It takes time to set it up, and every time anything changes, it’s just one more record that has to be altered. What’s more, it often fails to work, either not responding or putting incorrect data all over the place.

Apple has simplified the setup process by enabling the user to link Safari’s autoFill to the user’s contact card in his or her address book. However, the ability of Safari to actually fill out a form is just as dismal as it’s ever been, largely because there is no standardization of labels, locations, or anything else in forms.

I have solved the autoFill problem with a more technically complex solution: I use an app called Keyboard Maestro that sits in the background looking for certain key combinations. When it finds one I’ve programmed, it automatically replaces the text I’ve typed with a string of text I’ve previously stored. Setup was definitely more difficult, but now when I open a form and a field calls for my first name, I type, “bbbb” and it’s replaced with “Bruce.” I type “aaaa” and my address appears, “pppp” and my phone number pops into place, etc. It takes me 30 seconds to fill out a form, longer than autoFill would if it actually worked, but this method works on every single form every single time. It saves me time, effort, and frustration.

Often, you can assume that one user in the house will be technically inclined. When you have a trade-off between simplicity of installation/set-up and ease-of-use, get together with your marketing people. If they tell you that you can depend on at least one reasonably clever or sophisticated user, do make life a bit more difficult at first if it will make subsequent use a lot simpler for everyone else. However, expend effort making both installation and operation as simple as possible. That’s the approach that Nest took, where one person in the house must go through a complex and confusing process to tie their products to the Internet, but thereafter the lives of everyone in the house become simper.

(In Nest’s defense, they are doing their best to overcome a major flaw in the way Wi-Fi set up to work. It requires users to leave their normal Wi-Fi and log in to a new “network” with a gobbledygook name which is, in fact, their Nest device. This is a weird, backwards activity that throws most users the first time they encounter it. It also requires their going into the “basement area” of their phone or tablet, a place most users avoid whenever possible. It’s all-around bad, and the committees that oversee the Wi-Fi protocol need to address the issue if connected devices are to take off on an expanded basis.)<a name="illusion-of-simplicity"></a>

**Principle: Avoid the “Illusion of Simplicity”**

In the early years of this century, Apple became so focused on generating the illusion of simplicity for the potential buyer that they began seriously eroding the productivity of their products. They thought they had a good reason: They wanted new products to look bright, shiny, and simple to potential users. That’s an excellent goal, but actual simplicity is achieved by simplifying things, not by hiding complexity. (See Visibility.)

It’s just fine to make your showroom products look simple, but, to the extent you want to hide complexity to avoid scaring away buyers, do so in the showroom, not in the home or office of the purchaser now trying to accomplish real work. I started putting a special Dealer Mode into Apple software in 1978, so that the product would look and act differently in the showroom than in the buyer’s home. Computers allow that. Somewhere along the line, people forgot.

**Principle: Use Progressive Revelation to flatten the learning curve **

It is OK to make the user’s environment simpler when they are learning by hiding more advanced pathways and capabilities, revealing them when users come to need them and know how to handle them. This is distinct from the illusion of simplicity, where necessary controls are made invisible or hidden in obscure and unusual places so that users have to go on treasure hunts to find the tools they need to use right now.

Progressive revelation can cut down on support costs by eliminating calls from users trying to understand advanced capabilities before they have learned enough about the task domain to need them. It can also raise costs if advanced features are not introduced when they are needed or are too well hidden.

**Principle: Do not simplify by eliminating necessary capabilities **

This became another Apple problem after the release of their mobile devices. In 2014 on a Mac, you can set an alarm that will trigger 90 minutes before a calendar event. On the iPad, you can set a trigger for either one hour or two, but not 90 minutes. If a person needs a warning 90 minutes before the event, that’s when they need the warning. Apple has “simplified” the interface by giving the user no way to set an arbitrary time. No weakness or defect in the underlying interface would prevent Apple from giving users this capability. It is a conscious decision to limit what people can do with the product.

The way you set a 90 minute warning on an iPad is to create a second event, 30 minutes before the real event, and set a 60 minute warning.

How is that simpler?

Likewise, they have a very simple interface for finding photographs in your collection: You look through all your folders of photographs, one at a time, until you find the picture you’re looking for. Apple will neither display nor allow you to sort/search on the title, caption, or keywords you’ve carefully associated with your images. One can argue that the interface is simple: If you want to find a specific photo among that 20,000 on your iDevice, just look through your 73 folders you’ve created in iPhoto or Aperture to hold them until you find it. You don’t have to learn about searching, you don’t have to remember the name, you just have to have 10 to 20 minutes on your hands to spend the time looking.

How is that simple?

Fortunately, after many years, help is at hand: Apps like [Photo Shack HD](https://itunes.apple.com/us/app/photo-shack-hd/id478872437?mt=8) (the HD is important) enable you to search on all the criteria that Apple is importing but refusing to show you. That’s OK for really advanced features. However a remarkably high percentage (100% to be exact) know how to search.



---

## State

*   **Principle: Because many of our browser-based products exist in a stateless environment, we have the responsibility to track state as needed**

Our systems should “know”:

*   Whether this is the first time the user has been in the system
*   Where the user was when they left off in the last session
*   What the user has found of interest based on time spent with a pointing device moving, objects being touched, etc., in different areas
*   Where the user has been during this session
*   Where the user is right now and what they are doing

and myriad other details. In addition to simply knowing where our users have been, we can also make good use of what they’ve done.

One site with which you are familiar is so involved in and good at tracking state that it could be described as a state-tracking system that happens to do other stuff. That site is amazon.com. Their uncanny ability to make suggestions on what we might want to explore and buy is the result of their understanding our full history on their site. They know what expensive items we’ve come back to repeatedly in the past, what we’ve lingered over recently, and what would go well with what we just or recently purchased based on like-minded individuals.

*   **Principle: State information should be stored in encrypted form on the server when they log off**

Users should be able to log off at work, go home, and take up exactly where they left off. Following the principle of [Protect Users’ Work](#protectUsersWork), whatever they were last working on should be preserved in its current condition.

A private service for doctors, _Physicians On Line,_ does an excellent job with this. Doctors can be 95% of the way through a complex transaction, log off, log in again six weeks later from another part of the world, and the service will ask them if they want to be taken right back to where they were.

“Track State” came late to this list, in 1996\. Up until then, everyone had been tracking state on their own, without question. Because the web browsers failed to provide any tools beyond the purple color of a link indicating that link had been previously visited, engineers took this to mean they no longer needed to concern themselves with state at all. To the contrary, what it meant is that, from that day until this, applications engineers and designers have had to take over the full responsibility for tracking state that had historically been shared with the systems engineers, making the job that much harder.

*   **Principle: Make clear what you will store & protect the user’s information**

State data is neither good nor evil, but it can be put to both uses. You should make clear in your privacy policy that you will be saving data, making your case for why it is in the user’s interest. Any data from the user, including state data, should be encrypted and safeguarded.



---

## Visible Navigation

(See also: [Discoverability](#discoverability))

*   **Principle: Make navigation visible**

Most users cannot and will not build elaborate mental maps and will become lost or tired if expected to do so.

The World Wide Web, for all its pretty screens and fancy buttons, is, in effect, an invisible navigation space. True, you can always see the specific page you are on, but you cannot see anything of the vast space between pages. Once users reach our sites or web-based applications, we must take care to reduce navigation to a minimum and make sure the remaining navigation is clear and natural. Ideally, present the illusion that users are always in the same place, with the work brought to them, as is done with the desktop metaphor. This not only eliminates the need for maps and other navigational aids, it offers users a greater sense of mastery and autonomy.

While you may have a thousand pages on your site, if every one of them has the same heading and the same main and secondary menus, the illusion to the user will be that she is always on the same page with content changing in one panel of the page. They can still be lost if they don’t know what panel they are viewing, so reinforce it by highlighting the current menu items that resulted in that particular panel, as well as offering them, in development systems that support it (and they all should), bread crumbing, such as:

[NN/g Home](http://www.nngroup.com/index.html) ![>](http://www.asktog.com/images/arrow_white.gif) [AskTog](http://www.asktog.com/index.html) ![>](http://www.asktog.com/images/arrow_white.gif) [Interaction Design Section](http://www.asktog.com/menus/designMenu.html)

to help them build a mental model. As with the inherent statelessness of the web (see [Track State](#trackState), above), we must go beyond blindly accepting what the web’s architects have given us by adding layers of capability and protection that users want and need. That the web’s navigation is inherently invisible is a challenge, not an inevitability.

*   **Principle: Limit screen counts by using overlays**

In designing complex apps, strive for a minimal number of screens, each representing a separate and distinct task the user will be performing. When a user needs to perform a subtask, bring up an overlay that is smaller than full screen, so that users can see a darkened image of the main screen still present in the background. What is seen need not be memorized, so users need not remember how that overlay maps onto the screen behind it.



---

## Next Steps

If you want more, consider joining me for three days for my Interaction Design Course. It’s practical, engaging, and we always have a lot of fun. You’ll find the schedule close to the top in the right-hand column. Until then, thanks for reading.

(The copyright notice that follows you will discover is, essentially, a release for you to copy this post as much as you want as long as you aren’t publishing it for money.)  

---

## Copyright

“First Principles of Interaction Design” is copyright 1978-2014 by Bruce Tognazzini. Permission to make copies for personal use is granted without reservation, provided this copyright notice remains on the copy. Please contact the author for permission to republish on a web site, to publish in bound form, or to make multiple copies.

*   Exception: Educators and in-house corporate trainers may make sufficient copies for their own students.
*   Exception: This work has become a standard for heuristic evaluation and cognitive walkthrough, as well as day-to-day design work, and nothing about this notice should limit its application to those endeavors, regardless of whether they are for commercial or non-commercial use, including sufficient reproduction of copies for teams carrying out such work.

No commercial use may be made of the work beyond these exceptions without permission. This notice must be retained together with any version of the work.

If you want to translate this work and make your result available for free, [please contact me](http://www.asktog.com/misc/mailer.html) so we can exchange links.

In other words, I want people to make free and full use of this material, I just don’t want people to claim it as their own or to cynically make money off something that I am attempting to offer for free.
