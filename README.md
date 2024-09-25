# Fight-game-hit-box-generation-v2
Unusual and unnecessary source code to create hit/hurt boxes for a fighting game. It use radiosity to catch 3D rendered datas. It is non convenient and hardly
acceptable but I did it with freelancers. I mean the specs and full algorithm. It can catch some things !

The project is not the same as before because
we will use game designers algorithms to support error tolerance in hit boxes positions.
So, now, as we developped our engine and our game c# scripts during all this period, we don't have many things to do
to finish the game. I contact you to ask you if you can finish implementing C# scripting support to our game engine.
It is true that you will have to see the full source code and we will provide it to you. There are not many things to
do and, after that, we just have to finihs the fighting game logics.
Let me explain in more detail the current state of our scripting engine. First of all, the c# scripts can be serialized and deseerialized. Then, in order to use cpu mutlicore technology, the c# scripts are converted in C++ native codes which cpu core
will only handle c# functions bodies, nothing else. On the other hand, in the C++ side, we use boost to be able to deserialze untrusted objects, but the logic of the game remain in the C# code which need to be convert'ed in native code by .net.
So, in c++ side, there is another thing to do : we have to put class exact names in the main loop of in the main function
or more precisely, in the main class that the c++ main function call. The names must be the same as in the c# code. Note that the engine can be enhanced too if we had define directives to generate classes to handle that problem but, due to lack of time, we won't do that.
Are you still available to work on this cutting edge project ? Let me know your bid.The task is not hard but requires experts.
Then, I will send you the source code.


Applied Computational Geometry. Towards Geometric Engineering - Google Books
https://www.google.fr/books/edition/Applied_Computational_Geometry_Towards_G/56_td-bh4vgC?hl=en&gbpv=1&dq=computational+geometry+visibility+complex&pg=PA177&printsec=frontcover

page 188
page 181, there is a graph connection with objects tangents.
There is description of the algorithm with the form factors field used with radiosity. Maybe there is a way to use raytracing but the this may be the start of what I want unless you have a better idea. There msut be available source code relating this book problem or something similar in github. I think I already described what I wanted for my game. As my game engine only support rasterizer raytracing and some lacks in the scripting, I think you will not need it. You can do this work in unity. I mean to have a 3D scene with 2D movements with two characters with judicious management of the scene in order to enable your algorithm to be executed and have an output per frame hit boxes.

There is a link here which can allow you to have a basic fighting game which support multiple frames actions : 

https://github.com/Acre-Entertainment/New-Dino-Project/blob/50aac9c6856b187c6dc08224a56a69a012093b2b/Assets/-Dino_Project/Scripts/OurScripts/Fight/FightEnemyController.cs

You must notice that, for the scene, there must be a good configuration of light and meshes like sticks character to allow good fitted hit box generation (even with my started algorithm).

Then, I prefer to let you do your work. After that, like I said, 2 developpers works for 70 dollars per hour and the project manager work for 55 per hour. That said, the total amount will be 125 dollars per hour. With my current situation, I can pay you one developper with a project manager working with him too, that mean 80 dollars per hour. My budget is 800 dollars per month but as we accorded ourselves, I can pay you in multiple months. So I need your deadline.


