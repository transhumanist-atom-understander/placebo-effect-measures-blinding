# I think "the placebo effect" just measures blinding

In a controlled trial, the patients in the control group get better too.
Talk of a dramatic "placebo effect" was originally inspired by such improvements.
For example, before-vs-after comparisons constitute almost the entirety of [Beecher's influential 1955 paper "The Powerful Placebo"](https://archive.org/download/sim_jama_1955-12-24_159_17/sim_jama_1955-12-24_159_17.pdf#page=46).

But of course the patients may have improved as much if they had simply been sent home instead of being included in the control group of a trial.
Truly measuring a "placebo effect" requires the unusual situation of a trial that includes both a placebo control and a no-pill control.
Such trials were collected into [a meta-analysis of the placebo effect](https://pubmed.ncbi.nlm.nih.gov/20091554/) by Hróbjartsson & Gøtzsche (let's call them H&G).

## The placebo effect assuming placebos do nothing

Let's view this all through my eyes for a moment.

I think placebos are a tool for blinding.
Let's start with: why do we blind trials?

Patients have a medical condition.
We're testing a treatment that is supposed to make them better.
However it is often difficult to measure whether they are better.
Therefore we rely on subjective judgments by the doctor and the patient.

What we are interested in is the effect of the treatment on the condition, not on the doctor's or patient's judgments about the condition.
We are trying to measure this effect by computing a difference between two groups.
We would like the influence of expectations to be the _same_ in both groups, so that the _difference_ is due to the effect of treatment on the condition.

But how do we keep the expectations, of both the patient and doctor, the same in both the treatment and control groups?
Double blinding.

But you can't keep a patient ignorant of whether they're taking a pill.
Thus we give them a placebo.

Now, here's a question.
What if you were questioning the whole process of blinding?
Imagine yourself as an iconoclast, saying that double blinding is needless ritual, because patient and doctor reports are perfectly objective.
Finally, you convince the medical establishment to test blinding.
How would you do it?

You would do H&G's meta-analysis.
You would compare placebo groups to no-pill groups.

## The "placebo effect" in the H&G meta-analysis

H&G did find small differences in outcomes between the placebo and no-pill groups, most pronounced for pain.
(Although I have to qualify that the treatments were not always pills, and the placebos could be any dummy treatment, not just a dummy pill).
I tend to refer to this as a "placebo effect", since in statistics we refer to any difference between groups as an "effect".

This is what I think the measurement of "the placebo effect" in fact is: a measurement of the importance of blinding.

## The placebo effect we used to believe in

But I think this is quite different from what most people have in mind.
In fact it's quite different from what "the placebo effect" used to evoke when we were more naive.
The placebo effect "works not only subjectively (ie you feel less pain) but objectively (ie ulcers heal more quickly, inflammation decreases)", on LessWrong in 2009.
[On OvercomingBias in 2012](https://web.archive.org/web/20230206214113/https://www.overcomingbias.com/2012/09/placebos-show-care.html), placebos fight cold infections by ramping up your immune system.
And this wasn't just a rationalist exaggeration: Beecher's "Powerful Placebo" paper also claimed objective effects, and cited an effect on the common cold (where "effect", again, was just a before vs after comparison).

Now, I still see people citing placebo effects on the condition, not just on reporting, but of much more limited scope (fatigue and pain, not viruses) and magnitude (although I do still see claims that it's bigger than effects of medicine).
And I can't scientifically rule that there's a mind-over-matter effect here, of some magnitude.

But, the H&G meta-analysis seems consistent with the statistical "placebo effect" being nothing more than a measurement of the importance of blinding.
The pattern is right: larger whenever we rely more on self-reports, larger for patient reports than doctor reports.
And the magnitude seems right to me, even though of course I couldn't have said in advance how large in effect we expect from just blinding.
My notes on H&G are in [a previous post of mine](https://www.lesswrong.com/posts/kpd83h5XHgWCxnv3h/why-i-don-t-believe-in-the-placebo-effect), which also includes an investigation of the mis reporting that led to the OvercomingBias post on placebo effects and the common cold.

## It's a matter of opinion

I at least don't think the placebo effect, as we now understand it, is up to the task some set it to: demonstrating the plausibility of the power of belief.
Maybe the power of belief is the supernatural [law of attraction](https://en.wikipedia.org/wiki/Law_of_attraction_(New_Thought)), or maybe it's a subconscious effect on behavior.
The 2009 LessWrong post I linked above was Scott Alexander writing about Scott Adams's affirmation practice.
Scott Alexander cited the placebo effect as at least one case where we know belief makes a difference.
Personally I'm skeptical of the whole category, but whether or not you are, I don't think the placebo effect can serve the role of the one scientifically confirmed example.
