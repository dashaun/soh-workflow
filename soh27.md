**Dan Vega:** Good morning, good afternoon, good evening, and welcome to another episode of Spring Office Hours. I'm your host, Dan Vega alongside me as always my good friend, DaShaun Carter. DaShaun, how are you doing? I'm good. How are you? Like it's cold in Minnesota. It's very cold in Cleveland. I, it's cold. Tweeted out earlier.

I'm glad I still have the Intel based MacBook as a laptop heater. Yep. Ah, it does heat you up very well, , and I'm wearing my ViewConf Florida shirt to remember the good old Florida Sun. Very good. I also tweeted out, Hey, I'm not above. If you wanna send me free swag, I will wear it on the show, so I'm not above that.

**DaShaun Carter:** We can be bought. Hello. Hello. Welcome to this 

**Dan Vega:** show. Cool. Hello. Hello. I would say I haven't seen you in a while, but I have. I saw you last week, Chris. Yes. . 

**DaShaun Carter:** It feels like just yesterday. Greg's in the house. 

**Dan Vega:** Wonderful. Yeah. We're gonna talk about last week we're gonna get into Spring One Essentials. This was the online experience in place of the SpringOne event that unfortunately had to get canceled in December.

But last week was awesome. Spring one essentials was awesome. There was so much, there were so many announcements, there's so many great presentations. It was great to be back around people again in an office with a color coordinated bookshelf and games . So yeah, it was really great to be in San Francisco and we'll talk through that today.

**DaShaun Carter:** It was great. It was definitely an event with thousands of attendees. I still feel some of the momentum from last week online. Lots of great questions, lots of great content was delivered. And yeah, it was. . It was refreshing. It. I felt like I got upgraded during Spring. One Essentials last 

**Dan Vega:** week for sure.

All right. As always, please get your questions in. Doesn't have to be related to Spring One Essentials. Ask your questions, we'll see if we can't answer them. We did a lot of that last week. Anytime, I think anytime we're around people, we get questions thrown at us, which is good.

It builds builds up our vast knowledge of different customers and different questions we get asked. So please get those questions in. We'll see if we can't get 'em answered. 

**DaShaun Carter:** And it's your questions. It's that feedback. Your questions are what help us understand, hey, maybe we're not documenting something right.

Maybe we're missing something. , we need the feedback. So your questions help us understand where our community is and how we can help. We are advocates. We want to advocate for you. 

**Dan Vega:** Exactly. So what I'm gonna do is share my screen. We're gonna go through a whole bunch of stuff. Before 

**DaShaun Carter:** you do that, I wanna do one quick thing.

Yeah. I did send out stickers. I'm sending stickers out. Oh, nice. All over the world. If you would like a spring office hours sticker, all you've gotta do is email us stickers at spring, office hours.io. Awesome. Stickers. And send me your, I need your address. We're in the US so it might take a while for some of you, but send us your full address.

That's it. That's all you have to do. Email us stickers at spring. Office hours, io with your address and we will send you stickers. So I've sent out some stickers, so expect them soon. For those of you that have asked, 

**Dan Vega:** We do got a question. Maybe we can jump on that before we get into some of today's items, 

**DaShaun Carter:** what's the best way to upgrade to the latest version of Spring Cloud?

Spring Boot? Do you wanna 

**Dan Vega:** start? Yeah, so I don't know about Spring Cloud. I don't have any specifics on that. I can talk more about Spring Boot. There is a really good migration guide. I think we should probably have this on hand to just keep throwing up cause we get this asked a lot. But there is a Spring Boot three migration guide.

We'll see if we can't get that added to the show notes. And this walks you through all the things that you wanna look out for as you upgrade two Spring Boot. 3.0. The biggest thing is maybe not trying to jump from say two or two, one or two, four, all the way to three. Try and get yourself up to 2.7 and on Java 17.

Make sure you're good there. Then make the move to 3.0 and baseline at Java 17 and Jakarta e nine and 10 and all of the good stuff there. There are also some suggestions if you're using like security in your application. There are changes in Spring Security six that have a lot of features, not a lot a few features that have been deprecated, so you wanna make those changes as well.

Again, that migration guides the best place to start cuz it has a whole document of these are the things you need to look out for. As far as Spring Cloud, I don't know the answer to that. So Spring Cloud is such a big portfolio of things, right? It just depends what you're using and what you're trying to upgrade to.

I don't think, I don't know of anything off the top of my head that would stand out to me going, oh, make sure you look out for that. So 

**DaShaun Carter:** I have seen many examples of what this community is doing, migrating on blog posts. So lots of examples. Maybe I should add those to the show notes where community members have said, I was upgrading from this version to this.

Here's the steps that I took. Here's what I ran into. So there's lots of evidence out on the blogs, out in the internet for what people have done. So I can tell that a lot of people are excited about this migration to Spring Boot three. Yep. 

**Dan Vega:** Cool. All right. No other questions. I'm gonna share my screen here.

I have a very important announcement to make today is our good friend Josh Long's birthday. So he gets birthday balloons. 

**DaShaun Carter:** Happy birthday. Happy 

**Dan Vega:** birthday. So happy birthday to Josh. I don't think Josh really needs an introduction. He is our friend. He is our coworker. He is the longest standing spring developer advocate in the world.

That, that is the title I think. So Josh's birthday, so if you get a chance, go out on Twitter. Wish him a happy birthday. He also, I won't say this is a new one cuz there was videos from a few years ago. He has resurrected this YouTube channel and he is doing some focus on this. So if you want to go ahead and subscribe to this channel, coffee and Software with Josh Long.

He, by the way, did not ask me to plug this. I am plugging this on my own cuz it's his birthday. This is your birthday present, Josh. And it's 

**DaShaun Carter:** going to be good content for 

**Dan Vega:** sure. Absolutely. So that's Josh Happy birthday, another calendar. I don't know why Josh Long's birthday is not on the release calendar, but it should be.

So one thing we like to do is take a look at the release calendar. If you don't know about it, calendar.spring.io kind of keeps you up to date with everything that's going on in the spring ecosystem, not just Spring framework and Spring Boot, all of the other projects. And there are a lot, there's a lot to keep up with.

So this is a really good place to. So today is Tuesday, the 31st. Not much happening this week. So STS four 17 two release. We weren't here last week. A couple things got released last week as well. Integration for aws, spring Cloud Stream Binder, aws. And then the previous week was on Tuesday the 17th.

We were here. Spring Boot 3.02 did get released on that 19th there. So that is the latest version. If you go over to start spring.io, whole bunch of fixes and patches are in there. That pulls in that spring framework 6.0 0.4. So really great place to go ahead and start if you want to keep up with what's happening in the spring ecosystem.

We 

**DaShaun Carter:** have another question out here. Is spring moli for monolithic or can I apply it to microservices? , how do you feel about that one? 

**Dan Vega:** I don't, I'm not very familiar with the project. Okay. I'll jump on it then. I know who's behind it and I know the general premise of it, but 

