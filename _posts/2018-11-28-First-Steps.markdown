---
title: First Steps
layout: post
date: '2018-11-28 12:05:10'
categories: [game_dev, lua, love2D]
comments: true
---

<center><img alt="your classic copyright free image" style="border-radius:50%;"  src="http://www.picpedia.org/highway-signs/images/reasonable-doubt.jpg" width="200px" height="200px" /></center>
<br>
<p> When taking the first step into the game development world, a lot of questions came to mind. </p>
<blockquote>What language is the best? What engine? What are the component of a game?</blockquote>


<p>These question full forums and social groups all over the internet, and countless of good answer as being give in time, the problem is, rarely these answer are definitive to solve a single person problem.
</p>
<blockquote>I came, I saw, I regretted it</blockquote>
<p>
	There are countless of people that enter this world with the wrong foot and collect one failure after the other. Being one of those people I can now recognize the signs of the problem before it gets too late: 
	<ol>
		<li>Changing languages or engine before finishing a project.</li>
		<li>Embark in crazy difficult ideas without having finished something easy first.</li>
		<li>Choose to do everything by yourself without basis</li>
		<li>Get discomforted when other choose not to help with your "split revenue" project</li>
		<li>Get distracted by every new idea. Also known as "Feature creep" namely add too many features that defies or transcend the purpose of the original game.</li>
	</ol>

	Most of these signs are connected with a simple fact: <strong>Creating games can be boring! </strong>
</p>
<p>
	The human brain needs gratification and embarking in long difficult projects can drag your passion and dedication down the drain. If you recognize yourself in the previous statements, you are in the right place.
</p>
<h2>The first question is: Engine or Programming language?</h2>

<center><img src="/images/post/2018-11-28/languageVSeditor.png" alt="engine vs programming language" /></center>
<br/>
<p>
	This depends entirely on you. You'll always need some programming skills or someone who knows how to script in the future, so a smattering of programming will always serve you, the language is not important, the majority 
	of languages share a common ground. Anyway if you want only to create games choose the engine and forget the programming, you'll have time to learn it. Also choose carefully your engine and check some important things: 
	<ul>
		<li> it is still active</li>
		<li> it has a live community and lots of tutorials</li>
		<li> it's Multiplatform  (please be gentle and export for Mac and linux, these communities are always eager to play indie games cause the old windows monopoly)</li>
		<li> it doesn't require a nasa computer to run</li>
		<li> you can use it to sell your games without paying (you'll always have time to change to a more professional paid engine later, all the engines are similar in the use so if you get accustomed to an easy one, it will be easier to work on a more complex one</li>
		<li>It's 2D or strongly support 2D (you want to start from 2D before embarking in 3D, at least until you understand the basic concepts of game developing )</li>
	</ul>
</p>
<p>
My suggestion? Godot.  It has all of these qualities. And it's pretty intuitive to learn, also you can script in it and learn the basis of programming while creating your fist game.
</p>
<p>
	If instead you want to learn how to program or you know how to do it, just search "game framework for x language" (e.s.: game framework for c++ language) on your favorite search engine and follow the same ideas expressed for the engine search. My suggestion? If you already know a 
	programming language, choose a framework based on that, if you don't know any, start with c++ and sdl if you want to learn everything, with Lua love2D if you want a fast start. 
</p>

<h2>The second question: and now... what do I do?</h2>
<img src="https://upload.wikimedia.org/wikipedia/commons/f/f8/Pong.png" alt="pong game screen"/>
<p>
	The usual suggestion would be, start with some easy, well known games: pong, breakout, space invaders, tris, etc. And this is usually a good advice, because in this way you'll learn some tricks that will help you in the future. But if you are like me it can be boring to just follow some tutorial and get these games done. So my suggestion is: always put some of you into this projects. </p>
<p>
	Pong is boring? Put an explosive bomb instead of the classic ball that gets warm  the more the players bounce it
	(you can just make it more red every time it bounce and explode on the paddle once it gets completely red, destroying it and giving the adversary a point). Space invaders is plain and easy and xenophobic (poor aliens, what did they do to deserve such a fate?) change
	the aliens with something you hate and have double the fun destroying it.</p>
<p>
	It take just this to make it funnier. Just don't start with a 3D MMO or a vast metroidvania, there's plenty of reasons why to be found on the internet.
</p>
<h2>A last advice: If you can, comment it</h2>
<p>
	This becomes more obvious the more you program/create a game. The need of comments is ofter undervalued. Take your time to write observations for every new things you do. 
	Unless his purpose is obvious like ... int health = 10 //silly comment about assigning 10 points to health...
	and create a TODO list of things to do. Try to reduce your task to the atom, the littler the task, the more you'll feel accomplished after finishing four or five a day. You can find good examples of your language/engine comment etiquette online, or you can use <a href="https://www.cs.utah.edu/~germain/PPS/Topics/commenting.html" alt="commenting etiquette">generic ones</a> if you don't find anything.
</p> 
<p>That's said you're good to go. Now if you are interested in the continuation of these articles, please feel free to add my feed to your reader (if you don't know what RSS feeds are, inform yourself and add to your reader as many game dev blogs you find useful, it's a better way than
Facebook to learn something from this world). Also notice that <a href="https://github.com/sagana/Bummer" alt="bummer GitHub link">Bummer</a>, my first game in Lua+Love2D is being developed in this moment, and you can follow the progression of it and help with the correction of bugs and with your suggestions directly on GitHub :)</p>
