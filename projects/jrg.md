---
layout: project
type: project
image: img/jrg/jrg.png
title: "Japanese Reading Game"
date: 2026
published: true
labels:
  - C
  - SQLite
  - Python
summary: "A text-based game focusing on improving the reading comprehension speed of hiragana and katakana Japanese characters."
---

<div class="text-center">
  <img width="800px" class="img-fluid" src="../img/jrg/hiragana_table.png">
</div>
<br>
The Japanese Reading Game is a text-based game designed to aid in improving the reading comprehension speed of Japanese hiragana and katakana characters. The logic of the game is to provide words written in hiragana or katakana to a user and then have that individual respond with the romaji version of the word. The faster a user answers, the more points they gain. The hiragana and katakana words along with their romaji counterpart are stored in a SQLite database. The game itself is written in C and interfaces with SQLite to provide questions to the user and check the user’s answers. 

To provide easy access to the game, I created a Python coded Discord bot deployed through Railway that acts as the intermediary between the user and the game. Users can join a discord server to send messages directly to the bot and play the game directly in Discord. This project was a very engaging challenge learning how to interact between three different languages at the same time. This project improved my existing technical skills while developing new ones.

Source Code: <a href="https://github.com/danilk09/Japanese-Reading-Game"><i class="large github icon "></i>https://github.com/danilk09/Japanese-Reading-Game</a>