**DaShaun Carter:** so the idea is a longstanding argument like, Hey, do I need microservices if I'm starting today?

And I know what my app should look like, and maybe it's just me. I'm the only one doing development let's call it an experiment. I shouldn't make a bunch of projects. I shouldn't have multiple repositories. It'll be faster if I put things into one repository. I keep all of my thoughts together.

What the spring moth is going to do is it puts in place some guardrails so that when it is time to split that out, you're adding members to your team. It's time to split that out into microservices and get the value of being able to release things separately on that path to production. , it puts in place those guardrails to make it so that you can pull apart your mono or, yeah, monolith.

You can split that out easily into microservices at some later date. And that's the main thing. So it prevents you from doing calls across packages where it'll make it difficult. You'll limit the interdependencies, it'll li limit the coupling between those services, those moist modules.

**Dan Vega:** Cool. I think, something else to remember on that subject too is as far as distributed architectures go, it's become synonymous with microservices, and microservices are just a type of distributed architecture. There. There are many other patterns and ways to accomplish a distributed architecture that aren't microservices.

One example I hear a lot of people say is I don't want a database per service. And okay, that's fine. You don't need one. Like there, there are ways to distribute your application without having separate databases for each one. Now microservices have become very popular because they do solve a real problem and there are ways to solve that problem, but, , there are other solutions too.

So take a look at those. Do some reading on distributed architecture in general. Let us know. 

**DaShaun Carter:** Yeah. Use hashtag spring office hours on your social spring office hours. Let us know how are, what does your deployment look like big or small. We want to hear it all. Let us know what it looks like in your neck of the woods.

**Dan Vega:** Absolutely. All right. We have a lot to get to, so I think I'll just keep moving along here. I have a new newsletter that came out Monday, really just talking about Spring one Essentials. I don't know why this is so big, but it is big. But I thought I would share it because there are some pictures in here.

If you weren't in San Francisco again, DaShaun and I were in San Francisco last week. We were at the VMware offices in San Fran. This is not the headquarters. The headquarters are in Palo Alto, but there's a really awesome office in San Francisco, and so we got a chance to hang out there for a little bit.

So there's the front desk I talked about the Spring one Essentials. We're gonna go through some of this stuff today. When we got there early on Tuesday morning, the balloons were being delivered. So DaShaun and I carried up the balloons and that was a lot of fun. So DaShaun, quick witting. Snap this picture.

And he, if you can't tell from pictures , because the first time I met DaShaun I was like, wow, you are a tall person. DaShaun's a big, tall guy and he's able to stick his arms out 20 feet in front of you and get a good wide picture there. So thanks for the quick witty picture taken there, Deshawn.

Cuz that one was awesome. Absolutely. This was a snack bar that we had in the office for that day, for the day of the spring one essentials. And look at that. I'm just like, wow, I wish that was back here. Can you talk about the green these green things over here? Yeah. Those ones. Do you still have these in your possession?

**DaShaun Carter:** here's, you warned me. So there were some leftovers. They were in a bag. I was walking out. I was like, man, those are, And I took the bag. I took the bag, I took the whole bag. He's not lying. No. Whole bag of leftovers. I took it to my hotel and I ate too 

**Dan Vega:** much . I said, DaShaun, you may not wanna take those.

That's gonna hurt. 

**DaShaun Carter:** It did it, it messed me up real bad. , I just couldn't stop eating 'em. They were so delicious and they were spring colors, so it was great. 

**Dan Vega:** Yeah, it was great. I had a little, I had a few gummy bears and these chocolates, so that was awesome. I also here's the bookshelf from the office.

I love a good color coordinated bookshelf. It just makes my OCD happy, really happy. And 

**DaShaun Carter:** That picture. , yeah. Open the door to some other awesome conversations. 

**Dan Vega:** Yeah. Yeah. , just randomly tw tweeted something out and some people in the office were like, oh, we didn't know you guys were here and we got to talk to some folks in the office.

So that was really cool. I think that's all I want to talk about there. Cool. So a little bit more into Spring One Essentials. So some things were announced one of the things was the New Spring Academy. So there's a blog post. I'll go ahead and see if we can get this added to the show notes, or you can head over to tansu.vmware.com.

On the blog, and this just talks through what the Spring Academy is, there is a website, spring.academy. Learn from experts, build like a boss. . Love that. So this is an on-demand education developed and curated by the world's foremost experts in Spring. And I don't think you can think of anyone who knows spring as much as this guy right here.

You can see him right on the front page. Real wor real world training from the best in the community. So this is a chance to go through here. There is a free account, so you can create your own free account if you want. You get on DA on demand access to spring training. You get to go through some like real world projects.

There's also a pro account. I do not get a commission on this, but if you want to throw our name in, please do spring Academy Pro for 2 99 a year. The important thing to note here is that you get a spring certified professional exam voucher. And for those of you who have done the spring certification in the past, , our prob your eyes are probably lighting up right now.

Cause this used to cost a lot more to go through. I don't know the particulars on what it cost. I remember they were pretty high, but to go through and get trained and get a certification was a lot more than 2 99. So this is a huge bargain. You get the certification, exam, voucher, and all of the lessons and pro courses.

So definitely worth checking out. I've seen a lot of the curriculum for at least two of the courses. Really great content here. And just hats off to the entire team behind putting Spring Academy together. Anything you 

**DaShaun Carter:** wanna, a couple questions? Nope. I signed up for Spring Academy. I'm always trying to learn.

It looks like a great resource. There's tons of content available for free. ? I have not started yet, I'll be honest. Because last week I admitted I hadn't used all of the new. Features in Spring Data Redis. So I spent a lot of time since last week working with that. But as soon as I'm done wrapping up this project, I'm going to jump feet first into Nice Spring Academy.

There's a couple of questions wanna hear from. Dan says, I really Spring Boot Statistics slash Grafana Labs. Can you talk open telemetry? This keeps on coming up during our show, the spring actuator. The Spring boot actuator was a big deal for me and my career. Having those metrics available, having insight into what's really happening inside of my application, made a big difference in my career.

and I get it like this is going to continue to move forward. Dan, we have talked about this quite a few times on the show. We've had Jonathan on the show, you might want to go and check out his episode on tansu TV or spring office hours.io. You'll get to the same place. Go check out that episode.

But I definitely think this is one of those topics that we could literally talk about it every week. It should probably be a part of every single one of our demos. So yeah, thank you. Stay tuned. We'll have more around Spring Boot Grafana and Open Telemetry real soon. 

**Dan Vega:** Yeah, I would say I do have a little bit of an observation demo in my Spring Boot three.

What's new in Spring Blue three tutorial that's on YouTube, so you can check that out. There are chapters so you don't have to watch the whole thing if you don't want to. So jump into that again, the. Changes in Spring framework six and Spring Boot three around observability are really just the beginning.

This is a story that's going to continue as we keep progressing with the spring framework, but it's already there and there are ways to collect a lot of metrics right out of the box and use something like Grafana to, create your dashboards and collect that information. Yeah, I agree.

