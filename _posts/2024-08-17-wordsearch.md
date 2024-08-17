---
layout: post
current: post
cover:  assets/images/welcome.jpg
navigation: True
title: Wordsearch Generator
date: 2024-08-17 22:17:00
tags: [coding]
class: post-template
subclass: 'post'
author: pmak
---

On my recent trip to India, I found myself staring at a screen for extremely unsafe durations, be it my mobile, laptop or television. During that period of heightened screen time, I truly realized the meaning of 'tired eyes'. Consequently, I started looking for alternative ways of enjoying my time. By a stroke of luck, a book of 120 wordsearch puzzles, bought several years but left incomplete, was found by my mother. This book captivated my mother and I to such an extent that we 'rationed' the resource, limiting ourselves to solving two puzzles per day. It was with a heavy heart that I found the last hidden word, just when our trip drew to a close. Though this particular book's supply of eye-friendly entertainment was exhausted, I resolved to create a WordSearch Generator Program to ensure a never-ending supply of wordsearch puzzles.

### The Task
 - **Input:** A title for the wordsearch puzzle and a list of words to be hidden in the puzzle.
 - **Output:** A wordsearch puzzle grid with all the input words hidden in a sea of undecipherable character sequences.

### Initial Information - Rules of the Game

The puzzle consists of a **square grid** of alphabets. A **set of words** is provided. 

**Objective:** Find all the given words in the puzzle.

For a given word $w$, all characters of $w$ will be located linearly in a readable order. That is, it will be possible to draw a single straight line, starting from the first letter to the last of $w$, crossing all letters of $w$ in the order that they appear in the word. This straight line should be parallel to either the sides or the diagonals of the grid. 