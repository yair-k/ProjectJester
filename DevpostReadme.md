
![Project VSAP](https://media.discordapp.net/attachments/777942258569576468/853136241054580746/banner_side_text.png?width=1080&height=472)

# ✨Welcome to Project Jester ✨

## ✌️ Inspiration & Explanation: ✌️
Since childhood, we have all played the well known game Hangman.

The goal of this game is too guess a letter from a word or sentance taking turns, before the ammount of chances you have. When guessing the word, you know the length of the word, and as the game progresses, you fill in the blanks of the phrase.

Recently, I played Hangman again during online class, and the phrases were quite hard. I was inspired to create a tool to help me become better at hangman and have more fun at it.

Projest Jester is a tool made to help you guess likley possibilities for the words, and train your vocabulary for hangman the more you use the tool.

***Project Jester is meant as a tool for the popular game Hangman***

**Live Demo:** [Project Jester](https://projectjester.neocities.org)

**Explanation Video:** [Youtube - AlphaHacks 2021: Project Jester](https://www.youtube.com/watch?v=cn72vaj4BQk)

## 🖼️ Preview: 🖼️
![Main Page](https://media.discordapp.net/attachments/777942258569576468/853140902306775080/1.png?width=1080&height=545)
![Word List](https://media.discordapp.net/attachments/777942258569576468/853140905111191572/2.png?width=1080&height=545)![Hints and Tips](https://media.discordapp.net/attachments/777942258569576468/853140901408014336/3.png?width=1080&height=545)

## 🛠️ How I built it: 🛠️
Originally, I intended to use the [Flask Framework](https://flask.palletsprojects.com/en/2.0.x/) as I had prior experience with it and I enjoy Python coding. However, I realised that this was not neccesary for this case. The website was to be created using:
>Bootstrap 5.0

>HTML

>CSS

>JavaScript

The single page site was to have redirects and popups, rather then an advanced multi-page tool.

The original method to grab every word in the english dictionary as a call from an API. However after browsing, this turned out to be inneficient. Later I came across a download to a list of all used the words in the english language that were not impossibly long, complex, or confusing abbreviations. This list ended up being only *5200kb* in size (Much more efficient then calling an API and waiting for a request back).
![Wordlist File](https://cdn.discordapp.com/attachments/848754321595957298/853143541965520967/unknown.png)

The order of development I decided to use was to finish the Backend first, then focus on Frontend looks. This proved to be efficient in this case as the core was much easier to do then the design, and making datasheets look good is no simple task :P

After finishing a basic system for identifying the words with unknowns, I added a feature to count total character length for faster typing of the user.

After the main Backend was completed, I focused on creating a UI and interactive design. 

There were some challenges creating a responsive design and having everything be animated, but with the power of CSS, JavaScript, and Google, It was done.

In the middle of finalizing the Frontend, I remembered about embedded integration, SEO as well as making the website mobile Friendly, all of which are shown below: 

![SEO + Embedding](https://cdn.discordapp.com/attachments/848754321595957298/853145775068807168/unknown.png)
![Mobile Friendly](https://media.discordapp.net/attachments/848754321595957298/853145951039127552/unknown.png?width=1080&height=546)

In the end, small adjustments were made and I decided to add a seperate hint page rather then a little pop up from the tool, as well as creating the main navication Button based rather then one after the other.

## Challenges/Difficulties:
My main challenge I expected to go into was hosting. Previous projects proved how annoying hosting and configuration can be, however with this website, there were no advanced properties, so hosting was a breeze with minimal configuration.
![enter image description here](https://cdn.discordapp.com/attachments/777942258569576468/853146283703009311/unknown.png)

Another challenge I ran into was trying to get the hints page to work accordingly with a pop-up inside the Tools category. Unfortunatley, I had to choose between maximim detail or maximum looks and I went with detail. All the hints were added onto a seperate page and can be interacted with through a button on the main page.

Finally, the last problem I encountered was updating the website. The host had slow connection at times and my updates weren't updating in real time. Thankfully, near the end of the hackathon this was fixed on it's own.

**Before:**
![Before](https://media.discordapp.net/attachments/777942258569576468/853148246398074900/unknown.png?width=930&height=355)

**After:**
![After](https://media.discordapp.net/attachments/777942258569576468/853148449733738516/unknown.png?width=428&height=183)

## 💡 What we learned & What's next 💡
I learned a lot of usefull formatting tips as well as Bootstrap/CSS strategies to improve a websites performance/looks.

Additioanlly, I also learned string categorization and usage in JS, something I was a bit weary on before.

I plan on adding in more features as listed in our to-do list, as well as more classic game tools.

Project Jester was not only a fun development, but also has massive use to people playing hangman around the world.

I plan to keep the utility public for as long as possible, and continue to update it with requested features.


*If you made it to all the way here, thank you for reading about our development and we hope you have a great day!*

![enter image description here](https://i2.wp.com/wowlookawebsite.com/wp-content/uploads/2018/07/that_s_all_folks__by_surrimugge-d6rfav1.png?fit=1024,576&ssl=1)