We need more we need more tutorials and information about it. Cause right now, Just the docs are there, there's not a lot of other examples of I, as as a learner I need to be told why first, so why do I care about this stuff? And what are some practical examples of when I should be using this?

So I think that's where we could contribute. 

**DaShaun Carter:** All right. I had a couple more. Dan Vega loved your videos on Spring Security. I love new revamp and your videos helped me understand quite 

**Dan Vega:** a lot. Awesome. Thanks James. Appreciate that. Oh, 

**DaShaun Carter:** thank you for that feedback. Also a newbie question. It's a great question.

Is it possible to deploy Spring Boot app locally on my local machine for my own use to not pay for services like Heroku or other paid services? Yes, and I highly recommend you start on your laptop. That is not a new question. It's one of the big values of Seren Boot is it gives you all that, all the middle you need everything that you need to run your application on your laptop, and that's where you should start, is on your laptop.

**Dan Vega:** or what about a raspberry pie? I know you have, or a raspberry pie? 1 2, 

**DaShaun Carter:** 490 92 92 raspberry pies. I'm debating. I have a bunch of raspberry pie zeros. The first version that do not run 64 bit. So I can't deploy Spring Boot native to those. So I think I'm actually gonna give away. It's about 25 of them these first version of the Raspberry Pie Zero and zero w and yeah.

And I've also, I've, I heard through the grapevine that the team over at gra vm our friends over at GRA VM have announced that they have support for risk v. Native image support for risk V, which is just another architecture in that, in my head, that same bucket for my raspberry pies. I can go out and buy these $50, $30 single board computers and I can deploy.

potentially Spring boot. Spring native. I haven't done it yet. , but I have some in the mail on the way. And I'm excited to explore that real soon as well. Like how easy is it and how exciting is it that I have these little devices that can put all over? Yeah. And yeah. And I can deploy Spring Boot, my favorite framer.

I can deploy it to these little 

**Dan Vega:** devices. Yeah. When we were in San Francisco, we went to a computer shop next to the San, next to the VMware offices. . Sean was like, you got any resumes or pods? You got any ? Yep. Because he was ready to get 'em all. . 

**DaShaun Carter:** I'll be honest I've got some that are unopened.

I think I have three more still that are unopened. And I was I was gonna wait and do something special on a stream or something. 

**Dan Vega:** But yeah. That's awesome. I've got some let me know when you do that, cuz I'd love to check that out because I'm one of those people who bought one of those books on.

Things to do with the raspberry pie and never bought a raspberry pie and never tinkered with it. And it's been one of those things on my long list of things I'd like to do. So I'm gonna tell 

**DaShaun Carter:** you a little secret. , one of the abstracts that I've put together I'm really excited to present, Ooh, is Hot dog or not hot dog with Spring Boot.

**Dan Vega:** I saw the title for that abstract cuz you sent it to me yesterday. I honestly didn't have a chance to read the description, but I feel like I need to read the description now because I'm not quite sure whether that's going. 

**DaShaun Carter:** Image recognition, pure job or, oh, 

**Dan Vega:** I that I've, yeah, I'll talk about it.

Valley I've watched Silicon Valley, so I got you. 

**DaShaun Carter:** But the example, that target architecture, that target implementation is well-suited and. Validated on a raspberry pie. Zero two w a $15 computer is gonna be able to run hotdog or not hotdog. It's not a hot dog. . 

**Dan Vega:** That was great. Okay, cool.

Let me go back here. 

**DaShaun Carter:** So I appreciate you being here. Thank you for joining us again. 

**Dan Vega:** Awesome. So we talked about Spring Academy. The next, actually I'm gonna bring up this first. So the golden path to spring one. So again, spring one essentials. Spring one was essentials, was the replacement for spring one.

That was gonna happen in December. There were a lot more sessions that were gonna take place in December than what we are able to get to on the spring. One Essentials virtual conference. And I see we're streaming here. So what we did is we reached out to a lot of those speakers and said, Hey, we are creating this golden path to spring one.

We want to go ahead and highlight your talk that you was accepted, that we were going to highlight in San Francisco. We'd love for you to come on and do that for us. So we did that. So we created this golden path to spring one. Every single Tuesday and Thursday, there's gonna be a new talk.

You can go ahead and check out. We have some, we had one today that already took place. We have again, every Tuesday and Thursday, and as you start to go down this list, you'll see some really amazing speakers. Our friend Thomas Vitali, Matt Rabel, Marco Aaron and Dan Oleg. Just so many great speakers, so many different talks that I'm really interested in checking out myself.

And you and I are actually going to be hosts of some of these shows. So somebody from, more will host the, each of these episode and then speaker will go in to their presentation. Yeah, I'm excited about this. This is really great to see. Every Tuesday and Thursday, 2:00 PM Eastern. Check this page out.

To get a list of all of those shows. 

**DaShaun Carter:** Thursday, I'm hosting my first one on Thursday. Nice. It takes two to Salsa . 

**Dan Vega:** I love that. It's gonna be awesome. That title I saw. It's gonna be awesome. I love it. I saw that title. All right. Can you think of anything else that you want to talk about when it comes to Spring One Essentials?

Besides what I have on screen here? No, it's just 

**DaShaun Carter:** the golden path. It's really from now all the way up until spring one, we're gonna have content that is new from the best of the best out in the community. They're bringing it to share. It was just, there's so much, there's so much good stuff happening in our community that yeah we couldn't not share it.

So I'm excited to see how this works out. It's gonna be amazing. Me too. Every week upgraded. 

**Dan Vega:** Cool. Why am I not seeing, oh, there we're, Cool. All right. So another thing that we announced was the state of Spring 2022. This is the third year I believe we've done this. This is a survey that we go out and survey spring developers and it gives us, gives you a chance to share your experiences with us.

This year's survey explored important trends while focusing on areas for intent for potential improvements. So we get feedback from the community, we want to hear from them. We want to hear from you and take that feedback and helps drive, the next generations of spring framework. So what I thought we'd do is you can go get this yourself.

You can just put in your email address and you can get this. But what we're gonna do is just go through this and see if anything sticks out to us, see if anything is interesting and maybe have a little discussion around it. Sound good? 

**DaShaun Carter:** That sounds like a great idea. Simon definitely watched the Spring one Essentials.

He's filling us in with some of the announcements around GemFire and also Rabbit mq. I'm a big fan of Tap, tap one four got announced. The Rabbit MQ as a service got announced. Lots of really interesting stuff and I also enjoyed the actual customer presentations as well. A lot of really good 

**Dan Vega:** content.

Yeah. I'll point out in my newsletter here, there is a link. Our colleague Rita has a really good roundup here. I don't know why I didn't show this before, but basically if you want to get a roundup of all the announcements that happened, like the GemFire, like Rabbit MQ as a service, which is really great.

This particular blog post on the tan vmware.com blog is really good and puts all of those things into one.

State of Spring 2022. Let's go through this. So the introduction just goes through what it is. It's divided into four sections, modern architecture's, new tech, gaining ground upgrade and flourish and springing up to speed. There's some information about just an overview of what this report has included.

