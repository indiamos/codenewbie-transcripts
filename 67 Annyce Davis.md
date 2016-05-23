# Episode 67 • [Android Developer](http://www.codenewbie.org/podcast/android-developer) • Annyce Davis
December 21, 2015

**Saron:** Welcome to the CodeNewbie podcast, where we talk to people on their coding journey in hopes of helping you on yours. I’m your host, Saron, and I wanna tell you about our incredible sponsors.

Digital Ocean offers simple cloud hosting built for developers, and for all the code newbies who just started learning to code—yes, that means you—they’ve got one-click solutions for Rails, Django, Node, and much more, so you can launch your app in no time. And if you’re looking for full control of your server, they’ve got that, too. You can use the promo code “CodeNewbie” to get a $10 credit, so check ’em out.

I also want to tell you about Linode, where you can get a high-performance SSD Linux server for all your infrastructure needs. With eight data centers, native SSD storage, 40 GB network, Intel E-5 processors, you can get access to a powerful server and get it up and running in under a minute. Plans start at ten bucks a month, and if you go to linode.com/codenewbie and use the promo code “codenewbie10” before December 31, 2015, you can get a $10 credit, so give it a try.

Today on the show I am so excited to have Annyce Davis, senior software engineer at the Washington Post. Annyce, do you wanna say hi?

**Annyce:** Hi, everybody.

**Saron:** So, when people think of the Washington Post, and they think of, you know, print media and newspapers and all that, the idea that Washington Post has a team of developers and engineers might be a little…interesting? And I’d love to kind of hear a little bit about what the—you know, what it’s like to be a software engineer at one of the oldest newspapers that we have in the U.S.

**Annyce:** So, one really interesting thing about working at the Post is that when you tell people, the first question they ask you is, “So, you’re a reporter?” And for a while, I was really surprised by the question. Like, “No, of course not!” You know, I’m a developer. This is what I do.

**Saron:** Of course not! That’s preposterous!

**Annyce:** But it’s a really fair question, because I feel that only recently has the Post really been more vocal and visible about the amazing things that are happening inside of the engineering team. And so one way I heard it put is basically that we’re a startup inside of an older organization. And so that’s really how we work as an engineering team. We are on a DevOps model, and we’re always trying out the new technologies that are coming, and we’re trying to think in an innovative way when it comes to news and how users consume it.

**Saron:** So, when I hear about being in a startup inside of a much larger company, I’ve heard there’s lots of pros and cons to that, right? When it works, it works really well; you get all the support and the resources of the larger institution, but you get to kind of do whatever it is that you want. So as a developer, does it end up working out that way?

**Annyce:** I’ll say yes and no, to be fair. I feel that just coming from the perspective of an Android developer, a lot of times, most of these key stakeholders, they all have iOS devices. So perhaps they don’t really put the same amount of importance or weight on, you know, what we’re doing as far as Android is concerned. And so that’s one thing that I’ve found challenging working as an Android developer in such a large company. But I feel that, like, slowly but surely, Android is finally getting its time in the sun, I guess. And more and more people are recognizing how important the Android ecosystem is to users in general and to being a successful, I’d say, business.

**Saron:** So that’s a really good point, because for a long time it’s been iOS, iOS, iOS. And I know that a lot of people in our community are learning Android. And so I’m wondering has anything happened in recent years that, you know, in your opinion has made Android more important and more of a priority for dev teams.

**Annyce:** I have to say it’s the effort by Google, because, you know, they’re the keepers, mostly, of all things Android. And I think they finally recognize that just doing something that’s cool is not good enough. You have to actually care about marketing and design and user experience. And once they started putting more of their, you know, muscle behind that, I feel it started to open up the eyes of others to what is possible on Android. Also I think the fact that Android is gonna be pretty strong in a lot of the emerging markets makes a huge difference. So if you want to be the first to tap into the next billion users that are gonna come online, that’s going to be through Android.

