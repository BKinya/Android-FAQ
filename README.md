# Android-FAQ
Frequently Asked Android Questions

## Introduction. 
Hey Awesome Devs. Thank you for stopping by. This is a collection of frequently asked Android questions. Most of them are not Android specific. They can apply to software developers using other tracks.

These are responses by other amazing Android Developers and from various sources. You do not have to follow everything here to the letter. We all have different experiences. Use the responses as a guideline to figure out what works for you. 

Cheers! 🥂

### How do I get started in Android Development?
Android apps are developed using Kotlin, Java and/or C/C++. Android developers use Java or Kotlin to develop Android apps. C/C++ is used to write performance-based and hardware-based features. 

To get started in Android developemnt, you'd learn either Java or Kotlin. Check out [Should I learn Kotlin or Java?](#kotlin-or-java) section to learn more about about the two languages. 

Once you've mastered either of the languages, you are ready to learn Android developement. Check out [Build Your First Android App](https://developer.android.com/training/basics/firstapp) guide to get started. It includes a quick codelab, a deep dive course and other learning resources. 

### <a name = "getting-android-role"></a> How do I get my first Android Developer role?
- Have some well-documented projects on GitHub which has a Readme and at least one useful app on Playstore.
- Update your Linkedin profile with the projects you've worked on, relevant achievements,  volunteer experience, and any previous experiences like internships. 
- Keep your CV updated. You'd build one with LinkedIn Resume Builder
- Set your LinkedIn status to `Open to Network`. 
- Directly reach out to recruiters you know or have interacted with. 
- Check Companies career pages and job boards 

**Tips To increase your chances of landing a Job**
- Write about the technology you're looking to get a job in. In this, case Android. You'd write about an API you're recently learning about, a bug you solved etc. 
- Record a video tutorial showing how to do something in Android. 
- Contribute to open-source projects. Open-source projects give you an opportunity to learn practically,  practice your skills, and build your confidence.
- Build an app, while sharing the journey on social media. You'd write an article about the journey or record a video and post it on YouTube.
- Speak at local meet-ups and conferences.

