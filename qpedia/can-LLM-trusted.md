# Can LLMs be trusted?
    My short answer is No!

Trying to find out if a Nobel laureate has an advanced degree, I googled “Koichi Tanaka doctorate degree.” **Google AI** showed that Tanaka received a Ph.D. from UCLA and a bachelor of Engineering from the Tokyo Institute of Technology (see below, Koichi Tanaka from Google AI-search):

![Tanaka Google-AI](images/Tanaka-gglAI.png)

What’s going on? After scrolling down the search results, I noticed a LinkedIn page for another Koichi Tanaka, who has a Ph.D. from UCLA. Unfortunately, Google AI did not “know” that the **two** Koichi Tanakas were **not the same person** and mixed things up!

I then asked **ChatGPT (4o mini)** the question: “where Koichi Tanaka received doctorate degree.” what I got is as follows:

![Tanaka, ChatGPT: 1](images/Tanaka-4o.png)

ChatGPT got it all wrong (at least for my purpose; see below): wrong degree, wrong university (University of Tsukuba), and wrong contribution. I guess that ChatGPT might actually be “correct” in finding a Koichi Tanaka with a doctorate degree, but it failed to read my “mind” - I was looking for Koichi Tanaka, the Nobel laureate.

Maybe my prompt is not good. So I tried “did Koichi Tanaka receive doctorate degree.” This time, ChatGPT mentioned the Nobel prize, but again got both degree and university wrong:

![Tanaka, ChatGPT 2](images/Tanaka-4o_2.png)

To compare with my previous Google search, I finally tried “Koichi Tanaka doctorate degree” with ChatGPT. A third Koichi Tanaka was found with a doctorate degree from Tokyo Institute of Technology:

![Tanaka, ChatGPT 3](images/Tanaka-4o_3.png)

Unfortunately, the three different ChatGPT results seem rather random due to slight differences in the prompts. As a result, I have to conclude that **LLMs can not be trusted**, at least for the time being.

According to **Wikipedia**, the correct information is the following:

> “Koichi Tanaka (田中 耕一, Tanaka Kōichi, born August 3, 1959) is a Japanese electrical engineer who shared the Nobel Prize in Chemistry in 2002 for developing a novel method for mass spectrometric analyses of biological macromolecules with John Bennett Fenn and Kurt Wüthrich (the latter for work in NMR spectroscopy).”

![Tanaka Wikipedia](images/Tanaka-wiki.png)

## A catch-22 problem

As I understand them, LLMs train on text data, *learn* patterns, and then *predict* what comes next ranked by **probabilities**.

Philosophically or logically, with probabilities, there are uncertainties! **With uncertainties, we will never know whether the result of LLMs is correct unless we already know _the result_ or fact ahead of time**. In other words, we face a catch-22 problem with LLMs! I once posed this question to a student with a Ph.D. in computer science with a focus on LLMs, but did not get a satisfactory answer.

People can have the same names (especially so maybe in Asian countries), who may or may not be distinguishable by age, education, profession, or even sex. From the view of patterns, though, a name is just a text pattern. **Unless LLMs have a concept of complex associated patterns, they will fail with people’s names**.

Interestingly, though, Microsoft **Copilot** did give me the correct information:

![Tanaka Copilot](images/Tanaka-copolit.png)

(First posted on LinkedIn on November 2, 2024)