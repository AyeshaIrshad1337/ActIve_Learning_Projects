---
title: "Traditional Programming vs. Machine Learning: Navigating the Paradigm Shift"
seoTitle: "Traditional Programming vs. Machine Learning: Choosing Paths in Tech"
seoDescription: "Explore the differences between traditional programming and machine learning, uncovering their strengths, applications, and implications for the future."
datePublished: Thu Aug 24 2023 13:16:29 GMT+0000 (Coordinated Universal Time)
cuid: cllp6tmqq000e09jy6bsmbiot
slug: traditional-programming-vs-machine-learning-navigating-the-paradigm-shift
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/n6B49lTx7NM/upload/fd244ca33b96f61a1cfcc7b3d8fd96ab.jpeg
tags: programming-blogs, technology, machine-learning, problem-solving-skills, programming-paradigm

---

In the ever-evolving landscape of technology, two distinct approaches have emerged as powerful tools for problem-solving: traditional programming and machine learning. Each approach brings its unique strengths and weaknesses to the table, often leading to discussions about their applications, efficiency and potential for shaping the future of computing.

## Programming vs. Machine Learning

### Traditional Programming

Here's an example of the difference between machine learning ( or simply 'ML') and regular programming. Imagine building a program that plays video games.

With traditional programming that program might look something like this :

```python
enemy = get_nearest_enemy()
if enemy.distance() < 100 :
    decelerate()
    if enemy.is_shooting():
        raise_shield()
    else:
        if health() > 0.25:
            shoot()
        else:
            rotate_away_from(enemy)
else:
# ..... a lot more code
```

... and so on. Most of the code would be a big collection of if.. else statements mixed with imperative commands such as shoot()

Granted, modern language gives us the means to replace those ugly nested ifs with more pleasant constructs - polymorphism, pattern matching or event-driven. The core idea of programming, however, stays the same: tell the computer what to look for, and you tell it what to do. You must list every single condition and define every action.

### Flaws of Traditional Programming:

The approach served us well but it has a few flaws:

1. You must be exhaustive. You can imagine writing dozens of if..else statements that you have to cover for video games. Even in structured domains like accounting it's hard to cover all special cases, Good Luck with listing every possible special case in complex a domain.
    
2. Even if you could list somehow all those decisions, you'd have to know how to take them in the first place. That's the second limitation of programming and a showstopper in some domains. For example, take a computer vision task like our original problem: Identifying pneumonia in chest scans. We don't know how a human radiologist recognizes pneumonia. Yes, we have a high-level idea of it, like: "the radiologist looks for opaque areas," However, we don't know how the radiologist's brain recognizes and evaluates an opaque area. In some cases, the expert herself cannot tell you how she came to a diagnosis, except for a rather vague: "I know by experience that pneumonia doesn't look like this." Since we don't know how those decisions happen, we cannot instruct a computer to take them. That is a problem shared by typically human tasks, such as tasting beer or understanding a sentence
    

### machine learning

Machine Learning, On the other hand, turns traditional programming on its head: instead of giving instructions to a computer, ML is about giving data to the computer and asking it to figure out what to do:

![2.3 Terminology | Interpretable Machine Learning](https://christophm.github.io/interpretable-ml-book/images/programing-ml.png align="left")

The idea of a computer "figuring out" anything sounds like wishful thinking, but there are a few different ways to make it happen. In case you're wondering, all of them still require running code. That code, however, isn't a step-by-step procedure to solve the problem, like traditional programming. Instead, the code in machine learning tells the computer how to crunch the data, so that the computer can solve the problem by itself.

As an example, here is one way that a computer can figure out how to play a video game. Imagine an algorithm that learns how to play by trial and error. It starts by giving random commands: shoot, decelerate, rotate, and so on. If those commands lead to success, such as a higher score, the algorithm remembers this experience. If they lead to failure such as death, the algorithm also takes note. At the same time, it also takes note of the state of the game: where are the enemies, the obstacles, and the power-ups? How much health do we have? and so on.

From then on, whenever it encounters a similar game state, the algorithm is a bit more likely to attempt the successful actions than the unsuccessful ones. After many cycles of trial and error, such a program would become a competent player. In 2013, a system using this approach reached superhuman skills in a bunch of old Atari games.

This style of ML is called reinforcement learning. Reinforcement learning works pretty much like dog training: good behavior is rewarded so that the dog does more of it.

( I also tried the same approach with my cat but I failed )

# Conclusion

In the dynamic realm of technology, the divergence between traditional programming and machine learning reveals two distinct paths to solving complex problems. Traditional programming, with its explicit instructions and deterministic nature, offers control and precision, ideal for scenarios where rules are well-defined. On the other hand, machine learning's data-driven approach, akin to training a curious mind, empowers computers to learn from examples and adapt to changing environments. As these two paradigms continue to evolve, they merge in fascinating ways, propelling innovation and opening doors to new possibilities. While each approach boasts its strengths and challenges, their synergy underscores a pivotal truth: the marriage of human ingenuity and computational prowess reshapes the landscape of problem-solving, promising a future where both programming and machine learning play vital roles in shaping our technological horizons.