There's some demographics so from a region standpoint. Our 2022 survey reached a total of 1500 qualified individuals, wide range of roles, regions, and jobs. So we see half of it, almost half was from Europe. That's really great to see. Years of spring boot experience more than five years of experience dominated this survey.

And then all kinds of, here are the demographics for the survey. So here's what we can get to modern architectures in full flower. The shift to modern architectures and APIs continues with technologies like Open api, graph, qls, gaining momentum. That's great to see. So using mostly modern architectures in 2021 was close to or 50%.

We see that shifting a little bit even more. So that trend is only going to continue to climb, I think. 

**DaShaun Carter:** I wonder why it's not going faster. I do get to hear customers and I do get to hear things not just from the spring developers, but also from operations and I think everybody understands where things are headed.

Yeah, I think everybody's, not everybody, I think a lot of us have seen the value of. Things like Kubernetes, things like multi-cloud and I think that it's finally starting to loosen up. So just a feeling that I've got at the beginning of the year is that this is definitely true and I think it, the adoption curve here is going to increase quite a bit in 2023.

I'm excited 

**Dan Vega:** this year. It doesn't really surprise me that it's moving at this pace because I've worked in enough fortune 100 companies to know that it just, it takes a village to move things in larger companies. It is what it is. But yeah, it's nice to see that number going up. That's a good sign.

Oh, so we talked about modular monoliths. Mono monoliths was a question that we added to an architectural style for 2022. The idea of a monolithic modular system has regained popularity, so as we can see here microservices are continuing to dominate up. In the upper right hand corner here, you can see the legend.

The darker green is 2021. Lighter green is 2022. So pretty much stay the same. Microservice gets talked about a lot. Modular monoliths. A lot of people are starting to talk about that. Reactive, staying the same serverless we can see has jumped up. So a nice 5% increase there in serverless, which I'm a big fan of, glad to see that is catching mo momentum and especially in the Java space.

Java and Spring, right? Java's never been like, Hey, this is the first choice for serverless workloads or scale to zero. And with all the different technologies that are coming out around it some of the different platforms, it's making serverless a really great choice. Not only in the Java space but in the spring space.

So 

**DaShaun Carter:** yeah, I feel like the conversation around serverless is gonna change a little. Yeah. When up until recently when I heard. Serverless, I thought of Lambdas and functions. I thought of definitely the scale to zero aspect. However, with Spring Boot three and what we're able to do and what we've, I think we've shown it here in Spring Ops hours.

I can deliver a lot of those things without the Lambda part. I can deliver my applications, my NBC apps, my eventing apps. I can deliver those things still as scale to zero, even though they don't check the Lambda function box. So I think that there's maybe some opportunity for that serverless. Definition to evolve.

**Dan Vega:** . 

Yeah. And there are just some exciting things happening in the community. One of the things I've touched on before is AWS Lambda Snap Start, which, you know, one of the drawbacks to using kind of Java on a servers function is the cold start time, the time it takes to start up the execution environment, the run time, everything.

They have made improvements on the a w s side there. So that's great to see and. Spring, spring cloud function is really great. It's, if you haven't had a chance to play with it, you can write your serverless functions using the Spring Pro programming paradigm that you're used to. And they're platform agnostic.

So I if your if one of these functions are going to AW s and maybe you have other workloads that are on Google Cloud or Azure you can export 'em that way as well. So check out Spring Cloud function if you haven't had a chance to play with that yet. We haven't 

**DaShaun Carter:** done that in a while. I was doing that at the beginning of 2022, quite a bit.

This, hey, let me take a function, the spring cloud function running on Azure, running on aws, running gcp, running on Key Native. It, maybe it's time to circle and bring that one back. I think that'd be a good idea. 

**Dan Vega:** Yeah, that'd be great. I have a ton of stuff around, a ton of con, a ton of content around serverless in Spring and in Java in general.

Yeah, that'd be fun. Cool. Let's talk about the use cases of spring. So APIs remain the top spring use case. So being able to expose APIs remained at the dominant use case in 2022. Exposing APIs to internal com. Customers, our consumers has been steady growth since this survey began. So if we look over to the right exposing APIs to internal customers, we can see that has continued to rise and now at 86%.

So that is a lot of what people are doing. And I know, my previous position, that is exactly what we're doing. Tons and tons of services throughout an organization and they each gotta talk to each other and they would talk to each other via rest or event driven architecture. So pretty good to see.

Also GraphQL down there, getting a little low, 24%. I'm a big fan of GraphQL, so nice to see that on the rise. And based on the attendance at some of my talks lately and the questions I've been getting about it, I think that number's only gonna rise. So I'm excited for GraphQL in 2023. I'm 

**DaShaun Carter:** happy to see soap still on there.

I was just thinking the other day, , that idea of, Hey, I've released this API and this is exactly how you consume it and you can generate your client from this. It's like there's a lot of power there. So I don't want to dismiss that. I'm happy to see that it's still hanging around because there's still a lot of value in those types of services.

**Dan Vega:** Again, I would not want to write a client that has to talk to soap, but if it just works out of the box, and as I said earlier, I know lots of companies who just. It takes a little bit of time to move forward, so it's still super 

**DaShaun Carter:** powerful. I'm pretty sure that we can still generate soap based apps out of our spring initializer, although I haven't 

**Dan Vega:** in a while.

So I, the web service stuff Greg works on and I'm pretty sure is the lead for some of that web service stuff. So I think that 

**DaShaun Carter:** might be worth cracking open again because. I'm just saying. Yeah, that's good stuff. 

**Dan Vega:** All right. 

**DaShaun Carter:** Oh, look at there. Look at there. I know it's an outdated topic, but it would be great if you guys can cover calling soap services with Spring Boot.

What's the best way to do it, et cetera. Like we're speaking the same language. I am so happy to hear that. I have somebody else. There's another question. Hey Dan, how do you feel about Kelo? Is that a good idea? Kelo? 

**Dan Vega:** It's been a while since I've used Kelo, probably a good five years, so I don't know that I'm the best person to answer that question.

If it's still being actively maintained and it's still being used, yes, it's a great idea. There's also another product you can use from the Spring team. There is a spring authorization server, which just hit 1.0. So that's something else that you could look at as well. I'm pretty 

**DaShaun Carter:** sure you can use 'em together as well.

Yeah, stay tuned. I am. I'm gonna be pulling in Kelo into another effort. So yeah, stay tuned. We'll have 

**Dan Vega:** some fun. Are you familiar with where Kelo is right now? Is that still being, it 

**DaShaun Carter:** is still being maintained? It is still talked about a lot. Just my perception from the community. So yeah.

Yeah, I think it's still a safe bet. Cool. Also, hey, this one, a good one. J p Native Query not working with gal vm. Please fix it. I would love to see what you've got. We can help send us a link, send us some information, give us a guest and let's see what we can do to help. 

**Dan Vega:** Yeah. I wonder what's not working with that.

Should be pretty easy to check out. But yeah, I'm interested in, 