Check out this podcast: [How to land a job, if you've been laid off or if you are just starting out](https://fragmentedpodcast.com/episodes/238)

### What factors played a role in improving your Android development skills?
- Working on projects: work projects,  open source projects, pet projects, side projects. Some of awesome Android open source projects: [Droidcon KE 2023 Android App](https://github.com/droidconKE/droidconKE2023Android), [UseHover/Stax](https://github.com/UseHover/Stax?s=08). 
- Reading other people's code. Check out [Android Dev Notes](https://twitter.com/androiddevnotes) on Twitter. They share great Android projects. 
- Reading Android and Kotlin documentation, as well as Android and Kotlin articles. 
- Reading Android and Kotlin books. 
- Writing Android articles, and recording Android video tutorials. One of the best ways to learn is by teaching others, the protégé effect. 

Check out [Awesome Android Learning Resources](https://github.com/androiddevnotes/awesome-android-learning-resources) put together by [Android Dev Notes](https://twitter.com/androiddevnotes)


### How'd I stay updated with the latest trends in the Android development ecosystem?
- Attending major conferences like Google I/O, Android Dev Summit, Kotlin Conf', Droidcon conferences across the world. Updates and new developemnt are announced during the conferences. 
- Follow top Android Developers on Twitter, and LinkedIn. 
- Attend developer meetups. Check out [Android254](https://twitter.com/254androiddevs), [Kotlin Kenya](https://twitter.com/kotlinkenya) if in Nairobi, Kenya
- Listen to Android Podcasts. Some of my favourites are  [Android Developers Backstage](http://adbackstage.libsyn.com), [Fragmented Podcast](https://fragmentedpodcast.com)
- Subscribe to Android newsletters: Android Weekly, Kotlin weekly, effective android. 
- Subscribe  to Android Youtube channels: [Android Developers](https://www.youtube.com/@AndroidDevelopers)
- Read Documentation.
- Try new APIs on your projects. You learn more by experimenting.

### What topics do should I learn before applying for my first Android job? 
For your first role, make sure you master the basics in Android. Some of the things to consider include:
- Working Kotlin Knowledge
- Layouts either using XML or Compose
- Navigation
- Android SDK and API version
- Storing data locally in an app
- Calling a rest API from an App
- Debugging

### What do Interviewers look for in An Android Dev?
  
- Technical strengths: Coding best practices, implementation of Android libraries, test cases coverage, version control(Github, Gitlab, Bitbucket) 
  
- Cultural fitness: Team collaboration, good communication, honest feedback, conflict resolution.

### Resources to learn Jetpack Compose

- [Jetpack Compose For Android Developers training resources](https://developer.android.com/courses/jetpack-compose/course), to get started with Jetpack Compose in Android. 
- [Practical Jetpack Compose, Joe Birch](https://practicaljetpackcompose.com) to learn how to build Android apps using Jetpack Compose
Compose projects
- [Jetpack Compose Internals, Jorge Castillo](https://jorgecastillo.dev/book/) to learn deeper compose topics and compose implementation under the hood. 
- [Jetpack Compose and internals cohort course, Jorge Castillo](https://jorgecastillo.dev/course/) 
- Check for [Jetpack Compose Newsletters](https://twitter.com/alexstyl/status/1662740985456263168?s=20) here. 

### Which Architecture should I use in my app?
There exist several architecture patterns: MVP, MVVM, MVI, Redux and much more. Architecture patterns are guidelines for building quality apps. They are not cut-on-stone rules. 

All best practices can be applied to any architecture pattern. 

Nonetheless, architecture patterns are different: how they are implemented, the learning curve etc.  

Before adopting an architecture into your app, make sure you first understand how it works. 

My two cents: 
For beginners, I'd recommend starting with MVVM. It has a gentle learning curve, adopted in several Android projects and has many resources online. 

For Jetpack Compose projects, I'd recommend an MVI kind of approach. This helps a lot with state handling. And you can implement MVI on top of MVVM. 

### Should I learn Compose or XML?
Jetpack Compose is the recommended modern UI toolkit for developing native Android UI. With Jetpack Compose, you build the UI faster with less code and using intuitive Kotlin APIs. 

Do you have to know XML to learn to compose? No. For beginners, you could get started with Compose straight away. But XML knowledge is good to have. XML is still dominant in legacy projects. Maintaining such projects requires one to know about XML. 

I'd advise learning both. You'd working on some projects using XML then jump to Compose. Knowledge about how Views/XML work will help you appreciate the progress in Android UI development and the benefits of using Jetpack Compose in developing UI.

### <a name = "kotlin-or-java"></a>Should I learn Java or Kotlin?
When Google announced the first version of their Android OS, in 2007, they adopted Java as the main language for Android development.

In 2016, JetBrains officially released Kotlin. At Google I/O 2019, Google announced Kotlin as the first-class language for Android development.

Some of the benefits that Kotlin brings to Android development include:
- Interoperability with Java. You can call Java code from Kotlin, and Kotlin code from Java 
- Safety. Kotlin gracefully handles common mistakes such as null pointer exceptions.
- Structured concurrency. Kotlin coroutines simplify background tasks such as network calls.
 
With Kotlin as the first-class language for Android development, new Android development tools and content such as Jetpack libraries and training content are designed in Kotlin. For instance, Jetpack Compose, compiler plugin support, and multiplatform projects. 

Therefore, if you're considering Android Development, I'd encourage learning Kotlin. 

Also, Kotlin is cross-platform. It can be used in Android development, server-side and Kotlin multi-platform. Check the docs for more: [Kotlin Docs](https://kotlinlang.org)

### What does an Android developer do on a normal basis?
Android developers design and develop apps for various Android devices: phones, tablets, smartwatches, TV, and cars. They debug and troubleshoot issues in the apps, maintain existing apps, create Android libraries and stay current with Android OS, android development updates. 

### What does an Android dev interview process entail, are there DSA or behavioral questions?
An Android interview process will vary from one company to another. But the most common parts you will encounter include: 
- CV/Resume screening. 
- The recruiter, hiring manager call. This is typically not technical but covers your experience. 
- Technical Screening. Different companies choose different screening approaches. Some of the options include: 
    - Time boxed code  challenge. This includes likes of Hackerrank or leet code challenges, evaluted by an Engineer or automatically. 
    - Technical screening call with an Android Engineer. Android concepts are asked. You mighty be asked to pair program with the engineer to write code for a small problem. 
    - Take home assignment
- On-site interview. This is usually the last stage. It varies from company to company. Some of the activities here include
    - Coding. If you were given a take home assignment you migty be asked to expand the project to test how you respond to requirement changes. Others may ask general data structures questions
    - Mobile system design questions. You are asked to design a mobile app. This mostly focuses on the app architecture. 
    - Behavioral or hiring manager interview

Check this article for more details: [Typical Hiring Pipeline](https://thetechresume.com/samples/the-hiring-pipeline.html#typical-hiring-pipeline)

Preparing for interviews makes all the difference difference. So prepare😃. 

### As a beginner, when do I know it's the right time for me to start applying for a job?
I do not think there is a specific time. You could start applying immediately after Campus, after completing a boot camp.

Nonetheless, prepare for the job search. Build apps to show what you are able to do. Have them on GitHub and/or publish them on Play Store. 

Write content, work on projects ... Check [how to get an Android Developer role](#getting-android-role) section for more tips.
 
### GDE Questions
Google Developer Experts is a global community of experienced developers who love to share their knowledge and passion with others.

Check out this [feature with Madona](https://twitter.com/AndroidDev/status/1666133599039500307?s=20) as she shares about her GDE journey. 

Check out the [docs](https://developers.google.com/community/experts) to learn about the community, who can join and the application process. 


### Technical Writing
Technical writing is writing about technology, any writing to provide technical information.

To get started, pick a topic in your area of specialization, for instance Android development, and write about it. It could be something new you learnt, how you fixed a bug, a guide how to a given API in your app among others. 

Check out this article:  [Technical Writing: How Do I Get Better at it](https://harunwangereka.medium.com/technical-writing-how-do-i-get-better-at-it-4af86aa49a38) by Harun Wangereka to learn how to get better at it. 

There is no one right way to structure your articles. But always ensure correctness in your articles. Your articles ought to be comprehensive. You mighty not be able to cover everything but try as much as possible to cover important parts of the topic you are writing about. And be concise. 

Great articles are organised for readers to easily follow through. You'd start with general to specific topics, or start from basic to advanced topics. You are telling a story with the article. 

### Mentorship and Communities
Mentorship is a learning relationship between an experienced person and someone who **wants to grow**. With a healthy mentoring relationship, both parties gain, not just the mentee. ~[Growing as a Mobile Engineer](https://www.mobileatscale.com/growing.html).

Mentees, do not ask, "Will you be my mentor?". If you ask, the answer is probably no. Shift your thinking from "If I get a mentor, I'll excel" to "If I excel, I will get a mentor". Mentorship relationships start with a mutual connection -- and mentors often select protégés based on their performance and potential. ~[Lean In For Graduates](https://www.amazon.com/Lean-Graduates-Chapters-Including-Negotiate/dp/0385353677)

Start working on something. Start learning,  working on a project, writing that article etc. You'll find many people willing to help you along the way. 

Reach out for help, when you need assistance. For instance, If you get stuck coz of a bug, reach out for help. There are many amazing developers in developer communities willing to help you. This is one of the ways to find mentors. 

And Join developer communities. To learn, to network. 

Check out: 
- [Android254](https://twitter.com/254androiddevs), [Kotlin Kenya](https://twitter.com/kotlinkenya), [Flutter Kenya](https://twitter.com/KenyaFlutterDev), if you are in Nairobi, Kenya
- [Droid Pwani](https://twitter.com/DroidPwani_KE), An Android Developer for the Coastal region in Kenya. 


### Imposter Syndrome
Imposter syndrome is real. It happens to the best of us.

Check the following articles to learn more about dealing with imposter syndrome:
- [What Is Programmer Imposter Syndrome and How Can You Deal With It? | Turing](https://www.turing.com/blog/programmer-imposter-syndrome-tips/)
- [What Is Programmer Imposter Syndrome and How To Overcome It | Codementor](https://www.codementor.io/blog/imposter-syndrome-deypemtirw)

## Contributors. 