**Saron:** Oh, that’s very interesting. So when you think about the priorities of Washington Post, is emerging markets something that’s part of the conversation for them?

**Annyce:** Not that I’ve heard of.

**Saron:** It is called the *Washington* Post, right?

**Annyce:** Yeah, definitely. We’re focused on reaching more people internationally, nationally, but I’m not sure if they have a strategy in place yet for the emerging markets.

**Saron:** So you are our very first Android developer on the show, which I’m very excited about, because we haven’t done too many conversations on mobile development and that—it’s something that I really want to start doing more of for our community. And so I would love to hear a little bit about how you got into Android and how you picked that for the, you know, the mobile focus of your career.

**Annyce:** Sure. So, I started out as a Java developer doing enterprise applications, so I would think of myself at that time as more of a backend developer. And maybe around four years ago, I was still one of the holdouts who had a Blackberry.

**Saron:** Go, you. That is loyalty and dedication, and I respect that.

**Annyce:** And then finally, you know, I decided to get another phone, and I chose an Android device. And for me it was just so amazing that I could create something that I could just carry around with me all the time. And prior to that, you know, when you tell your friends, “Oh, I’m a developer,” they think, “Oh, okay, well, can you fix this issue that I’m having with my printer?” They really have no concept of what you do. But working in the mobile space is really awesome, because you can make something, have it on your phone, and you can show it and share it with everyone. So for me that was a huge draw to migrate to being an Android developer. And it was a pretty logical move, because Android uses Java as the programming language.

**Saron:** So when you decided to get an Android, did you consider getting an iPhone?

**Annyce:** Honestly, no, I really didn’t.

**Saron:** Interesting! Why not?

**Annyce:** I guess I like the appeal of the Android community. I kind of like having something where it’s a little broken and I get to figure it out on my own. I mean, at that time, if we go back four or five years ago, when Android was really just getting started, the experience honestly really couldn’t compare to what you had available on an iOS device. However, you had more power as a user. And that’s something that I find amazing with Android. I could easily see, you know, what’s happening in the background, access all the files in my file system,… So, to me, that was the appeal. And as a developer, I always sort of want to tinker with what’s happening behind the scenes. And so for me, Android, you know, allowed that to happen.

**Saron:** So, as a developer I completely understand how important it can be to have that power, right? To have that ownership and to build whatever you want. Has that been frustrating at all? Like, having all that power and maybe not always making the best decisions? Like, that’s been kind of the crux between Android and iOS, right? iOS says, “We know what’s better for you,” and Android says, “You can do whatever you want.” As a developer, has the “You can do whatever you want” ever been too *much* responsibility?

**Annyce:** I would say it’s not too much responsibility, but it definitely can be frustrating. Because, for instance, with iOS they may say, “This is the way you load an image.” Okay, great. With Android, it’s more like, “These are the ten ways that images can be loaded.” And then it’s up to you as a developer to decide, “Well, which one is best for me, my team, my organization?” And what’s more, those ten ways are constantly evolving. So with every release, every operating system, every device, it may change—“Well, actually, you can only do five of those ways on *this* device…”

**Saron:** Ah.

**Annyce:** So, yes, that can be a little frustrating. But I think when—the benefits outweigh the negatives, I’ll say.

**Saron:** So I want to hear a little bit more about how you learned to be an Android developer. I’m being very honest—I know nothing about it, I don’t really know anything about Java. So what was that transition like, to go from doing enterprise-level Java work into Android?

**Annyce:** So, the first thing was realizing that a phone is not a computer.

**Saron:** Interesting!

**Annyce:** And that seems, like, really obvious—of course it’s not!—but that means that it’s a very constrained environment. So the memory is not the same, and the speed is not the same, and the number of processors is not the same. So you have to be, you know, very cognizant all the time of the objects that you’re creating, making sure that things are able to be destroyed properly. And to be honest, when you’re working on, you know, a Web application, that’s not something that you’re constantly concerned with. But you have to really start thinking about it a lot as a developer for mobile devices. So one thing I did was—my brother actually had the great idea to make a word game. So he literally just kind of sat down one day and said, “Okay, what would it take to make a word game for Android?”
And for me that was amazing, because that was an app that I was really proud of, with, you know. just my brother and I. And it really taught me a lot about the Android operating system and handling memory and things like that.

