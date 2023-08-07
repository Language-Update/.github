# Language Update
Hi there! My name is Bora Ozenbirkan and I am the creator of this project(s). The idea was to **gamification of language learning** and **focus on the results of learning**, instead of being easy.

There are many language learning apps but they are not effective and most of the time, **boring**. As a Japanese learner, I couldn't find any app that really helps. So, I decided to make one!

Once I started to think about it, I come up with dozens of ideas. I created concept art for them and started to make the first game. **Japanese Warrior!**
<p align="center">
<img src="/profile/Images/Language_Update_Apps.png" alt="Japanese Warrior" width="500"/>

The idea of learning languages by playing games involved a **language-learning universe** combined with blockchain technology! I made very detailed business plan on that called **[Language Update Yellow Paper](/profile/Language%20Update%20Yellow%20Paper.pdf)**, you can find it in the files above. Japanese Warrior was the first step of this bigger plan.

## Japanese Warrior
Japanese learners start with learning the **Japanese Alphabet: Hiragana and Katakana**. There is also Kanji but they are scripts and next-level stuff.

Hiragana and Katakana learning apps have a simple system. First, it shows you the alphabet in parts, then asks them in a random order. After a while, it becomes so boring to do so.

**Japanese Warrior comes to the rescue!** You are learning on a screen where you match alphabets while you are getting help with the correct matching order you see above. Then, you can start practicing. **The fun part!**
<p align="center">
<img src="/profile/Images/JW_Learning.gif" alt="Japanese Warrior" width="200"/>

You are defending the Castle! There are mutant turtles attacking you. **Whenever you give the correct answer, you earn a blade to throw to attacking enemies.** Wrong answers give causes a delay for the next question which makes you nervous because the **enemy doesn't stop!**

Enemies come in **waves** and each wave is more difficult than the previous one. They are **speeding up, getting different mutations, and being bigger and stronger!** Eventually, you hunt you down and take the Castle!
<p align="center">
<img src="/profile/Images/JW_Practice.gif" alt="Japanese Warrior" width="200"/>

The goal is to defend the castle as long as possible. Just like the Flappy Bird, you are competing with your older self! **How many waves can you handle this time?**

And there is also a **multiplayer** version! Real fun relies on competing with your peers, right? Although the multiplayer version was a demo and it was actually a bot, it was the very next thing I would do after the success of the Open Beta version. **You can watch the full video of the game [from here](https://youtu.be/lBS6TOwJl0w)**
<p align="center">
<img src="/profile/Images/JW_Multi.gif" alt="Japanese Warrior" width="200"/>

**I also developed an Algorithm** to evaluate the learner's acquisition on certain words, alphabets. **The order of question wasn't random in Japanese Warrior, it was ordered by algorithm!** The basic mechanism of it was deciding learner's acquisition level (new, weak, modarate....Native) and giving questions accordingly. 

It is more likely to ask you to the ones you are week on. While learner's acquisition level is increasing with more intense correct answers, the chances of encountering with that word decreases. **But if the learner answers wrong on that word after a while, the word starts to appear more! The app guarantees that you'll learn everything!** You can find **[ the Algorithm code here](https://github.com/Language-Update/Japanese-Warrior/blob/patch-in-work/Japanese%20Warrior/Assets/Scripts/Algorithm.cs)**, in the Japanese Warrior > Assets > Scripts.

## Key Features
- An **algorithm** that makes sure you to learn everything well!
- User authentication and database
- **Lazy login:** Keeps user data saved locally until user registers!
- Exciting and **fun** practice!
- **Multiplayer:** Even though it's a bot for now.

## Challenges
✅ Creating a language learning algorithm and data structure was quite challenging. Displaying these contents on learning scenes and practice scene was the first challenge I handled.

✅ The second challenge was the game itself. Creating a game design that enemy comes in different waves and starts to get better in each wave was really fun!

✅ The biggest challenge in this app was the Learning Algorithm. Previously I was displaying content randomly but then I developed an algorithm to evaluate learner's acquisition on certain words. Then this app questions and tests the learn and makes sure that every word is being save in the long memory of that human brain! This was the most difficult thing that I have done in this project!

✅ I have implemented a User Authentication and Database system with Firebase to save learner's data in cloud. This was the first time I have created such systems. Learning how these system works and implementing them into this kind of complicated project was quite educational and experimental.

❌ I wanted to complete the multiplayer feature of the app but couldn't find the motivation to do so. Because the app didn't get any traction with its Open Beta version.

## Results
Even though the app didn't get any traction at first, I continued to develop it. I added **User Authentication and Data Base** as you can see in **[this update video](https://www.youtube.com/watch?v=zDZ8_PH5P4M)**. But, in the end, nobody didn't install the app for a long time. And I left the project as it was, in Open Beta.

Sad story, but, I continued to develop the idea into a simulation metaverse called **[Metalife!](https://youtu.be/uS1atfC8YNk)** You can find more about it on my Github profile!