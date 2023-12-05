---
title: "Mastering Technical Knowledge"
subtitle: "Unleash the Power of Technical Learning: A Revolutionary Framework for Mastery, Efficiency, and Real-world Proficiency"
tags: ["4geeks", "4geeks-method"]
authors: ["alesanchezr"]
---

## Abstract

Today’s traditional teaching methods for achieving mastery and technical proficiency focus mainly on fundamentals and the theoretical aspects, **neglecting the importance of hands on and real life experience as well as the motivation and engagement in the learning process**. The system works to a certain degree but still suffers from increasing drop rates, decreasing enrollment rates while taking several years to graduate students in skills and technologies that drastically evolve year over year.

Bootcamps and other apps or websites have emerged as a possible solution with more fast-paced, engaging, hands on and interactive learning environments but they often **lack a scientific approach or framework to optimize learning efficacy**. They may not have the expertise to design and implement evidence-based and proven effective curriculum. 

By failing to provide a comprehensive and fast paced method to learning technical skills, we end up with a workforce that is not fully prepared, institutions that struggle to retain students, and companies that are hesitant to hire. The gap between junior and senior developers also widens, creating a bottleneck in the market. 

What is needed is a holistic approach that addresses both **motivation** and **time efficiency**, and implements a cost-effective solution that scales to thousands of users while remaining accessible to everyone.