**Saron:** Is he developer, too?

**Annyce:** He is not a developer. He’s just a super-smart guy.

**Saron:** Yeah. So was that your first Android project?

**Annyce:** So, my very first Android project was actually for work. We had an application and I was able to convince my boss that we should make a native Android app. So that was my very first project, and from there—

**Saron:** Wow. That’s a big project.

**Annyce:** Yeah, it was very exciting at the time. I think it was, like, Android one-dot-something. So it was definitely very challenging to work with Android at that point. But I guess I’m really honored to have been there from the very beginning, because now I can fully appreciate where we are right now.

**Saron:** Yeah. So when you convinced your boss to have that native Android app, what’d you say, what did you do to, you know, get him onboard?

**Annyce:** So the first thing that I did was I sort of made a rough prototype—like, on the side, on the weekends—to say, like, “Look, I already kind of have this rough, you know, prototype going. It wouldn’t be too much more work to make it something that’s viable that we could ship.

**Saron:** Nice.

**Annyce:** And, honestly, I think that’s a good tip for others. If there’s something that you’re really interested in and passionate about, you know, why not just do a little proof of concept and see if it’s something that you can kind of make your real full-time thing.

**Saron:** That is such good advice, because I’ve heard a lot of stories in the CodeNewbie community of people who are not doing, you know, coding on the job but want to get into it—you know, want to find little avenues, little pathways. So if you have an idea of something you want to code, and you do a little prototype on the weekend and then come in and say, “Hey, I could finish up this really awesome idea for you,” it sounds like that worked for you.

**Annyce:** Right.

**Saron:** So what was the process like of learning Android? Was it, you know, a lot of tutorials and searches? Was it talking to people? What was that path like?

**Annyce:** So, in the beginning there wasn’t a lot of talking to people, to be honest. There was just a very nascent group of Android developers. So I would say the main thing was tons of googling and… Stack Overflowing, I’ll say.

**Saron:** I’ve never heard that before. That should be what it’s called—Stack Overflowing. 

**Annyce:** Pretty much. That’s a skill in itself. But, yeah, and just reading the documentation. I did pick up one Android development book. It was like the most basic, bare-bones, you know, intro to Android. Just so I could wrap my head around the life cycle. And when I say “life cycle,” I’m basically just referring to, in Android when you launch an application, okay, what is the process? What’s sort of happening behind the scenes, when a user sees the buttons and the text and the images. There’s actually a lot going on back there. And so I wanted to make sure I really understood that, so that I could, obviously, make the best app possible.

**Saron:** So, knowing everything that you do now—and you’ve been working on Android for, you said, six years?

**Annyce:** So, about the past, like, four or five years.

**Saron:** Four or five years, yeah. So, knowing everything that you know now, what advice do you have for people who are listening who might be looking into doing mobile development and are picking between Android and iOS and are not sure really how to think about it.

**Annyce:** That’s a great question. I think I would say… Android developers are very open and very willing to share. And I feel that it’s a perfect time to get into the community, because there are so many conferences, so many meetups and talks around the world, and also available online, where you could take advantage of it. And I don’t know if there’s that exact same sense of sharing and openness in the iOS community. So I think, you know, for me, even after, you know, everything I’ve been through, I’d still choose Android again, you know?

**Saron:** Yeah, that environment—that supportive environment is absolutely crucial when you’re—when you’re really doing *anything* for the first time.

**Annyce:** Right.

**Saron:** I’m wondering… As an Android developer, do you hate iOS?

**Annyce:** No!

**Saron:** That is good!

