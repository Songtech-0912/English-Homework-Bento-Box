# The Nuance of the Ethical Source Controversy

By Jacky Song

Disclaimer: I am not affiliated with the FSF, OSI, ESM or any other organization mentioned below.

In 1985, the world saw the birth of a new idea that would radically change the landscape of technology. Richard Stallman founded the Free Software Foundation, a charity dedicated to the promotion, creation, and education of free (libre) software. Over nearly four decades, the FSF, and its partners (including the OSI, Linux foundation, and others) have created a world in which nearly any programmer can run, edit, contribute to, and redistribute computer programs. Once an avant-garde idea, the freedom to make your own copy of software is now accepted as an industry norm.

In 2020, a new movement arose, and it promised to radically change the landscape of technology again. The Ethical Source Movement aimed to revolutionize the ideas of the Free Software and Open Source movements. It promised to end what it called "the misuse of [open-source] software".

Only this time, it was different. Instead of going mainstream, the ESM became quickly mired in controversy. Free/libre software communities were quick to condemn the ESM, and the resulting reception caused very few mainstream free/libre projects to adapt the license. So what went wrong?

*Before I start my discussion, I should note that while I try to be nuanced in my analysis, I am not going to be impartial. So read all of this with a grain of salt.*

## The Crux of The Controversy

The major gripes of anti-ESM communities were centered, and still are mostly centered, on the ESM's mission of "empowering developers". In essence, this means that developer should be able to control how their software is used. The ESM regards this principle as essential to "prohibiting mass surveillance, anti-immigrant violence, protester suppression, racist policing, the deployment of cruel and inhumane weapons, and other human rights abuses all over the world".

Unfortunately, this runs counter to the free/libre software movement's ethos of *user freedoms*. That's because *if* a project adopts an ESL (Ethical Source License), developers inherently have the right to tell users what they can and cannot do with their software. An ESL restricts a user's freedom to use software in certain ways, among which are using software for human rights abuses. It should be pointed out, as well, that most free/libre software supporters don't agree with using software for human rights abuses either. So why the disagreement, then?

Well, because of its central principle: developers are in control, *not users*. And a brief thought experiment will demonstrate this issue.

Imagine a developer who is a member of a pro-life group and an anti-abortion activist. We will call this developer "Adrian", a unisex blanket name, for the sake of argument. Adrian, as a developer, likes the idea of free/libre software. Thus, Adrian chooses to adopt the MIT/Expat license in every future personal project - with one caveat. Adrian adds this line to the GPL license:

```
...

You must use the Software for Good, not Evil
```

Besides the obvious nature of how anyone would enforce these terms, Adrian has now created another major issue. Remember that Adrian is pro-life and an anti-abortion activist? Well, it would be logical to presume that Adrian would also perceive "good" and "evil" in a certain fashion. For instance, suppose Adrian creates an application that helps users rate facilities for pregnant women based on their quality, hygiene, services, etc. As mentioned previously, this application would be released under the forked MIT/Expat license, with the statement prohibiting using the software for "evil". As this is the case, it would be reasonable to assume that when Adrian is developing this app, Adrian deliberately turns off the ability for users to rate abortion clinics.

Now imagine a hypothetical scenario in which a pro-choice abortion activist makes a fork of Adrian's app, and turns the ability for users to rate abortion clinics back on. This would be a breach of Adrian's personal values regarding "good" and "evil", and because Adrian is the developer, Adrian has the power to stop the user from using and/or distributing the app. Adrian's exact beliefs don't matter, because as long as the clause of *"for Good, not Evil"* remains, Adrian has the power of enforcing these ideas. Existentially, if you place restrictions on free/libre software, it is no longer "free as in freedom".

The ESM is admittedly better in this regard, because it references the Universal Declaration of Human Rights, probably the most authoritative document of what constitutes "good" and "evil" in all of human history. Still, the issue is that a developer has power to *re-interpret* certain uses of software as wrong, and therefore in violation of the license. Subjectivity is a horrible idea, when everyone can re-interpret usage differently; Big Brother would perceive software that could track dissidents as "good" and software used for organizing protests as "evil". Now think of the wider picture - how many people would be excluded from using software, just because a developer and a user disagree on a violation of an ESL, and the developer has the power to deny the right to use the software to the user?

Besides, one may consider the whole point of the ESM to be fundamentally flawed, because any entity that wants to "do evil" will rarely follow a license's terms. Consider how many nations today do not follow their Constitution, the highest of laws. Why would they follow a software license, the lowest and sometimes the simplest of laws, that tells them to not do evil, or to commit human rights abuses?

## My Stance

I really don't think that using free/libre software for ostensibly evil purposes is a good idea. Yet, I cannot infringe on a user's rights on how they can use my software.

I believe that the way forward is to include the ideals of using free/libre software to protect human rights outside of a legal framework. That means, instead of saying *"You must use the Software for Good, not Evil"*, you would say: 

```
"Please use, modify, and distribute the Software in accordance with the Universal Declaration of Human Rights, and in a manner that protects the human rights of users, though it is not legally-binding. Be aware that an infringement of this recommendation will cause action to be taken, even if it is not a violation in legal terms."
```

In conclusion, I understand the issues that prompted the ESM to arise. I understand why they stress on giving power back to the developer, rather than the users. I fully accept that they are doing this in good faith.

But no, I don't agree with the ESM or its ideas.
