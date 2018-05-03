---
title: "Devenez un Développeur de Jeu : Vos Premiers Pas en Programmation"
description: Vous souhaitez créer vos propres jeux mais vous n'avez aucune expérience en programmation ? Ce guide est fait pour vous ! Cette série vous aidera à débuter en programmation et en conception de jeu.
author: nathan

banner:
  src: ./img/banner.png
  alt: Un personnage étudiant du code devant un ordinateur, un bureau et deux livres

date: 2018-04-12T09:04:58+09:00
---

Vous souhaitez débuter dans la création et la programmation de jeu mais vous ne savez pas par où commencer ? C'est justement le sujet de cette série !

Cette première partie est faite pour vous si vous n'avez pas ou très peu d'expérience en programmation. Vous allez apprendre :

1. Que vous devriez **d'abord apprendre les bases de la programmation**
2. Que **La programmation est accessible à tous**. Ce n'est pas juste une question de math et ce n'est pas réservé aux hommes ou aux jeunes personnes
3. **Comment débuter dès aujourd'hui**

<!-- TODO: Si vous maîtrisez déjà les bases de la programmation, consultez la deuxième partie : [ Débuter en Programmation de Jeu et Godot ](). -->

<span class="note">
Ceci est la première partie d'une série *Libre et Open Source* d'introduction à la création de jeu et au [ moteur de jeu Godot ](https://godotengine.org/). Cela a été rendu possible par 760 genereux soutiens et sponsors Kickstarter.
</span>

<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-refresh-toc -->
**Table of Contents**

- [What do you want to create?](#what-do-you-want-to-create)
- [To code games, you need programming foundations](#to-code-games-you-need-programming-foundations)
- [The first language you'll learn isn't that important](#the-first-language-youll-learn-isnt-that-important)
- [Programming is for everyone](#programming-is-for-everyone)
- [Visual programming is still computer code](#visual-programming-is-still-computer-code)
- [I recommend to start with Python](#i-recommend-to-start-with-python)
- [Three resources to learn Python step by step](#three-resources-to-learn-python-step-by-step)
- [Your Questions](#your-questions)

<!-- markdown-toc end -->


## Faites un pas après l'autre

La création de jeu peut donner l'impression d'être insurmontable de prime abord. Nous avons tous vécu de durs moments à nos débuts *que l'on se le rappelle ou non*.

Pour faire des jeux seul, vous devez à la fois apprendre :

1. **La conception de jeu**, comment trouver des mécaniques intéressantes, des règles et des objectifs pour les joueurs
2. Et la **programmation**, ou comment traduire votre conception en un langage que l'ordinateur comprend

Cela fait beaucoup à gérer d'un seul coup ! Comme toute discipline créative, cela prend du temps. Néanmoins, ne vous inquiétez pas : apprendre peut être une expérience amusante !


{{< figure
  src="./img/one-step-at-a-time.jpg"
  alt="Un chat descend des escaliers"
  caption="Le code et la conception sont de nouveaux mondes à découvrir et à explorer. Prenez votre temps, restez curieux."
>}}


Au début, vous ne serez peut-être pas capable de communiquer votre vision et vous ferez face à des obstacles tout au long du chemin. Mais vous vivrez également de nombreux moments drôles et vous aurez une profonde satisfaction quand votre famille ou vos amis jouera à vos jeux.

Lorsque vous débutez tout juste, vous devriez vous **concentrer sur le code et la conception de jeu séparément**. Que ce soit en parallèle ou une discipline après l'autre, vous devriez apprendre les bases, écrire quelques programmes, concevoir des jeux simples sur papier... puis rassembler les deux disciplines pour créer des jeux vidéos.

C'est ce que nous allons explorer dans cette série, à commencer par la programmation.

## Que voulez-**vous** créer ?

Pour rester motivé, il vaut mieux que vous compreniez pourquoi vous voulez apprendre et quels sont vos objectifs.

Qu'est-ce qui vous pousse à créer votre propre jeu ? Prenez un moment pour réfléchir aux questions suivantes :

- Quel jeu voulez-vous créer ?
- Faites-vous cela pour le plaisir, en tant que hobby, ou pour devenir un professionel ?
- Qu'avez-vous besoin d'apprendre en premier pour atteindre ces deux objectifs ?

Il n'y a pas de réponse définitive. Voici comment j'ai débuté, il y a longtemps :

> Je veux créer un petit RPG inspiré des jeux Japonais pour le plaisir, le terminer, et le partager avec mes amis. Je veux tout faire moi-même alors je dois apprendre la conception de jeu, l'écriture d'une histoire, le codage ddu jeu, le dessin des personnages et des environnements, la conception des niveaux, la création des sons et des musiques, ... euh, par où dois-je commencer ?
>
> <footer>Moi, 13 ans et naïf</footer>

Cela faisait beaucoup à gérer seul mais ce but devint l'objectif qui me guida toutes ces années : j'ai construis des fondations dans tous ces domaines à différents degrés. Homme à tout faire, maître de rien ! Cela me prit un long moment avant d'être capable de créer des jeux car je me mis à la programmation en dernier.

{{< figure
  src="./img/shapes-old-game-project.jpg"
  alt="Capture d'écran d'un vieux projet abandonné de RPG"
  caption="Un de nos vieux projets de jeu d'Aventure avec Nemega"
>}}

Vous devrez être patient. Visez petit et développez vos compétences dont vous avez besoin séparément. Vous n'êtes pas non plus obligé de tout faire tout seul. Avec un peu d'expérience, vous pouvez vous associer avec d'autres créateurs de jeux qui vous sont complémentaires, dans des game jams par exemple.

Suposons que vous souhaitez créer des jeux vidéos par vous-même. Peut-être que ce sera juste des prototypes de jeux que vous pouvez essayer avec vos amis et enrichir avec l'aide d'un développeur lors d'un stade plus avancé. Let's assume that you want to make video games by yourself. Vous allez devoir plonger dans le code, mais...

## Pour coder des jeux, vous avez besoin de bases en programmation

Si vous foncez directement dans un éditeur de jeu et essayez d'écrire du code, vous allez avoir des ennuis. Un moteur de jeu est une large collections de technologies qui accumulent des centaines, si pas des milliers de nouveaux outils et fonctions à apprendre en plus des bases de la programmation. Vous allez être souvent bloqué et vous finirez frustré de ne pas pouvoir avancer. Si vous ne savez pas ce que sont des variables, des fonctions, des boucles, des objets, et des classes, ou comment ils fonctionnent d'une manière générale, vous devrez d'abord **construire de solides fondations**.

> Vous devez écrire du code pour devenir développeur. De nombreux débutants ont peur d'écrire du code qui fasse planter l'ordinateur. Vous ne l'abimerez pas. Evidemment, votre programme va planter et il y aura de nombreux bugs mais tout va bien. Vous ne pouvez apprendre qu'en essayant.
>
> <footer><a href="https://twitter.com/valryon/">Valryon</a>, co-fondateur de <a href="http://pixelnest.io/">Pixelnest</a></footer>

![](img/sterenden.png)

Pour avoir de bonnes fondations vous devriez :

1. Apprendre votre **premier langage** et avoir une idée des outils de base de la programmation tels que les variable, les fonctions, les boucles, et les classes
2. **Ecrire** des programmes simples tels que des jeux interactifs uniquement en texte ou des scripts pour automatiser des tâches ennuyeuses sur votre ordinateur
1. **Lire** du code écrit par d'autres personnes et essayer de comprendre ce qu'il fait

<span class="note">
La programmation - en particulier pour les jeux - est une activité créative. Vous pouvez passer votre vie entière à explorer de nouvelles techniques et affiner vos compétences. Prenez votre temps et essayez d'apprécier le voyage.
</span>

Gardez à l'esprit le principe **KISS** pour éviter toute frustration : **faites court et bref (Keep It Short and Sweet)** Vous pouvez apprendre rapidement avec des sessions d'entraînement courtes et concentrées.


## Le premier langage que vous apprendrez n'est pas si important que ça

There are [ hundreds of programming languages ](https://www.wikiwand.com/en/List_of_programming_languages) out there. But it isn't that* bad: by learning one language you learn a lot more than syntax. You're going to learn concepts like variables, loops, and objects that work about the same in most programming languages. C++, Java, C#, etc. have a lot of similarities so moving from one to the next won't feel like starting over again.

{{< figure
  src="./img/programming-languages-books.jpg"
  alt="A large pile of programming books with many different languages"
  caption="Dozens of languages are represented in these old tech and programming textbooks. CC 3.0 SA Victorgrigas"
>}}

**Learning a given language is a small part of learning programming**. As you gain experience, you'll acquire more and more knowledge that you will be able to transpose across tools and languages: how to structure your code, how to avoid bugs, how to learn on your own with a programming manual or reference...


## Programmer est accessible à tous

You don't need to start with a tough, low-level language like C++. When I was in middle school, a more experienced developer taught me C++,  his argument being that it is one of the most widely used languages. At the age of 14, I got a 1000 pages long intro to C++. I had a horrible experience reading it and concluded that programming was not for me. I was disgusted from programming and stayed away from code for years.

I got back into code with Construct 2's visual event system, working as a junior game designer on mobile games. The engine's creators sold it as a *programming-free* engine. That seemed perfect for a designer like me!

{{< figure
  src="./img/construct-2-event-sheets.png"
  alt="Construct 2's event blocks"
  caption="Construct's event sheets work by picking conditions on the left and coding actions or consequences on the right"
>}}

It took me a few months to realize that I was storing values in variables, writing calculations, using functions and loops, data containers like arrays… I was coding all this time. And it was fun! From there I learned some JavaScript followed by Python. It sure had nothing to do with C++. The tutorials were a lot more accessible and both languages much simpler to use.

There are different types of developers, and different paths to becoming a developer. There are languages, programs, and technologies that will prove to be a better fit for your skills and what you want to make.

> Programming is for everyone. You don't need to be a man, to be young or "gifted". If I had started earlier I would've avoided a lot of obstacles in my career.
> It's a myth that we should debunk right now.
>
> <footer><a href="http://fenntasy.com/wanuts/">Florïn Zolli</a>, level designer at Ankama (Dofus, Wakfu), community manager at MotionTwin, now studying development</footer>

Women can code just as well as men. Designers and artists can also code. Again: **programming is for everyone**. You've just got to find the tool that's right for you.

## Ne commencez pas par le C++

Unless you like to learn the hard way, you don't have to start with C++. C++ is a **complicated**, feature-packed language designed to write code that runs fast. It's not meant to be accessible. It's not meant to be part of your first programming experience. Especially if you are young and don't like math or if you are not very comfortable with a computer. Lucky for us, it's not necessary at all to get started with programming or to become a professional game developer.

{{< figure
  src="./img/c++-book.jpg"
  alt="Three programming books piled up, dedicated to the C and C++ programming languages"
  caption="It's one of these monolithic programming books that made me hate programming at first"
>}}

> There are different types of developers: some like to code for the sake of it while others are driven by projects. You shouldn't be discouraged if you aren't part of the first group. I don't like math, or programming in itself, it's ok : it doesn't prevent you from creating games.
>
> <footer><a href="http://fenntasy.com/wanuts/">Florïn Zolli</a>

There are **thousands of ways to code**. You don't have to do complex math to build games. You can challenge yourself with complex algorithms if you want to. Or just animate characters moving on the screen!

Even if it feels scientific at first, programming is a creative problem-solving activity. There are always multiple solutions for a given problem. In an upcoming guide in this series you'll learn about a paradigm, a set of mental tools to structure your code called **Object-Oriented Design**. As the name suggests it involves design work. Keep this in mind as you're taking your first steps: doing code is not just about maths. I am a designer at heart and I enjoy programming.

{{< figure
  src="./img/object-oriented-design.png"
  alt="Diagram of two monsters inheriting from a base class"
  caption="Object-Oriented Design is a tool to make your game code manageable"
>}}

## La programmation visuelle reste du code informatique

Do you feel uncomfortable writing code as text? At first that's normal; you're learning to communicate with a machine using a foreign tongue.

You may be tempted to stick to visual programming tools, thinking it's not really programming but it is. Whether you use Scratch, Clickteam Fusion, Unreal's Blueprints or anything similar, you already have some programming experience.

{{< figure
  src="./img/godot-visual-scripting-language.png"
  alt="Screenshot of Godot's VisualScript editor, a visual programming language"
  caption="Game engines like Unreal or Godot offer an extensible visual scripting languages for designers and artists."
>}}

As a beginner the main differences between text-based and visual programming are:

1. Visual programming is a little more accessible at first, as it is visual in nature, but is often slower to write and manage as your code gets more complex
1. With text-based code you can make typos. Unlike us, a computer can't make sense of a keyword if you swap two letters.
  - But modern code editors are here to help: they smartly autocomplete keywords as you type, they can tell you when you've made a mistake and often even highlight issues for you.
  - As with every discipline, practice makes perfect: the more you write, the fewer typos you'll make.

<span class="note">
A code editor can report errors when you run the program and it fails. You will then see the error report as text in a programming console. Text editors can also read your code as you are typing it and report the most common errors before you run your project. This is called **linting**.
</span>

{{< figure
  src="./img/godot-gdscript-fuzzy-autocomplete.png"
  alt="Screenshot of Godot's GDscript editor with fuzzy code autocompletion"
  caption="Godot's script editor suggests the right keywords even if you don't type all letters or invert some"
>}}

In my experience working only with visual languages does not scale well. As your projects grow in size, visual languages will become more inconvenient. They're often slower to use than text as you end up navigating through menus and connecting blocks to do basic operations.

To give you an idea the VisualScript example above only takes 2 lines in the text-based GDscript language:

{{< highlight gdscript >}}
func _process(delta):
	position += direction * speed * delta
{{< /highlight >}}

You will only see the drawbacks of visual code after you have learned and gotten comfortable with text-based programming. It is okay to start with visual code. Just don't count other programming languages out because they're harder for you to get started with. As a designer I'm glad I made the transition: it felt a little uncomfortable at first but I never looked back.


## Je vous recommande de commencer par Python

As a game development tutor, I see so many **beginners jump head first in an engine and fail**. They follow step-by-step tutorials or copy-paste code from demo projects hoping to build their own dream project. As they lack programming foundations they get stuck as soon as they tweak a line of code. Doing that, you mostly end up wasting time and building up frustration.


Coding is like writing in a foreign language: you've got to learn some basic vocabulary and grammar first, use everything you learn as often as possible in order to commit it to memory, and take your time.

**Be patient**. It won't take too much time before you can get started with game programming. Try to spend about 20 hours focusing on programming basics. Then you can start having fun with game development if you want. Just don't forget to keep building and sharpening your core programming skills in parallel!

![Python programming language logo](./img/python-logo.png)

I recommend to start with Python for at least 3 reasons:

1. You can create **all kinds of programs** with it: automate tasks on your computer, code web applications, science applications, even games...
1. It has a **huge active community**. Python is taught in many schools and universities so it's easy to find good learning resources for teenagers and adults alike. My friend Chris Bradiel even [ teaches Python to kids ](http://kidscancode.org/)!
1. It is easy to approach thanks to its **simple syntax**

Python looks like this:

{{< highlight gdscript >}}
numbers = [2, 4, 6, 8]
product = 1

for number in numbers:
   product = product * number

print('The product is:', product)
{{< /highlight >}}

With these instructions the computer calculates the product of `1 * 2 * 4 * 6 * 8` and tells you the result:

```
The product is: 384
```

**Python is great to get started with code**. For aspiring game creators it's also a reliable tool: it's the most common language to write plug-ins for graphic applications such as Blender, Krita, and Gimp. This is not only true for Free Software: large 3D applications like Maya or 3DSMax also let you write new features with Python.


> During the last Europython I've met companies who use Python in game development work. Crytek and EA (Frostbyte) use it in their assets pipeline, the build system, and automated tests.
>
> <footer>Emmanuel aka TouilleMan, author of the <a href="https://github.com/touilleMan/godot-python">Python support in Godot</a></footer>

As explained earlier, we're talking about your first text-based language here. It certainly won't and shouldn't be the last you'll study. Python is a good stepping stone on your learning journey: it's a middleground between visual programming languages like Scratch and strict ones like C++.

You'll find few games written in the Python language. Game development companies mostly use Python for the creation of tools outside of the game engine: everything that has to do with processing art and other assets to use in the game for example.

{{< figure
  src="./img/jetbrains-python-uses-2017-survey.png"
  alt="Graph showing the percentage of Python developers who use the language for data science, web development, etc."
  caption="One in four Python developer uses it for educational purposes"
>}}

> Various studies show that the number of Python developers is growing steadily year by year. [...] Many people are starting to use Python for data science and machine learning.
>
> <footer>Jetbrains 2017 <a href="https://www.jetbrains.com/research/python-developers-survey-2017/#types-of-development">Python developers survey</a></footer>

<!-- <span class="note"> -->
<!-- You can write all kinds of programs in Python. Developers around the world use it to create anything from basics scripts to self-improving artificial intelligence, complex cross-platform applications or website back-ends like YouTube's. Both small and large companies like Google and Microsoft hire Python developers. -->
<!-- </span> -->



## Trois ressources pour apprendre Python pas à pas

I don't want to flood you with a long list of resources. Instead here's three that I like: two interactive courses which you can complete in your browser without having to download any tool and a free ebook that will help you automate repetitive tasks on your computer with Python.

### Codecademy's interactive Python 3 track

You can get started right now with the Python programming language using [ Codecademy's interactive Python course ](https://www.codecademy.com/en/tracks/python). You don't need to download a code editor as you'll write code directly in your browser. It covers the language's basic syntax in an accessible fashion.

{{< figure
  src="./img/codecademy-console-example.png"
  alt="Codecademy's programming console with Python sample code"
  caption="Codecademy's Python editor features the lesson, your code and the result side-by-side"
>}}

### Code the Blocks

[ Code the Blocks ](https://codetheblocks.com/) defines itself as a "free and interactive playground for learning how to code". Drawing blocks in a way reminescent of Minecraft, you'll get to see how to create shapes in space with Python from your first program.

{{< figure
  src="./img/codeblocks-console-example.png"
  alt="Example of a helix made of blocks and the Python loop that generates it side-by-side"
  caption="Code the Blocks lets you play with a 3d environment, a bit like what you'll do in a game engine"
>}}

### Automate the Boring Stuff with Python

Put your new Python knowledge to good use with this [ free book ](http://automatetheboringstuff.com/)! It is a collection of nice tricks to make your computer work for you. Need to rename many files in a complex way or automate web searches? Each of these programming drills will help you better understand your computer and the Python language by giving you new tools which will help you save time in your future projects.

![Automate the Boring Stuff with Python ebook cover](./img/automate-boring-stuff-with-python-cover.png)

The Python community also put up a [ nice guide ](http://docs.python-guide.org/en/latest/intro/learning/) to help you go further with the language.

## En résumé

That was a long article, right? If you should only remember a few key points:

1. You'll need some **programming foundations** before you can make your own video games
1. Learning to code may feel hard at first but it will get easier with practice
1. You don't have to start with a difficult language
1. **Code is for everyone**. Not only people who like math, not only men
1. Learning to code is a bit like learning a foreign language. You've got to write and read a lot of it to become comfortable

It is time for you to use the resources above and to start building your programming muscles! Pick one course, learn in short, focused sessions, and try to practice on your own to learn most efficiently.

In the next part we'll get started with game design. You can find me [ on Twitter ](https://twitter.com/NathanGDquest) if you have questions!

{{< gumroad-call-to-action >}}

##  Vos Questions

Got questions about getting started with programming? [Send me a tweet](https://twitter.com/NathanGDquest) !

I'll add the most useful answers here. Click on questions to unfold them.

<details>
<summary>{{< icon cog >}} What about performances? I heard Python is slow.</summary>

When you're learning how to code, the language or the engine's performances is the least of your concerns. Today's computers are so fast you will have to try very hard to bring them to their knees. Your goal at this point should be to learn to code, not to write fast applications. Lastly, most of the performance issues you'll face will come from your own code.

Now let's talk about the language's performances. You may have heard Python is a [ dynamic language ](https://www.wikiwand.com/en/Dynamic_programming_language) and that it is slower than classic languages like C or C++. It turns out that Python is built upon the C language so most of the instructions you write in a dynamic language like Python call code written in the comparatively fast C language.

The same is true when you work with a game engine. Many rely on a dynamic language to help code gameplay mechanics fast. These languages, often called scripting languages, may be slower than C++ but every engine feature you use, like drawing on the screen, uses the fast engine's C++ core.

Back to Python. You can compile Python code just like C or C++ and get the same speed and control over your code. If you really need to.

{{< figure
src="./img/pypy-logo.png"
alt="PyPy Python JIT compiler logo"
caption="Pypy does Just-In-Time compilation to make your Python code run faster"
>}}

But again: you shouldn't think about performances when you're learning. When starting a game, professional game developers don't care so much about performance as you can always improve performance later. Most of the time it's only a tiny part of the game's code that drags the performances down.

However using a language that's easy to read and fast to write saves you a lot of development time. That's why, as you'll see, game engines like Godot generally provide two languages: one back-end language for the fast core, and one or more scripting languages for the gameplay.
</details>