**Annyce:** I don’t. Actually, among my list of podcasts that I listen to, one of them is strictly an iOS podcast. And the reason for it is that there’s so much overlap between being an iOS developer and being an Android developer. Because ultimately we’re all mobile developers. So I love to take bits and pieces from both sides of the spectrum to push myself to be a better *mobile* developer. And I have actually coded in Objective C. So I do have some vague familiarity with, you know, iOS development, and it has its own set of frustrations. It’s not like, you know, iOS developers just walk on clouds every day. They have their own challenges that they have to deal with. So, hate them? Definitely not.

**Saron:** That’s good, because that’s one thing that, you know, I see sometimes on Twitter between different coding languages and, you know, people saying—people who are Ruby developers, like, y’know, hating other languages or other languages—everyone apparently hates on JavaScript. {*Annyce laughs.*} But that’s just so—it’s so unproductive. You know, I think that every language has its benefits and, y’know, its pros and cons, and at the end of the day we’re all trying to make good products for other people. And, you know, understanding the woes and the pros and the cons and all that I think is a much more balanced view and a more productive way than just, you know, throwing darts at other languages.

**Annyce:** Right. Yeah, I agree.

**Saron:** So, one thing that you’ve done that’s a little new—a recent development in your life—is that you’re working with O’Reilly.

**Annyce:** Yes. So, um, even more recent I’ll say is I started conference speaking, and I actually had the opportunity to be connected with someone at O’Reilly who was interested in one of my talks on developing maintainable applications. And so from that sprung this opportunity to create a short video course where I walk users through the fundamentals, and making sure that they produce a quality Android application.

**Saron:** Wow. So I didn’t know that was a thing that happened at conferences. So, that is amazing.

**Annyce:** Yeah, conference speaking—wow, that’s—I mean, it’s been really great for me, I’ll say. Like, I guess one little-known fact is I took a year off of working full-time as a developer in order to get a sort of speedy teaching certificate, and I taught computer science to middle school students.

**Saron:** Really?

**Annyce:** Yeah. And, you know, for me that was great, because I absolutely love teaching and *attempting* to explain complex concepts in a way that’s really accessible to others. And, so, conference speaking is sort of the way I get to combine my love of coding with my desire to teach. So it’s something that I’ve really been enjoying, and I hope, you know, to be able to continue it for, you know, the foreseeable future.

**Saron:** Teaching can be very hard. You know, it’s a lot of work to get outside of your own head and outside of your knowledge and, you know, your comfort zone, and to understand someone else’s perspective and explain it at their level, and then somehow get them to where you are. Right? You’re starting at their point, and you’re taking them on this journey. What do you get from teaching?

**Annyce:** So, the biggest thing for me, anyway, for teaching someone else is you get to see the satisfaction across their face when they have that “aha” moment. And you know what it was like for yourself when something finally clicked. And it could be anything, like the time—whenever you finally understood sine versus cosine. You know, whatever it is. When you had that “aha” moment, it just sort of made everything else better from that point on. And getting to give that to someone else—that’s amazing. And when you’re just, like, head down coding all day, you don’t really get to do that; you don’t get to experience that. And so when you get out there and you try to share your knowledge with others, yes, they may be benefiting, but it’s really benefiting you, because you get to have that sense of satisfaction, knowing that you’re helping others.

**Saron:** When you see these middle schoolers—and, y’know, in a way, your audience when you’re speaking—when you see them trying to understand your concepts and try to, you know, hopefully one day get to your level of understanding and expertise, what have you found to be tools, processes that they use, that have helped them get that knowledge and really understand it better?

**Annyce:** I think one thing that’s really useful is trying to make the material relatable. So, for instance, you know, if you just go up there and you’re kind of just like showing a bunch of code, and it’s like, “Yes, this is how it works.” You know, “Just do some code like this and then you’ll be successful.” That’s not very relatable for people, especially not if they’re new to that particular concept or that particular way of doing it. So I try to approach it from the perspective, “Well, here’s the problem. And it’s a problem that no doubt we’ve all experienced. And look at how this particular, you know, concept or algorithm can help address that problem. And now let’s look at a little bit of code that shows how it can be done.” So, I try to make the code the sort of afterthought and moreso focus on the problem and *then* the solution.