**DaShaun Carter:** I know that it's not like completely broken. I think this is gonna be one of those edge cases because Yeah, I think we've demonstrated the JP native query working with Colm. So we're happy. How 

**Dan Vega:** cool. All right. I'm gonna go on.

Spring projects fruitful for developers. An important goal of the spring team is to deliver modern apps quickly. Almost half of the stakeholders reported that they will be using more spring modules in the coming years. An increase in eight points for 2022. The top three spring projects remain spring security, spring data, and spring web nbc.

So not surprising there. Those are the three reach for all the. Spring web security and data. Notable gainers spring, Kafka, spring batch, and spring web flu. So cool. Yeah, 

**DaShaun Carter:** that is cool. Another question, red shock. Where should I put my API calls? Logic? Is it service layer or 

**Dan Vega:** something else?

Yeah it, I, as always, it depends what logic is, what logic are you talking about? If I'm talking to a database and we have like a data tier, that could be in a repository. I write a lot of applications where I don't need a service layer and I'm just talking to a repository that talks to a database.

I know so many people create examples out there, or have examples of like complicated architectures where you have interfaces and services and that delegates to a repos. It doesn't need to be that complicated. If I'm talking to a database, I use a repository. If I have business logic that pertains to that application, then it would be, yeah, service layer, it works great.

That's exactly what that's for. How you split up that business logic and where in the service layer, what level it's in depends on what it is. And then, it may delegate to some other project for some business logic, but yeah, service layer is a good place to start. 

**DaShaun Carter:** I think that one of the things that we've learned and we've heard multiple times here, is that it depends on how you're testing.

A lot of times, don't forget about how you want to split up your application in order to have it properly tested and get that coverage. So there's more than just Hey, where should it be? Which pattern should it follow? The what matters more with those patterns that we're following is how you're testing them, right?

We can throw it all into one box and that's okay, but when you split it out, you can test things individually and if you're into testing, you should check out code. Another show on Tzu tv. Mario Gray has been doing a lot of really interesting stuff over there. 

**Dan Vega:** Check. . Yeah that's a great point.

I was just gonna, as soon as I got done talking, I thought about that as well. So I'm not a I'm not against T d, I just don't do T D a lot. I end up writing tests for code that I've already written, which again, is, I know sacrilege to some people, but that's just how, that's how I get down, , but, One thing that I do love about testing is it usually points out problems with my code.

So I always, I like to get something to work first. Like it doesn't need to be this beautiful architecture architected code for it to work. I like to solve the problem first. Let me get it working. Okay. I think I have what I think is a viable solution. I'm gonna write some tests for this cause as soon as I start writing tests that usually, like there, there start to be code smells in my test that go, oh, maybe I shouldn't, this is, this one service class is doing way too much.

That's a code smell for me that, we're violating the single responsibility principle. That is not, there's too much going on there. So when I start to write tests, it gives me an idea of, okay, maybe I could refactor this a different way. So get it to work first. Then, if, however you write your tests your tests can usually lead to some of those answers.

One of 

**DaShaun Carter:** the things that I found in my career is that if I'm grabbing, there's a bug and I'm looking at somebody else's code, I always do t d first. Hey, Dan you've given me this ticket and there's an issue in the member service. And the issue is this. The first thing that I do is create a test that validates that bug.

Then I start working on the fix, and I know that it's fixed when that test goes green. 

**Dan Vega:** And then you ask the original developer, why wasn't there a test for this scenario? ? 

**DaShaun Carter:** Yes. I wasn't gonna go there. I was saying that pattern of I've been there. I don't write tests all the time. Sure. But I'll also say pairing with Mario.

While he's doing the t d makes it easier. So I've done a few sessions with Mario and then when I go and I'm doing my own thing, I've, I found myself writing tests first. I find myself making these changes on my new projects. I'm automatically including the spring rest doc. I'm automatically including test containers because I've found these patterns that are just so valuable.

That I can't imagine not putting it in right away because I know I'm gonna do it and I know it speeds me up and gives me more confidence. 

**Dan Vega:** Yep. That's a really good point. I know a lot of times, I'm sure everybody has done this. At one point you may be writing some code during a block of code.

You may write some comment there that says to do let's validate that this particular use case works. So instead of writing that comment in the code, just go write a test for that right away. Let it fail. That's fine. But you have your documentation for later that says, oh yeah, I need to go ahead and check for that use case.

Now I can write a test to make sure that use case passes. 

**DaShaun Carter:** Thank you. Another question, do you have an alternative for aca actor with Native Spring Boot? 

**Dan Vega:** I don't know what ACA is. 

**DaShaun Carter:** I have a lot of this conversation. I've had a lot of this conversation in the past but I think I need more information to understand your use case.

The ACA actor pattern can be used in a lot of places, and yes, we have ways of doing that with Spring, but yeah, tell us more. Tell us more. Good questions. Bring your questions. Remember if you leave here and you still have questions, answer that's on you bring your questions, we'll get to 'em. If we don't get to 'em during the show, we're gonna make sure that we at least see them so we can get to 'em offline, and then we'll share them as content.

**Dan Vega:** All right. New tech gaining ground. The Spring team keeps a close eye on upcoming up and coming innovations. More than 54% of surveyed this year, like the fact that new modules are consistently being added to keep up to date with the latest technology. So that's really great to see. Project Loom and GRA VM jump to the top of the New Tech People plan to use each selected by 30 risk 30.

So GRA VM Loom, project Loom, those are two big things that everyone is very interested in. We talked about both of those last week in San Francisco that's really exciting that this is exactly what people are looking for. So we'll keep talking about that. We, I talked a little bit more about Loom last week.

We'll hopefully get to some more of that as the year goes on. And as we march towards Spring framework 6.1, hopefully Loom will be out of preview in the next version of whatever. I don't, it's hard to keep up with versions of Job now, . The next one's 20, so I think 21. It may go out of preview, so we'll see.

But yeah, good to see that. 

**DaShaun Carter:** I have a question. Welcome to the show. What do I have to watch out when I go? Production productive with a Spring Boot application in a Docker container. What do I have to look out for? Not a whole lot. If you use the Maven Spring Boot plugin, you're getting the best of the best.

You're getting the best practices from the rest of the community. We've been doing this for a while. The whole built pack story is just moved into that plugin. So yeah, I highly recommend checking out the Maven Spring Boot plugin, which is gonna use theto built packs outta the box. And then you've got all the support and all of the that expertise bundled right into your containers.

**Dan Vega:** Yep. When it comes to containers, we have a simple rule around here at spring office hours, and that is friends. Don't let friends write Docker. 

**DaShaun Carter:** They just don't do it. , don't let your friends write their own Docker files. Yep. Yeah. Another question. Resource server and OAuth client. How do we use these in microservices?

It's so easy. It's so easy. It's easy. I want to show I would crack open my IDE and show that right now. But I want to finish going through this and what I'm gonna do is I'm gonna say, Hey, let's, next time let's show this off. Or in an upcoming show, we gotta show this off. We gotta do a few more demos.

