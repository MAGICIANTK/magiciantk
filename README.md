
Gemini

Chat

Spark
beta
New chat
Search chats
Images
Videos
Library
New notebook
OTHM Level 5 Web and Mobile Applications Assignment Briefs
Managing Digital Information: OTHM Assignment Briefs
All notebooks
Modify Registry Value: AutoCheckIntegrity
Installment Plan Comparison: 3 vs. 6 Months
Presentation Pacing and Q&A Practice
Phone Down Payment Calculation
Mail style RP
GitHub README Generation
Unlock Abans TV Key Lock
Group Skills Identification Document
Career Path Skill Gap Analysis
Career Path Skill Gap Analysis
Binary Code Translation: "I Love You"
Phone Comparison For Mother
Phone Comparison For Mother's Needs
Lecture Reschedule Request Email
Image Enhancement with Unintended Lens Flare
Image Enhancement with Specific Constraints
Image Enhancement of Graphic Emblem
Edit Promotional Poster Date and Time
Class Diagram Relationships Explained
Database Design: Entities, Relationships, Schema
Girls' School Comparison: St. Paul's vs. St. Joseph's
School Comparison: St. Paul's vs. St. Joseph's
System Modelling Introduction Note
සිම් ඊ-සිම් පරිවර්තනයට අනුමැතිය
සිම් ඊ-සිම් බවට පරිවර්තනයට අනුමැතිය
Monitor Installment Plan Comparison
Warranty Advice and Reddit Search
Installment Plan Comparison And Calculations
Database Design for PhD Supervision
ER Diagram: Student-Module Relationship
ER Diagram Based on Requirements
Vehicle Class Inheritance C++ Example
Relational Database Schema Design
Romantic Couple Image Combination
Installment Plan Comparison Calculator
Understanding 3-Tier System Architecture
Installment Plan Comparison: Monitor Pricing
Current Time in Sri Lanka
Conversation with Gemini
Write a GitHub README file that matches the modern era



My name - Thulmith Karunathilaka



Nickname - MAGICIAN TK



my email - thula.karu123@gmail.com



my social media URL - https://guns.lol/magiciantk



Undergraduate Software Engineering Student



divide into sections



add skills - as emojis as in the image



get a idea from the attached image



make with nice visuals



And add a mini game





and give me steps to add this from begining ( from creating a repository too ) 

Your README file is ready!

MD icon
README
 MD 
Open
I have crafted a modern, visually striking profile README tailored to your details (MAGICIAN TK). It includes a dynamic typing animation, a cool coding GIF, skill icon badges that perfectly match the aesthetic of your reference image, standard connect buttons, a Spotify "Currently Listening" widget, and a placeholder for the famous GitHub Snake Mini Game.

Here is your step-by-step guide to adding this to your GitHub profile from scratch, including making the mini-game work!

Step 1: Create Your "Special" Repository
Log in to your GitHub account.

Click the + icon in the top right corner and select New repository.

In the Repository name field, type your exact GitHub username.
(GitHub will show a green box saying "You found a secret! This is a special repository...")

Make sure the repository is set to Public.

Check the box that says "Add a README file".

Click the green Create repository button.

Step 2: Add Your Content
Go to your newly created repository and click the pencil icon (✏️) on the README.md file to edit it.

Delete everything currently in the file.

Open the downloaded README.md file I generated for you, copy all of the text inside, and paste it into GitHub.

Click Commit changes (top right corner) to save it.

Step 3: Activate the Mini-Game (Snake Animation)
Right now, the snake game image in the README will appear broken. This is because you need to tell GitHub to automatically "play" the game over your contribution graph and generate the file.

At the top of your repository page, click on the Actions tab.

Click on the "set up a workflow yourself" link.

Name the file snake.yml (in the box that says main.yml).

Delete the default code and paste the following code exactly as it is:

YAML
name: Generate Snake Mini Game

on:
  schedule:
    # Runs automatically every 12 hours
    - cron: "0 */12 * * *" 
  workflow_dispatch:
  push:
    branches:
    - main

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      
      - uses: Platane/snk/svg-only@v3
        with:
          # your github username
          github_user_name: ${{ github.repository_owner }}
          # generates the snake game files
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
            
      - name: Push the game files to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
Click Commit changes at the top right.

Now, go back to the Actions tab, click on Generate Snake Mini Game on the left menu, click Run workflow on the right, and click the green Run workflow button.

Wait a minute or two for the action to complete (it will turn into a green checkmark).

Once this finishes, go back to your main GitHub profile. You will see an awesome snake animation eating your GitHub contributions!

(Note: In the provided README file, under the mini-game section, make sure the <img> tags point to the output branch if you want them to display properly, but modern GitHub handles relative pathing easily once the action runs!)






Gemini is AI and can make mistakes.


<h1 align="center">Hello Fellow &lt; Developers/ &gt;! 👋</h1>
<h3 align="center">Hi! My name is Thulmith Karunathilaka. Thank You for taking the time to view my GitHub Profile 🤩</h3>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=2196F3&center=true&vCenter=true&width=600&lines=Undergraduate+Software+Engineering+Student;Tech+Enthusiast+%26+Developer;Welcome+to+my+Profile!;AKA+MAGICIAN+TK+🎩✨" alt="Typing SVG" />
</div>

---

### 👨‍💻 About Me

<img align="right" width="350" src="https://raw.githubusercontent.com/aungku-km/aungku-km/main/assets/coding-boy.gif" alt="Coding Animation" />

* 🔭 I’m currently an **Undergraduate Software Engineering Student**.
* 🌱 I’m constantly learning and exploring new technologies and frameworks.
* 👯 I’m looking to collaborate on **innovative software and web projects**.
* 💬 Talk to me about **software engineering, tech, and mind-blowing sites!** 🤯
* ⚡ Fun fact: I go by the nickname **MAGICIAN TK** 🎩✨
* 📫 Contact me via: **[thula.karu123@gmail.com](mailto:thula.karu123@gmail.com)**

<br/>
<br/>

### 🛠️ Skills `< / >`

<p align="left">
  <!-- These icons are generated dynamically and match the exact style from your reference image! -->
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=c,cpp,cs,html,css,js,react,git,github,dribbble,ai,ps,discord" alt="My Skills" />
  </a>
</p>

---

### 🤝 Connect with me 🤝

<p align="left">
<a href="https://guns.lol/magiciantk" target="blank"><img align="center" src="https://img.shields.io/badge/Website-MAGICIAN_TK-121212?style=for-the-badge&logo=about.me&logoColor=white" alt="MAGICIAN TK Profile" /></a>
<a href="mailto:thula.karu123@gmail.com" target="blank"><img align="center" src="https://img.shields.io/badge/Email-thula.karu123@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

### 🎮 Mini Game: GitHub Snake 🐍
*A game of snake played on my contribution graph! The snake eats my contributions to grow.*

<div align="center">
  <!-- NOTE: The image below will appear broken until you set up the GitHub Action (Step 4 in instructions) -->
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="github-contribution-grid-snake.svg">
    <img alt="github contribution grid snake animation" src="github-contribution-grid-snake.svg">
  </picture>
</div>

---

### 🎧 What I'm Listening to Right Now
<p align="left">
    <a href="https://open.spotify.com/"><img src="https://spotify-github-profile.midudev.now.sh/api/view?uid=spotify&cover_image=true&theme=default&show_offline=false&background_color=121212&interchange=true&bar_color=53b14f&bar_color_cover=false" alt="Spotify" /></a>
</p>
README.md
Displaying README.md.