**Saron:** So I know that you have a computer science degree. And I know that a big topic in our community is figuring out, you know, if I want to be a developer, if I want to do Android work at WaPo, you know, do I need to do that, right? Do I need to go back to school and get a master’s or, y’know, switch degrees. How has having a computer science degree—how has that impacted your coding journey.

**Annyce:** Hm. So, I’ll say for me, just speaking as a minority, I think it’s important because it opens doors. And that perhaps if someone saw my résumé and the education *didn’t* have it listed—the fact that, you know, I have this degree—maybe they just would have skipped me and passed on. But I think maybe that’s just because of *my* background. So, essentially what I’m saying is I don’t feel like it’s a necessity to be an amazing developer. But I do think that unfortunately, in this society that we live in, there are more obstacles to success for minorities.

**Saron:** So one thing that I’ve heard that I think is related to what you’re saying is a computer science degree can be a great way to *start* the career, right? To get that first job.

**Annyce:** Right.

**Saron:** But hopefully, you know, once you have that and you’ve worked for a couple of years, your work and your experience, and then the letters of recommendation you get from your peers and your boss, like, all that kind of trumps having that one degree. Is that—has that been the way it’s been like for you?

**Annyce:** Yeah, definitely. I mean, I don’t think anyone even really *notices* at this point that I have a degree. It’s more, so, you know, “Hey, so what have you been doing?” You know, “Tell us about this project. I see you’ve worked here. What was it like?” So, even when *I* interview people, I’m not so focused on, you know, what they’ve done in their educational career. It’s more, so, like, “Well, show me a project you’ve worked on. Show me an app on your phone that you’ve written.” You know, so, that’s kind of how I approach it. But like I said, I’d—you know, everyone is different.

**Saron:** And do you feel like at the Washington Post, you know, not being Google or, you know, Microsoft or a very hardcore tech giant corporation, do you feel like places like that are a little bit more lenient about CS degrees and those kinds of traditional expectations for jobs?

**Annyce:** Yeah, I think so. I think that we’re moreso looking for a good fit. We want someone who’s excited about new technology. It’s always great when you see someone who is able to communicate well, maybe through their own personal blog, and they also have, you know, sample applications to back it up. Those things to me are much more exciting than, you know, kind of talking about someone’s degree.

**Saron:** So, when I was looking at your LinkedIn, I saw that before Washington Post, you worked at NASA—which just sounds *so* badass—and then Lockheed Martin. And then you went to Washington Post. I’m wondering about the—what it was like to work at those really hard-core impressive, you know, science institutions. And then what it was like to work for y’know, a newspaper?

**Annyce:** Hm. That’s a good question. So, working at NASA surprisingly was very laid back.

**Saron:** Really?

**Annyce:** I was actually working in the mechanical engineering department at the time. And it was really a great experience for me. That was my first, you know, real internship, in, like, my senior year in high school, and I was able to, like, carry that through into college. And so it was just great to see, you know, engineers doing what they do day in and day out and see how much code has a real impact on tangible things like, y’know, telescopes and spaceships and things like that. So that was a great experience for me. As far as Lockheed Martin is concerned, that was definitely a much more structured environment. And there I was even working with some government things. So, for my personality, I feel that the Washington Post is just much better for me, as far as the approach that we take to coding by, you know, having agile and scrum. And things move a lot faster, and that’s better for how I am, versus, you know, a standard project with the government. You may be, you know, coding something for a year or two before it ever even gets released. So I definitely prefer the more fast-paced environment that I get, you know, being at the Post.

**Saron:** So, next let’s do some fill-in-the-blanks. Are you ready?

**Annyce:** Sure.

**Saron:** Number one. Worst advice I’ve ever received is…?

