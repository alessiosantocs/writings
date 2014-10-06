# ThoughtsFlow
###### 6 Oct 2014
Yesterday's topic was basically financing and seed fund raising. I played with a tool to simulate equity distribution in a startup that is going through several rounds of investment. The key point there is that every round is linked to the next and with every round your share of the pie gets smaller (in percentage of course) because when money gets in there's dilution.

I also attended to a skype call with an experienced entrepreneur/vc from which I understood a good number of concepts:
1. Choose co-founders carefully when starting a business. Something that founders always do is get a co-founder quickly and possibly they think making someone a co-founder makes that person highly motivated. Don't do that! Co-founders are people you are going to have discussions with, they will have a say for the future of your company. Just be careful when chosing a co-founder (because probably you need one).
2. Founders tend to be extremely generous about giving a piece of the company to people just to get them motivated and do their best at their job. This is great, just don't do it too much. Shares are an important heritage in the long journey of a startup and you're probably not thinking about this now but the right thing to do is to raise a bar and give everyone who's worth a part of that bar (once a bar is set is fairly easy to give people what they deserve based on their motivation and commitment)
3. The most important thing is commitment. Do you want to hire some super star because of their past and quallity of their job? Don't do it. People are what drive business to success/failure. So not only try to hire people only when you really need them but also after a careful analysis. Before hiring you should at least give yourself an idea of the kind of values you're looking for in an employee. You write them down and use them to choose candidate to test. 

Yesterday was a good day. Today's monday and I'm gonna start working in half an hour.

###### 4 Oct 2014
As expected I am not able to write just everyday. I'll try to do my best anyway.

Yesterday was hacking night and we've focused on building levels for Magnetiq. We decided to build levels as soon as possible and then adjust them to make them fit into the main story.

The interesting things that happened last night was that we faced a serious UX problem we're still trying to solve. The thing is about gameplay and controls. We thought that a combo of touch tracking (for character movement) and acceleration to move into space would've been the best choice. Instead we found out that moving your finger around the screen is a painful way of moving things around. We're testing different inputs and combination and we're constantly thinking about how to improve the game's UX more.

Another challenge we're facing these days is the levels' difficulty problem. We need to find a standard measure to understand wether a level is too difficult/easy and find a way to insert training levels for inputs and commands we're introducing that someone may not be confortable with.

Things are getting very clear day after day and I think we're getting very close to release date.

###### 1 Oct 2014
Yesterday I was pretty busy building the level 0 of our nice game. The behind the scenes included a lot of work of automation and animation. Yes because our little P must float around the screen gently and almost as if he really wanted to.

That's why I needed to improve the base Animation class with some logics to better handle both complex and simple animations and extend it creating another animation class called MoveToAnimation. This nice prototype will take the point that has to be moved and the point[s] it needs to move to!

By default it accepts a track of points. The animation will be stopped only when all points have been reached and passed and it can be restarted automatically if the user specifies a tiny boolean that specifies so.

I am quite satisfied about the animation system. It's easy to use as a developer, it's built upon inheritance and it has strong scaling possibilities. Probably it's not the most powerful animation engine I've every seen, but I am sure that after this it will indeed contain a lot of core functionalities that will allow creating complex animations in a blink of an eye (or in a few lines of code :D).

Another interesting fact is, while working on the level 0 I started better understanding the story of our main character and - why not? - of our stars and universe. I started giving more attention to these details in the game because the end user will expect these to be as senseful as possible. We need to give our character a life to live in and the graphic representation of it will come out by itself.
###### 29 Sept 2014
It's monday and I spent the day working on the development plan for our brand new application here at Snaphealth.

I also passed a couple of hours watching/learning how a real graphic engine works. Watching the simplicity and at the same time the complexity of SpriteKit was a pleasure. I am now discovering a really good start point where to begin building ios games in 2d.

The evening is another match! Salvatore, my engineer friend, and I came together with some great ideas about levels in Magnetiq. We thought first to have a look at our solution of graphic engine and I think we'll be reviewing it a bit because of some illogical results we ended up during development. But I am trustful that we'll solve them easily.

What strikes us now are levels. We came up with 7 levels which are one more incredible than the previous. That's a great (in some way simple) start for Magnetiq which will be on the Play Store probably in 2 and a 1/2 weeks.

We're working really hard on the story of our main character as we believe it'll make a big impact on the game. We'll make it gain abilities and new powers and increase the awareness of the player that the universe is much much bigger than that little screen.

Our main concerns are basically related to the user interaction with the game and the development of some special features that are not present in the version we already built.

We'll begin soon breaking the laws of the physics and playing with mathematical functions which I will describe here further on!

###### 28 Sept 2014
These days I'm working on Magnetiq a simple html canvas game similar to Sinuous but better :)

We basically started rewriting it in coffee from the bones of the first only-javascript version. That version was incredibly raw and was a first try of building a custom 2d graphic engine.

Yes because I realized a few days ago that what we're basically doing is building a totally new and customized graphic engine.

It's not formed completely but yet it does have a:

- Custom animation engine
- A collision engine
- A simple but effective system to draw objects automatically into the canvas

I have to say that building this kind of system (as basic as it is) was quite straight-forward. In one long night and some bites of days was done.

The thing that strikes me now is the Levels manager. The need is to easily create levels and make them work seamlessly into the scene of the game. We managed to find a way to do that in a simple way but there's a long road ahead of us and we're just getting started.