In this paper, we propose a framework that incorporates a series 4 metrics to mathematically score environments with higher learning and time efficacy: [Memory Retention](#Memory-Retention), [Feedback Quality](#Feedback-Quality-and-Frequency), [Learning Mastery](#Incremental-Learning-or-Mastery-Learning) and [Motivation](#Motivation). Our proposed solution leverages cutting-edge technology and minimal human intervention to create a cost-effective approach to education that can be measured in real-time using these 4 metrics.

## Environmental Learning Efficacy

> ⚠️ Instead of focusing on assessing the student’s learning ability, we focus on assessing the environment’s learning potential.

We define environmental learning efficacy to the effectiveness of an educational institution to provide and environment, syllabus and tools that lead high learning efficacy and eventually to student’s technical proficiency.

![Learning Efficacy Formula (1).png](https://github.com/breatheco-de/knowledge-base/blob/main/images/learning-efficacy-formula.png?raw=true)

> 📖 A highly efficient learning environment leads to ideal learning outcomes.

## Memory Retention

$$
R(t) = I \times e^{-\frac{t}{S \times n}}
$$

> *The more time it passes without practice, the less your brain will retain.*

After receiving new information, the brain's medial temporal lobe can save that information in memory for a few days or weeks. But, without using methods such as spaced repetition or active recall, your brain cannot store that memory for long due to memory trace decay and interference – a process more commonly known as “forgetting.”

![ebbinghaus-forgetting-curve.jpg](https://github.com/breatheco-de/knowledge-base/blob/main/images/ebbinghaus-forgetting-curve.jpg?raw=true)

[Forgetting Curve²](#References)

| Name | Description |
| --- | --- |
| `I` represents the initial retention rate | How easy was it to understand at first? |
| `S` is the “stability factor” | It is influenced by internal factors like cognitive load, prior knowledge, emotional state, and external factors like complexity of materials, format and presentation style, practical applications, etc. |
| `n` is how many times during time window | How many times you will repeat and practice the content material during the time window. For example: n=3 will be 3 times over the course of 1 week. |
| `t` is the time window, | The time window has to remain consistent, if can be weeks or months, etc. For example: t=1 could mean “over one week”. The bigger the t the faster your memory will decay unless you increase stability and/or repetition. |

In a coding bootcamp where students practice daily with auto-graded exercises and projects but don't have exams, you can apply this formula to strategize the reinforcement of learning.

### **Practical Example:**

### Assumptions:

1. Let `I=1` (or 100%), assuming students fully understand a new coding concept when they first learn it.
2. Let *`S*=0.7` , assuming the stability and quality of the material to be 70%.
3. Let *`n*=3`, assuming a student revisits the concept 3 times after initial learning (perhaps in future projects or exercises) during the time `t` period.

### Application:

To keep the retention rate above a certain threshold, say 80%, you can find the time *`t`* at which *`R*(*t*)` falls below that threshold and schedule additional practice or review at or before that time.

$$
\text{Solve for } t \text{ in } 0.8 = e^{-\frac{t}{0.7 \times 3}}.
$$

Solving this equation yields:

$$
t \approx 1.65 \text{ days}
$$

With these parameters, you should schedule additional practice or review exercises around the 2nd day after the initial learning event to maintain a retention rate above 80%.

This way, the bootcamp can align its curriculum to proactively counteract the effects of the forgetting curve, ensuring that crucial concepts are reinforced before students are likely to have forgotten them.

### Stability (Quality) Factor when Learning Technical Skills

In the previous practical example, we assumed a Stability of `80%` . We should focus on achieving > 80% stability to provide the best possible learning environment.

In the context of learning to code, the stability factor *`S`* in a forgetting curve model could be influenced by various elements. These elements can be broadly categorized into internal factors related to the learner and external factors associated with the learning environment or content.

**Internal Factors**

1. **Prior Knowledge**: A learner with a strong foundational understanding of programming concepts might have a higher stability factor for new, related information.
2. **Cognitive Load**: Code that is easier to understand and well within the learner's cognitive capacity may be retained longer, leading to a higher *`S`*.
3. **Emotional State**: Stress, fatigue, or anxiety can impact the stability factor negatively.

**External Factors**

1. **Complexity of Material**: More complex or abstract code might have a lower stability factor, as it's harder to retain.
2. **Presentation Style**: Well-organized and clearly explained code could result in a higher stability factor.
3. **Practical Application**: Code that is immediately applied in a practical project may be retained better.
4. **Spacing and Repetition**: Employing spaced repetition techniques when learning code could increase *`S`*.
5. **Community and Collaborative Learning**: Interacting with others to solve coding problems can reinforce memory and increase *`S`*.

These are not the only factors, and their impact can be interrelated. For example, prior knowledge might interact with the complexity of the material to affect *`S`*. Similarly, the format of the material could impact cognitive load. While it's hard to quantify these factors into a single stability factor *`S`* in a precise manner, they provide a general guideline for what might influence how quickly or slowly coding knowledge decays over time.

### How Active Recall Increases Stability

> 📖 Active recall refers to reviewing materials in an active and self-directed manner.

Traditional learning materials mainly discourage self-direction.

Students need a high level of self-direction [to achieve higher dopamine levels, confidence and motivation³](#References).

Reducing cognitive load and improving the student's emotional state (very influential factors for stability). 

Also, active recall improves the presentation style of the materials and a more practical hands-on learning path, which also strongly impacts learning stability.

![Active Recall (1).png](https://github.com/breatheco-de/knowledge-base/blob/main/images/active-recall.png?raw=true)

Active learning, which involves engaging students in activities such as group work, problem-solving, and discussion, [can lead to increased motivation and learning efficacy⁴](#References) compared to more passive forms of learning such as lectures.

Active recall allows for a form of continuous, self-generated feedback. As learners review material, they gauge their understanding and performance, informing their learning path. This self-feedback loop can be incredibly powerful when paired with external feedback, making each round of external feedback more impactful.

### Using Spaced Repetition to Increase Memory Retention

> 📖 Spaced repetition refers to the practice of repeating and recalling information at specific time intervals.

Ideal exercises contain **high frequency** with a very **active** and **self directed** approach.

As a second priority, exercises containing medium frequency but still very self-directed are also recommended.

Lastly, exercises with some degree of social interaction are also encouraged as they [increase dopamine levels**¹**](#References),

![Spaced Repetition](https://github.com/breatheco-de/knowledge-base/blob/main/images/spaced-repetition.png?raw=true)

## Feedback Quality and Frequency

High-quality feedback should be frequent, clear, personalized, and relevant (related to current challenges the student is having); Providing actionable information that can be used by the learner to improve their performance or understanding.

| Frequency | Provide feedback multiple times a day. |
| --- | --- |
| Relevance | The moment student are having issues, asking questions or submitting assignments. |
| Clarity | Accessible, engaging formats and syntax that the student can understand addressing specific topics, exercises, assignments, lines of code, etc. |
| Personal | Addresses the learner's specific struggles, at the specific moment its needed |

By properly implementing frequent “micro-feedbacks” we can address frequency, personalization and relevance all at once, leaving Clarity to be the most challenging factor. We describe the concept of micro-feedbacks better in the next section.

### Micro Feedbacks

> 🔥 Giving feedback very often achieves personalization, relevance, and frequency at once.

Micro feedbacks are short, immediate responses given to learners to offer quick corrections, affirmations, or tips. Because they are immediate and frequent, they allow for high levels of personalization.

If the implementation of micro-feedbacks **ensures a consistent level of high personalization**, then it's reasonable to treat personalization as a constant and remove it from the quality equation. Under this assumption, the personalized nature of the learning process is embedded within the micro-feedbacks, making a separate term for personalization redundant.

> *With micro-feedbacks, giving relevan and personalized feedback is not longer a concern. 
Its a given.*

The real-time nature of micro-feedback allows for a granular focus on individual tasks or lines of code, **making it highly relevant** to what the student is working on at any given moment. It can guide the learner toward best practices and correct misunderstandings or mistakes that might otherwise propagate into larger issues.

$$
S = \text{Clarity} \times \log(1 + n(t))
$$

The formula aims to quantify the stability of a learner's understanding or skill level based on two key factors: the clarity of the feedback they receive and the frequency of their interactions with the learning system.

- **Clarity**: This is a measure of how well the feedback is understood by the learner. It could range from 0 to 1, with 1 being perfectly clear feedback.
- **`log(1+*n*(*t*))`**: This term accounts for the frequency of interactions that include feedback *`n*(*t*)`, at a given time *`t`*. The logarithm helps to dampen the effect of very high frequencies and makes the relationship non-linear.

### **Practical Example in a Coding Bootcamp:**

Let's consider a coding bootcamp that uses automated systems to provide immediate feedback on code exercises. Students complete coding tasks daily, and the system automatically checks their submissions.

- **Clarity**: The bootcamp has invested in generating high-quality, automated feedback. After assessing it, we decide that its Clarity score is 0.9.
- **Interactions *`n*(*t*)`**: During the first week, a particular student submits code for automated checking 15 times.

Using the formula:

$$
S = \text{Clarity} \times \log(1 + n(t))
$$

$$
S = 0.9 \times \log(1 + 15) = 0.9 \times \log(16) = 0.9 \times 1.204 = 1.084
$$

This value would suggest that the combination of clear feedback and frequent interaction has led to a relatively stable understanding of the material for this student. In this bootcamp setting, such a high stability score implies that the student is likely retaining the material well, assuming the feedback is effective and relevant to the tasks.

## Incremental Learning or Mastery Learning

Mastery learning is fundamentally built on cycles of instruction and feedback, focusing on ensuring that each learner attains a thorough understanding before progressing.

> 💡 Mastery learning implements frequent assessments, but we have decided to use feedback as a replacement for assessments as it avoids scenarios were students may get discouraged by assessments results.

The concept of "mastery" in the context of mastery learning is generally not defined strictly by the percentage of material retained. Instead, mastery often refers to the ability to apply knowledge or skills consistently, accurately, and independently in relevant contexts. It's about functional competence and deep understanding rather than just retention of information.

In our version of mastery learning, frequent feedback is used to identify areas where a student has not yet achieved mastery so that they can focus on those areas in subsequent cycles of instruction and practice. Self-directed active recall can augment this process by helping students identify gaps in their understanding.

## Motivation

Learner motivation can be defined as the degree of willingness, drive, and interest that an individual has to engage in and persist with learning activities.

![Motivation (1).png](https://github.com/breatheco-de/knowledge-base/blob/main/images/motivation.png?raw=true)


## References

1. "Interpersonal relationships and learning: the influence of social structure on attitudes, behaviors, and learning outcomes" by Johnson and Johnson (in Advances in Learning and Behavioral Disabilities, 1994)
2. Forgetting Curve by [Hermann Ebbinghaus.](https://en.wikipedia.org/wiki/Hermann_Ebbinghaus)
3.  "The Relationship Between Self-Directed Learning and Employment and Life Satisfaction Among Undergraduates, Graduates, and Alumni” by Reio and Callahan, 2004.
4. “Active learning increases student performance in science, engineering, and mathematics. Proceedings of the National Academy of Sciences” by Freeman, S., Eddy, S. L., McDonough, M., Smith, M. K., Okoroafor, N., Jordt, H., & Wenderoth, M. P. (2014)