**Annyce:** So, good things come to those who wait?

**Saron:** Ha ha! Love that.

**Annyce:** This is something that I constantly told myself, until I realized that in reality good things come to those who *take.*

**Saron:** Mm hm. Yes.

**Annyce:** So, whether that’s, like, taking a chance, taking a leap of faith, taking a risk, … Just sitting and working so hard with my head down for the past decade, it’s only *now* starting to pay off, because I’m pushing *myself* to take more chances and to be more vocal and visible.

**Saron:** Number two. My first coding project was about…?

**Annyce:** So, my first *memorable* coding project was a Visual Basic program that exported telescope calibration data into an Excel spreadsheet. And I was really proud of this one, because at that time I was just an intern at NASA. And initially it was extremely intimidating for me to be part of such a renowned institution.

**Saron:** Right!

**Annyce:** But I had an *amazing* mentor, and he really helped me to have confidence in my abilities. And I feel that his confidence in me was a huge part of my desire to continue pursuing, you know, my career in programming.

**Saron:** So, I know that mentorship is something that we talk about a lot in the community. When you say that you had a mentor, what did that relationship look like? What did they do that was so helpful to you?

**Annyce:** So, at that time, I would have weekly check-ins with him. We would talk about my goals, what I learned over the past week; he would recommend books to me that I should read; and then he would also entrust me with these, you know, small projects. So, you know, transferring some calibration data into Excel, that wasn’t huge; he could have probably done it himself in, like, an hour. But it’s a project that he gave to me, and it helped me learn the fundamentals of programming and understanding, you know, conditionals and checks and integrating multiple applications. So, I mean, I think a mentor, to me, does more than just, you know, say, like, “Good job!” You know. “Hey, keep it going.” They take actionable steps. And I feel like that’s what was done for me.

**Saron:** That’s wonderful. Oh, it’s so good that you had that. That’s great. So, for the mentor that you had, was that your manager? Or how did you find that person?

**Annyce:** So, one thing about my high school, I went to a science and technology high school. And—

**Saron:** Wait, which one did you go to?

**Annyce:** Eleanor Roosevelt?

**Saron:** Okay, no, I was gonna—I was gonna say I thought you went to, um—I think it was Blair that had—I was in the CAP program? But Blair also had a computer science program, too.

**Annyce:** Yes, it was like the sister program at Roosevelt. And so part of that is you do an internship your senior year, if you desire, and then they also assign you a mentor. And so my mentor was also my manager there at NASA. And so that was great for me and really taught me the importance of mentorship and, um…Yeah.

**Saron:** Good for you. That’s amazing.

Number three. One thing I wish I knew when I first started to code is…?

**Annyce:** So, one thing I wish I knew was that I didn’t have to do it all by myself. In college I’ll say there was definitely this every-man-for-himself type of thinking in place. So I feel that I basically carried that with me, and I tried to grow and learn every single thing on my own. But I’ve seen that when you collaborate with your peers and you work on building your network, that you actually grow exponentially faster. So that’s definitely one thing I wish I knew when I first started.

**Saron:** I love that. And I think that’s why community is *so* important. Because when you do it alone, it’s *hard*, and it’s lonely. And, you know, when it’s frustrating and things don’t work, you know, you don’t really have anyone. So, yes, sharing and working together is definitely the way to go.

So! Let’s do some shout outs. Do you have a couple for us?

**Annyce:** Yes! So, the first one is *not* programming related. But it’s a book called _The Platinum Rule_, by Tony Alessandra and Michael O’Connor. And basically it’s a great book that exposes the four business personality types. And it sort of helps you to understand what type of person you are when it comes to business, and the best way that you can interact with the other three types. So I really, really love that book.

**Saron:** Interesting. Wait—which type are you?

**Annyce:** I’m a Thinker. Surprise surprise, right?

**Saron:** That sounds like a good one. Is that one of the better ones? Are there, like, bad types to be?

