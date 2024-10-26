---
title: "Rank one approximation as a strategy for Wordle"
collection: publications
category: manuscripts
permalink: /publication/2022-04-11-Wordle Paper
excerpt: #'This paper is about the number 1. The number 2 is left for future work.'
date: 2022-04-11
venue: 'arXiv'
slidesurl: #'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/abs/2204.06324'
citation: #'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

This paper presents a mathematical method of playing the puzzle game Wordle. In Wordle, the player has six tries to guess a secret word. After each guess the player is told how their guess compares to the secret word. With the available information the player makes their next guess. This paper proposes combining a rank one approximation and latent semantic indexing to a matrix representing the list of all possible solutions. Rank one approximation finds the dominant eigenvector of a matrix of words, and latent semantic indexing reveals which word is closest to the dominant eigenvector. The word whose column vector is closest to the dominant eigenvector is chosen as the next guess. With this method the most representative word of the set of all possible solutions is selected. This paper describes how a word can be converted to a vector and the theory behind a rank one approximation and latent semantic indexing. This paper presents results demonstrating that with an initial guess of "SLATE" the method solves the puzzle in 4.04 guesses on average, with a success rate of 98.7%