But in the meantime, I'm pretty sure Dan's got. a good example on his website, on his YouTube of this exact same thing. 

**Dan Vega:** Yeah. I don't know. So when you say the term in microservices, like what are you trying to do? Because if you're trying to have a bunch of different clients authenticate with one thing, right?

That's where we're gonna start talking about spring authorization server. So you have one central place where all the authentication is done. You don't wanna rewrite that logic X number of times, right? And each of those clients register with that authorization server. So the microservice one, microservice two and three all say, Hey, I'm someone who's going to authenticate with you authorization server.

And so that's how that happens. So I would say if you haven't had a chance to check out the documentation on that, start there with spring authorization server. That should get you up and running pretty quickly. Yes.

**DaShaun Carter:** Let's see why you don't care about explaining Spring of VC with template engine like Time Leaf. Is it still useful? That is a great question. I was actually on Twitch last night with somebody in Korea, right? I assume they were in Korea. They, it was I was using Korean to do the translation, but they were still using time Leaf.

Time Leaf is still amazing. It's still very widely used. It's still super powerful. So yeah, if that's what, if you are running into something, if there's something that you'd like to see around time Leaf around what you're doing with time before, you'd like to see some of the patterns that we see out in the community, let us know.

Happy to share more on Time Leaf. It is super powerful. I'll be honest, lately I'm clicking the V button. I click the V button and I have a lot of it taken care of for me. But. Time Leaf is where I've been for the last seven years, I think is, it's been my default and it's only recently switched to Vaden.

**Dan Vega:** Yeah. So I think it really depends on what type of applications you're trying to build, right? So a lot of the demos I build are API driven, so whether I'm using REST or GraphQL, I'm not really using a front end or a templating engine on the Springside. Those APIs are developed in Spring Boot.

They're consumed via other clients. So those clients could be a mobile application in iOS or Android. They could be a front end application written in JavaScripts. So they're, I think another thing that gives weight to this is just the rise in popularity of the different frameworks out there.

Whether it's react, angular views, felt, and insert any framework here. , those are really great to use these days. And so that, that is usually what I reach for. So if I have an API in Spring Boot, I may develop a front end and something like View that talks to that api. So nothing wrong with using Time Leaf.

I think that just teams already doing front end development may not have developers on staff who use time leave. They may have front end engineers that work in these different component-based libraries. And it's like, all right, let's build our front ends separate so that we can deploy them separately.

Because again, that's one of those trade-offs itself. Hey, I want to constantly deploy my front end without having to restart my backend. . So really it just depends what you're building. Nothing wrong with time Leaf, but in the world that we live in today as you saw from the State of the Spring survey, most people are using Spring Boot to build APIs, and that APIs is being consumed by some other client.

**DaShaun Carter:** I definitely have I think I have some example repositories. One of the patterns I like to do with time leaf is I like to take a bootstrap theme and just grab that bootstrap theme. And then I'm using Time Leaf to fill in the blanks. And that is a super fast, super powerful way of getting that reactive.

Is that what they call it on the front end? 

**Dan Vega:** The 

**DaShaun Carter:** interactive, the resizable, all the good stuff. Yeah. I don't know the word I'm thinking of, but yeah, that's a pattern that I've used quite a bit. So don't be afraid to use time leaf. Don't be afraid to grab it. It'll work. What's a best practice around Docker files?

We, we said it already. Don't write your own Docker file. Don't write your own Docker file. Use Mavens Spring Boot Build image every time. every time in that, not just for Spring. Find a bill pack. Don't write your own Docker files. I'm not saying that's just for Java. I'm saying that across the board.

Don't write dockerfiles, don't do it. Don't let your friends do it. use a bill pack. 

**Dan Vega:** You have, your time is valuable. You could be doing much better things with your time than writing, build pack or, but writing Dr. Foz, . 

**DaShaun Carter:** No. Hey, this is it. Don't apologize. Yeah. We're here for you. We are at your service for if one person shows up to the show or if a thousand people show up the show.

We are here at your service. That is, yeah. That's the whole goal of this show. As much as I like to learn from Dan we're both here to support you, the community. And if we don't have the answers, we've got Slack. We know how to get it. Yep. Why? Spring remains less efficient than Corcus can see.

Spring greater? I'm not sure. I believe that. But again, we could take a look with Spring Framework six and Spring Boot three. I don't think that this can be said anymore, and I would love to educate you on this. There's, but there's a lot. It really depends on the use case, et cetera, but it's worth exploring.

It's worth exploring for sure. I don't think that there, this is the case anymore though. More questions. Thank you. James Hayes. What bill packs do you recommend? What do I recommend? I recommend Uhto jumping into Thatto ecosystem. They have a ton and the people there are great. The community around there is great.

I'm actively trying. Support and upstream some of the work I've done around build Pack into Theo Ecosystem as well. So that's where my heart's at. Do you have any others, 

**Dan Vega:** Dan? No, that's Itto. 

**DaShaun Carter:** Fix our socket streams. I don't understand. I need more information. That doesn't help me. I know that there's a few issues open.

Tell me which one that you're interested in. Go add information that you have around those issues in GitHub and let us know. Cuz we are also doing a lot of exploring. And Mario, my good friend, Mario Gray, also has a lot of great content around using our streams. Not just for, message driven, event driven things, but combining functions and that function to function combin.

To get really interesting outputs with native images using our saga streams. Let us know what else 

**Dan Vega:** you'd like. You know what, we have been saying it, but we need to get Mario on the show to talk to us about. He's 

**DaShaun Carter:** a busy person. We have. He is. I get it. I might have to just show up at his house and make it happen.

**Dan Vega:** We were in San Francisco last week. We probably could have done that. He was in Nebraska. Oh, that's right. . We went to San Francisco. He was in Omaha. Yeah. 

**DaShaun Carter:** Can you explain test containers? Why should I use test containers? I would love to explain test containers. Thursday test containers live.

You should check that out. I'm gonna be there. I'm gonna walk through using test containers Whispering boot. In more than one way. How do you use test containers As part of your regular integration? Yes. How to use test containers to validate and test your native images. The idea is that the implementation of the database we've.

I've done in the past a lot of things to where, hey, I want to validate that my persistent here works. Some of the things I've done is maybe I've used H two or an in-memory database during my unit test, and then I switch to some other version of a database down the road that can cause problems.

So the idea with test containers is you can use the exact same implementation, the exact same API for your unit tests that you might use in production. And what it does is it simply pulls up a docker image, it deploys a docker image from scratch or you can initialize it and you can run your test against the actual database that you're gonna be running in production.

That's an example. 

**Dan Vega:** Yeah. And it runs it extremely fast, which I think is what blew me away because I'm like I don't, do I really wanna be spinning up a Docker container and then executing these tests runs really fast, or I wouldn't have, I wouldn't have used it. So that, I think that was really impressive to me.

**DaShaun Carter:** Is Java now Jakarta, 