**Annyce:** No, and that’s the best part of the book. It helps you to see the strengths and weaknesses of each type. So instead of looking at someone who may have a sort of direct-er personality, where they’re very matter of fact, you just look at the strengths of that person and see how you as a Thinker can better interact with them based on their strengths and your strengths. So it’s really a great read.

**Saron:** Very cool. What else you got?

**Annyce:** The next one is a podcast. I’m a podcast addict. And so for people who are really interested in getting more into Android, I wanted to recommend the Fragmented Podcast, with Donn Felker and Kaushik Gopal. It’s a weekly podcast where they share Android development tips, they talk about the latest libraries, and they also interview some of the people in the Android community.

And along the same lines is a YouTube channel, Android Dialogs, with Chiu-Ki and Huyen, who both interview developers in the Android community, and they share little tips and tricks that they do at their jobs. It’s very short, but it’s really useful.

**Saron:** And you were one of the people they interviewed.

**Annyce:** Yes!

**Saron:** I saw that. I saw that video.

**Annyce:** Good catch!

And then the final thing is for—if you wanna get into conference speaking, there is a e-newsletter called Tech Speak Digest with Cate Huston and Chiu-Ki Chan, and it’s really catered toward trying to get more women into conference speaking in the tech space. And it’s awesome because they share, like, tips and tricks of presenting talks and writing your proposals, but they also include links to conferences that are looking for speakers that have a code of conduct, which is amazing.

**Saron:** Wow. Those are some great resources. Thank you so much!

**Annyce:** No problem.

**Saron:** So I have a couple sponsor shout-outs to start. Digital Ocean’s offering the CodeNewbie community a chance to try their cloud hosting service. Use the promo code “CodeNewbie” and get a $10 credit to get your app up and running. They’ve got easy one-click solutions for Rails, Django, and much more, so give it a try and let me know what you think.

Linode’s giving you a chance to try their powerful servers built for all your infrastructure needs. Just go to linode.com/codenewbie, and if you use the promo code “codenewbie10” before December 31, 2015, you can get $10 off, so give it a try.

So I’ve got three Android-inspired shout-outs I’m really excited to share. So one is the Android developer training guide. So when I was looking at developer.android.com, they had really good resources and really great starter projects and, you know, how to get started and what are the things you should know, and all this really, really rich, really great documentation, rich tutorials, lots of great articles. And so if you are curious and thinking about learning Android, that is definitely a place to start.

Another one is a collection of these tutorials for first-time app developers. And it’s by Sitepoint, and it’s called “The 12 Best Android Tutorials for First-Time App Developers.” And they have a nice list there of different types of tutorials and starter projects and lots of really good stuff to help you get started if you’re interested.

And the last is actually from the Washington Post. So, to me one of the things that I saw that made me go, “Oh, yeah, Washington Post is a digital company” is when I saw the 2014 Year in Graphics that was put out—I think—I guess it was the end of 2014, and it shows all of the really incredible, really beautiful storytelling that the Washington Post had done throughout the year of different events that have happened and different, you know, breaking news pieces and different stories. And it was all data visualization and, you know, interactive storytelling, and it’s absolutely beautiful. And I’m really excited to see the 2015 version of that. So if you’re looking for good examples of the awesome stuff the Washington Post does on the digital side, that’s one thing that you should definitely check it out.

So if you want to join the conversation, you can join us on CodeNewbie Discourse, our online forum for people excited about code. Or you can chat with us every week on the CodeNewbie Twitter chat; just search for hashtag #codenewbie and tweet with us every Wednesday evening at 9 PM Eastern time. You can learn more about that as well as show notes on this episode at codenewbie.org/podcast. If there’s a topic you want to hear about or a guest you wanna hear from, send us an email: hello@codenewbie.org.
Thank you again, Annyce, so much for joining us. Wanna say bye?

**Annyce:** Bye, everybody. Thanks for having me.

**Saron:** Thanks for listening. See you next week.