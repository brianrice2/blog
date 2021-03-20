---
toc: false
layout: post
description: 
categories: [healthcare]
title: AI in Healthcare
---

My dad's experience with skin cancer has made me interested in the intersection of AI and healthcare - how can we take advantage of all the data and analytics at our disposal in order to improve the wellness for the people around us?

Skin cancer is the most prevalent type of cancer in the United States<sup>[1](https://www.aad.org/media/stats-skin-cancer)</sup>, yet much of the country does not have reliable access to dermatologists. These barriers can come in a variety of forms - financial, geographical, cultural.

Financial barriers may be the most common, but also the hardest to resolve outside of broad policy changes. Three in four Americans live paycheck-to-paycheck<sup>[2](http://press.careerbuilder.com/2017-08-24-Living-Paycheck-to-Paycheck-is-a-Way-of-Life-for-Majority-of-U-S-Workers-According-to-New-CareerBuilder-Survey)</sup>, and copays and cost of treatments not covered by insurance present a significant enough financial setback that many individuals simply avoid checkups in the first place. To make things worse, minority groups are typically paid less and [their symptoms are taken less seriously by medical professionals](https://www.health.harvard.edu/blog/racism-discrimination-health-care-providers-patients-2017011611015). Karla's experiences detailed below happen a lot more frequently than many notice ([thread](https://twitter.com/karlitaliliana/status/1260761171717582848)):

> I was hospitalized last week for a very accelerated heart rate, very low BP, and cycling oxygen levels. And my entire experience at Alameda hospital was of one of being punished for being “insubordinate”. &mdash; Karla Monterroso (\@karlitaliliana)

There are some actual reasons why skin lesions may be harder to detect on darker skin. Most reasons are not those. I like this quote from [Hardeman, Medina, and Kozhimannil](https://www.nejm.org/doi/full/10.1056/NEJMp1609535#t=article):

> Most physicians are not explicitly racist and are committed to treating all patients equally. However, they operate in an inherently racist system...Structural racism, the systems-level factors related to, yet distinct from, interpersonal racism, leads to increased rates of premature death and reduced levels of overall health and well-being.

A good goal, which is entirely unoriginal, is fair and accessible healthcare for everyone. But after an explosion of data and advances in machine learning, we may finally be able to make that happen. It will take a long time and a lot of careful consideration and hard work, but it can impact so many people around the globe.

AI is in a unique position to transform healthcare, but there are a lot of challenges to consider:

- Race can be treated as a restricted feature during training, preventing models from automatically associating race with certain levels of care or health outcomes. However, existing systematic biases in data will likely be very difficult to separate from the any collected data. White patients often make up a disproportionately high number of samples, and [skin lesions are particularly difficult to detect in skin of color](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2757062/).

- Doctors are notoriously over-worked, with an average visit outlasted by the clerical work doctors must complete afterward. AI can help on both fronts:
    - Virtual assistants can translate a doctor's verbal descriptions in real time into formatted notes. See: [Suki](https://www.suki.ai/)
    - A preliminary round of AI-based screenings can provide an initial opinion and highlight particularly informative areas that guided its decision. Models should be highly [sensitive](https://en.wikipedia.org/wiki/Sensitivity_and_specificity), since a patient's case can be easily passed off to a doctor or specialist for further review rather than risking many false negatives.
    - Interestingly, American culture may also be a factor: working in a society which so greatly values independce, doctors in the United States are more reluctant to partner with an AI system than in other countries like India.

In whatever capacity AI can be reasonably, safely, and effectively implemented, the focus should be on worker *assistance* rather than replacement. Deep learning systems are highly sophisticated by historical standards, but can still be fooled by adversarial and out-of-distribution examples. Holding out for a perfect, state-of-the-art system will in all likelihood never be widely adopted - [DeepMind is not our role model here](https://www.forbes.com/sites/samshead/2019/08/07/deepmind-losses-soared-to-570-million-in-2018/#7d721ca23504). But there is so much to gain - we may as well give it a shot.
