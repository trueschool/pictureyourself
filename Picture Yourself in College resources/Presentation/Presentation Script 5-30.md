### Describe your app.  What was the problem you were trying to solve?  How does the functionality of your app address this problem?
 Six years. This app needs to be relevant to a student's life from middle school until they graduate high school. Six years ago next month, the first iPhone debuted, and the world of mobile has never been the same since. Think of the apps you were using six years ago. Which ones are you still using now?  	What characteristics do those apps have?
 ![The Original iPhone][1]
 
** Picture Yourself in College** is designed to solve two problems: One is that younger students (and less academically-engaged students) are more motivated by immediate goals like friends, developing their identities, and engaging in social interaction rather than working on "college readiness"-- an abstract concept that lives far in their uncertain future. The second is that many underserved students do not receive messages from their schools, families, and society telling them that they are "college material"-- these students often assume a four-year university is out of reach for them and do not apply. 

**Picture Yourself** aims to become a part of young students' lives by balancing a fun, social camera sharing app with scaffolded activities that help students build their college application over six years. More than that, they build an identity as "college material" by breaking down the daunting task of preparing for college into scaffolded, manageable steps. They also build that identity by sharing college-themed photos of themselves to their social networks and publicly declaring their intention to go to college. 
 
### Now that you’ve had some time to think about what you hacked, what changes would you make if you were going to flesh out the app?

The photo manipulation component of the app might be updated to provide a similar experience with fewer technical barriers. Removing the background from images is technically challenging and less-than-reliable. Adding college-themed "stickers" over photos (as in [Aviary Stickers][2])can happen out of the box with the [Aviary SDK][3] and can provide other desirable photo editing effects while staying consistent with the app's overall vision and objectives.  

The app needs a server side component that can handle the interactive features such as periodic updates, media storage, college milestones, and so on. These features would require deeper technical knowledge than I personally have, so I'd like to work with a back-end coder who has PHP or similar experience. 

Additionally, I have been working on version 0.2 of the app mockup, built on a more solid HTML5 foundation that should gracefully integrate with the more advanced features once they're developed. The original was built quickly in [Tumult Hype][4], a tool that produces great-looking mockups with questionable code. [Twitter Bootstrap][5] is a professional grade mobile webapp framework that will support whatever advanced functionality we can develop.

Currently I am developing the app in HTML5 with the intention of using [Trigger.io][6] to port it to all of the major mobile phone platforms. 
 
### Question to audience:  based on what you’ve just heard, what changes would you recommend?
 
 (take notes)
 
### What is your interest in continuing to develop the app?  What would you see as a good timeline for bringing it to implementation?
 
I have a full-time job and am not currently looking at this as a career move as much as a hobby/volunteer activity. Mostly, I am motivated to stick with it because I believe this app should exist in the world and can potentially do a lot of good. 

I think the timeline should be defined in work-hours, not months or weeks, as I don't know whether this will become someone's full-time job or a "nights and weekends" pursuit. 
 
### If we invite you to build the app, would you be open to working together to blend or modify the apps and perhaps create a new/hybrid model?

I would be happiest to collaborate with a team that can bring the technical and marketing expertise I lack. My strengths are pedagogy, front-end design, and creative vision, and those I will happily contribute to this group's finished product, even if it's a hybrid vision.


[1]: http://web.archive.org/web/20070607062543im_/http://images.apple.com/iphone/images/indexhero20070109.jpg
[2]: https://play.google.com/store/apps/details?id=com.aviary.android.feather.plugins.stickers.free_stickers&feature=more_from_developer#?t=W251bGwsMSwxLDEwMiwiY29tLmF2aWFyeS5hbmRyb2lkLmZlYXRoZXIucGx1Z2lucy5zdGlja2Vycy5mcmVlX3N0aWNrZXJzIl0.
[3]: http://www.aviary.com/
[4]: http://tumult.com/hype/
[5]: http://twitter.github.io/bootstrap/
[6]: https://trigger.io/