**Dan Vega:** Java EE is now Jakarta ee. So big difference. Java EE stood stands for enterprise adi enterprise Edition, I think. Yeah, I think I just did a video on this, so I should know that. But Java EE Enterprise Edition was really for building enterprise applications in Java. That was stagnant for a while.

Oracle governed Java EE had ownership of it was stagnant for a while. The eclipse come foundation came along and said, Hey, we'd really like to take ownership of that project. We'd like to evolve some of the APIs in that project. Oracle said, great. You can do it with one requirement.

You need to rename all of the packages from Java. Something to Jakarta or to anything. But they ended up with Jakarta. So that is, that's of great questions. So good answer. Spring Boot three and spring framework six. Now use Jakarta EE nine and 10. So yes, if you are updating from Spring Boot 2.7 to Spring Boot three, you need to rename those packages.

Your IE can do it for you until J has a nice little feature that says, Hey, rename of the Java EE packages to Jakarta E. So not a huge change for you. But as framework, for the framework itself, it was a pretty big change. We had a lot to go through to get that to work, but it's nice now we are on the newer versions of Jakarta and we get to see an evolution of those APIs as we move forward.

So 

**DaShaun Carter:** how do I know how many users at once can my basic Spring API application handle before another container created? That's a great question. That is a great question that can be answered by using the actuator. By making your code observable, you can expose and you can see and you can watch in real time what's happening.

You've gotta understand your application on, you have a chance to learn before it goes to production, how your application is gonna behave. And with this approach you can figure that out. Every application is different. My hello World app could probably support 10,000 users in the single container because I've compiled it natively.

If your application is making thousands of blocking calls to multiple backends, it's going to behave different. So it really depends on an app to app basis, but that's why we've provided the observability and the spring actuator so you can get real-time insights into what's happening with your Spring Boot app.

Why can't our socket be a little simpler to put in place, be like website? I'm not sure what you're running into, and I really want to know more. So I'm gonna ask you to reach out, DM me on Twitter or on LinkedIn directly. I wanna work with you to figure out what's going on because I'm a big fan of our socket.

I think it's a great little protocol and I want you to be excited about it as well. James says, for testing, I borrowed the strategy used by laville of having factories for entities. That's a great idea. That's an absolute great idea. Oops. Let's see here. How do you generate docker file, if not manually?

Spring Boot build image. You don't need the docker file. Use the bill pack. The bill pack has all the guts inside of it. You can have multiple versions and it's configurable so you're not just taking a simple Docker file maybe for one build. You want to attach an agent for AppDynamics or For other you can do that all within a consistent guardrail that's got support from the community.

So don't write a Docker file. If you see a Docker file in your repository, do not touch it. Somebody else created it. Somebody else has gotta maintain it. Don't touch it. Don't use the Docker file. Don't let your friends use a Docker file. Use buildpacks. How does TTO compare to using Buildpacks on Cloud Foundry?

Are they compatible? That is a great question. The Cloud Ry Buildpacks are not compatible with the Cloud native Buildpacks, but the idea that. The architecture, the idea is the same, is that you're letting some platform build the images that are actually going to be ran on your platform in your Kubernetes or in your Docker or wherever the Theo Build packs can be used inside of Cloud Foundry.

They can be deployed as docker images. They can be used on Kubernetes. They can be used on Docker. They can be used standalone. But that's not the case for the Cloud Foundry Build packs, theto Cloud native build packs are the evolution of this build pack pattern. And it is a it comes from a joint venture of the team over at Heroku and Pivotal Tansu, formally Pivotal where they're taking the standard and they made it available so that we could have this concept of bill packs that could run anywhere, or the images that could run anywhere.

Let's see. Spring now uses Jakarta Imports. Yep. Yep. How can you please explain about New Observability API with micrometer? How is it different from just using locks? Oh, there is so much, Oren. I'm gonna point you just cuz we're running outta time. I'm gonna point you to episode it, was it 14 with Jonathan Ivanov?

You gotta go watch that episode of Spring Office Hours. But then you come back we've had a couple questions earlier in today's show around observability. We have some stuff to show you, but I want you to watch that episode first and then come back and join us. 

**Dan Vega:** Yeah, and I think, so again, just at a high level, observability is not just logs, right?

It's about metrics logging and distributed tracing. So at least those three things fit into that observability bucket. And each one of those answers a question a different way, right? Like, how and why, those types of things. So check out that episode. There's some great information in there. All right.

**DaShaun Carter:** Thank you. I use Loom, excuse me, with Spring Booth three native on production for a small project, and it works great. I saved 60% of resources. I'm so happy. That is amazing. That is amazing. I would love to hear more if you could share any of it that would be wonderful. We want to hear your story, let us know what's going on so that we can tell the world how, what's a good path.

It might not be the best path, but this is the path that we can go forward and it's working for you. I think everybody in here if you go to your boss or your wife and you said, Hey, I'm saving a 60%. I'm saving 6%, I think you're gonna pat on the back. So yeah that's let everybody 

**Dan Vega:** do that.

And so yeah, if you're running, workloads on something like Spring, NBC Loom is gonna, luma's gonna be pretty big. So we're looking forward. Awesome. 

**DaShaun Carter:** Do you know if I can test Java virtual threads on Cloud Foundry using Cloud Foundry built backs, or do I need to create my own docker image? That is a really good question around, so yeah, the virtual Let's 

**Dan Vega:** thread.

Yeah. Let's unpack that because there's a lot of things in there. So let's back up to just virtual threads, right? Virtual threads is what we've been talking about with Project Loom. They are new in Java 19, they are preview, so this isn't even a release yet. This is still a preview feature. So to enable it, you have to do the dash enabled dash preview you're running your application.

So with that said, there is a blog post on the spring io blog that you can read through of how you can use virtual threads in a spring booth three project. And so again, if you are using something like spring NBC and you are doing blocking operations, I'm calling out to a database. I'm calling out to read a file, doing some input, output, anything that is blocking.

Project loom and virtual threads are going to help you out a lot. We saw 60% of the number thrown around, and it's going to help out a lot in those particular use cases. The suggestion here is I think someone said they were running a small project on it. Go test this out. This is a preview. This is not final yet.

Take a sample up that you have, go ahead and run it on a server somewhere in preview mode for a small subset of traffic and test it out. But in those kind of scenarios for those type of workloads, it's going to be awesome. Now, on Cloud Foundry using Built, you know those I, I don't know, question.

That's a whole nother stack on top of that. But if we just bring it back to virtual threads, spring Boot three in a spring NBC app, yes, you are going to see performance improvements there. 

**DaShaun Carter:** Yeah, so you, you've got options. If that build pack a Java 19 build back is available for Cloud Foundry, then you could probably go forward with it.

Otherwise, you have another option of doing the dock image. I'll be honest, I haven't taken a Java 19 compatible build pack to Cloud Foundry. So I'm putting it on my list. Come back, join us next week, come back and I will have an answer for you and maybe even a demo. Ooh, Alexander says, Hey DaShaun.

Sorry for fam. No worries. I've missed you on Twitter. Regarding specific soap use case that I have to integrate with a legacy service. Let's go. We're gonna, we're gonna connect, we're gonna do this. Let's go. Thank you for asking it. It'd be my pleasure to sit down and work with you on something like that.

Now that you've mentioned Time Leaf, is it better to have translation? Oh, I think you mean like language translation in Time Leaf with its files or in the front end. See you with Beautify. Do you have any opinions on that? Cause I do. 

**Dan Vega:** I don't I would probably put it on the backend, but because, oh, so now I guess I do have an opinion, so I'd probably put it on the backend because what if you have a second client that starts talking to it?

Now you have it all centralized in one place. That translation happens there instead of on the client. Yep. 

**DaShaun Carter:** Also the translations I've done that in the past. The idea of, Hey, I'm, I need to translate this into maybe 47 different languages. That process needs to happen somewhere so that the backend process, the way that I can ingest that into time lease as those translation, those different locale versions of the properties that I'm gonna be translating, that is a simple process.

I know that process. So I know what that path to production looks like. So I have no reason to disrupt that versus having those translations. Cuz then if, in order to do that on the front end, I've gotta send all the translation data to every client. You can't do a translation if they don't have the data, or they're gonna have to make calls for that translation to the backend, which again, you could do it on the backend.

So I have strong opinion about that. I would much rather it be done on the backend for those reasons. Hey, sleep that burns. You stumbled upon this. this is we try to do this weekly. We might even be doing it more than weekly in the future, but yes, this is a regular show. Today is episode 27. Follow us on VMware Tan, on tansu tv, spring office hours.io.

That will forward you, okay. Yeah you'll get to where you need to go. Spring office hours.io. James, thanks. We're happy that you're here. Thanks for joining everybody. Thanks for joining. 

**Dan Vega:** Yeah. If you have any more questions, get 'em in. I think what we'll do is we'll save the second half of that state of spring survey.

We can always touch on that. There's so much cool stuff to talk about there. Yes, for sure. Cool. 

**DaShaun Carter:** Hashtag spring office hours on your places. We are paying attention. I'm writing bots. I will share those two like we are writing. We want to help you out as much as possible. You don't have to wait and bring your questions here.

We have a spring community on Twitter. We have the Getter community. We have Stack Overflow. We're where you are. We're in those places. We're on LinkedIn. We're in the u, the LinkedIn group. We are in those places where you are hashtag spring office hours. Let us know. Otherwise bring your questions here.

We're happy to help. 

**Dan Vega:** Cool. I see. One more question. Let me just pull that up. Can I still use sleuth or should I migrate to micrometer? So yeah, if you're in Spring Boot three, as you're moving forward, you're gonna wanna move to micrometer. If you're doing distributed chasing, you had to bring in Spring Cloud sleuth before.

You don't have to do that in Springwood three. So one last dependency just kinda rolled up into that same api, so I would move to that. 

**DaShaun Carter:** Definitely move to Spring Boot three. 

**Dan Vega:** Thank you. Appreciate you. Thank you guys. Always a pleasure. Pleasure is ours. Thank you guys. Thanks James. Thanks for answering all my 

**DaShaun Carter:** questions and I can go next.

Josh, appreciate this one. Love it. Thank you for sharing. 

**Dan Vega:** Yep. Is the certification in spring worth it? So worth the effort. So I think that's really a question you need to ask yourself. Certifications in general, are they worth it? Is it something that your work is requiring? If it is, then obviously it's worth it.

If it's something that you're seeing out in the job market as you're looking for a new job and you see it a lot, then it becomes worth it. 

**DaShaun Carter:** And where are you? If you're Dan doesn't need a certificate. I can use one. I'm thinking about maybe I should invest and go ahead and go on that path because.

I would like to know more. Yes. So I think it's an individual basis. But that's something for you. I definitely think it's worth it for some people so 

**Dan Vega:** that that would that actually brings up something else. So I think if it's going to drive you to learn more then I think it's well worth it.

So why do we read books? Why do we take courses? Because we wanna learn from someone else. We want an incentive to learn as well. If I don't have a book in front of me I really, how am I gonna learn? I need something to drive me to, learn a particular subject. So if you're using something like Spring Academy, there's courses that's going to give you motivation to go through those courses.

Learn more about spring. We can all. Learn more about a particular subject. So you get to learn more about spring and the end goal is, hey, you get certified. Whether that certification does anything for you later, I don't think is the end all question, right? It's the process of getting there.

The, we, DaShaun and I run a lot. We may run a race later this year. We may run a half marathon or something like that. The half marathon is great. It's a huge goal, but getting there is really what it's all about all the time that it takes like months of preparation, getting all of those runs in those practices in that's what it's really about, right?

The end goal of getting, going through a half marathon, that's fun, but everything leading up to it is really what it's about. So I would say yes. Long, long answer, short, yes, because you're gonna learn something new and you're gonna feel proud about yourself that you got through it. 

**DaShaun Carter:** James, I have never used GraphQL or the pointers when to use Graph QOL versus rest.

James, I'm gonna go ahead and say it because Dan won't go check out Dan's YouTube videos. His talks around spring for GraphQL have been the most popular topic in 2022. Of all the work that we've done and all the conferences I've been to, , that conversation, that topic has been the most popular one.

**Dan Vega:** Thanks. I appreciate that. Yeah, so I think from a when to use it, yeah, I mean it's a technology like others that you always have to say, when should I be using this? I do have some talks on it. Real short of it is, if you have a bunch of different clients talking to one particular api and when I say clients, hey, we have a bunch of mobile apps here and we have a bunch of different, maybe micro front ends over here.

We have an IOTT application over here. All these clients talking to a single rests a api, right? You start to your rest API to meet all of those client needs. So I, instead of just crud, methods that are returning a list of. Widgets. Right now I'm writing all these different methods to format the data the exact way that each of these specific clients are asking for it.

If you get into that business that's not great because now you have all these different methods out there. More code means more maintenance. Right now you're writing code and you're introducing new bugs. The best bug free code that you have in your system is the code that you don't write.

I, I think from that standpoint, if you have a lot of clients requesting information in a different way grapho makes a lot of sense because you have just a single endpoint and you're putting that onus back on the client saying, Hey, you go ahead and tell me exactly what data you want, and I will retrieve it on the back end for you.

**DaShaun Carter:** This has been a great episode. Thank you everybody for joining. Yeah. I gonna say this, appreciate. Spring is coming. The journey spring is the destination. 

**Dan Vega:** Spring in Spring is coming. Spring is coming. It is February 1st. Tomorrow I'm, you can't tell you how excited I am. I look forward to March 17th, somewhere, what is it 19th?

Somewhere around there when the clocks move forward and it just stays light out longer. I cannot wait cuz that means I get to get outside and start running again. I hate running in cold road, . So yes, I'm excited. Spring is coming. Spring in, spring is coming. So thank you everybody. Everyone. Thank you.

Hopefully we'll be back next week on Tuesday, three 30 Eastern standard time, spring office hours. We'll see you there. Thanks again for joining us. Thanks everybody. 

**DaShaun Carter:** Bye.

