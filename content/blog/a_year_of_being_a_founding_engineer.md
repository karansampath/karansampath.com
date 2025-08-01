---
title: "A Year of Being a Founding Engineer"
date: 2025-07-02
author: "Karan Sampath"
---


The Valley glorifies the archetype of the founder: taking risks and making hard business decisions while developing a novel product. The fundamental founder role, however, is that of the messiah, since it is those around them make an idea's potential go kinetic. Being a founding engineer then is a unique choice to get on the ride with far less of the glory or upside, coming down to passion in the mission and / or the people. I chose that path a year ago by joining Aryn, an unstructured document intelligence seed stage startup based in Mountain View. I was the employee 10, and we are 15 now, with a number of pivots, successes, and failures in that intervening time. Here are three questions I found better answers to from the preceding year.

<p align="center">
  <img src="/images/blog/xkcd.png" alt='xkcd: "Everything" is a little ambitious.'>
</p>

## How should I best contribute?

A founding engineer is a diaphonous balance: you are both an employee but also an owner. The company critically depends on you, but possible (probable) failure of the organization is unlikely to be blamed on you. Contrary to popular belief, balancing this does not mean playing different roles, rather understanding how they mesh together.

As an engineer, my mantra is to write code that both speeds up the [REPL cycle](https://davidvujic.blogspot.com/2022/08/joyful-python-with-repl.html) and is understandable on different timescales. Different timescales can be broken down in multiple ways: let's use tomorrow, 3 weeks, and 1 year as useful benchmarks. You know almost exactly what the codebase looks like tomorrow, probably what it does 3 weeks from now, and very little about it 1 year from now. For tomorrow, you write code that is useful. For three weeks from now, you write code that is understandable. And for a year from now, you write code based on where you think the company is going, and often where it ought to go. These aren't necessarily tradeoffs, but writing quickly debuggable and understandable code is often incongruent with the higher level abstractions needed to make more widely accessible.

You might ask, how is this any different from a large company? It isn't, at least not *prima facie*. In a startup, each line of code you write has to be tinged with a gut understanding of its 'half-life'. How long do you expect it to go before it has to be changed or junked? The closer that number gets to 0 *{time_duration}*, the more you prioritize your code being solely optimized for the REPL cycle. Importantly, this is also a product decision, so it's worth having an opinion on the entire business justification before going ahead. When Aryn decided to deprioritize products, I saw lots of code that was painstakingly reviewed and rewritten get junked, making this approach all the more important. This applies for those around you as well. Reason through the entire chain of decisions, and if a practice doesn't make sense, call it out. A company that can't value that kind of communication is not worth it.

## How do I grow?

Personal growth in a seed stage startup is a double edged sword: you have the opportunity to accelerate faster than ever, but also not change at all. A startup has little to no performance reviews, few feedback opportunities, and little choice in what you work on. You often either surge on what the next customer needs or attack the ever growing list of improvements needed, with little ability to control much beyond that. You learn from your work, but there's an inevitable plateau that shows up, often earlier than expected.

In my experience, being proactive is the most important factor to growth. Proactive to the point of being shameless, ruthlessly reflective, and introspective at all times. Asking those around you that you respect for feedback regularly is essential. Make the breadth of inquiry supplement your future goals. I'm interested in exploring roles at the intersection of product and engineering, so I like to pepper GTM with questions about my interactions with customers and driving deadlines, while other engineers are more focused on my technical capability. The crux here is that a startup offers the ability for closer mentorship, but only if you reach for it. Create your own group of mentors and champions, they will push you forward in good times, and pull you up in bad ones.

In parallel, it is vital to navigate and choose projects that align closer to your interests. The typical goal to land your project is to find a potential business use case for it. But that's often not enough in a small startup: you need to find a client for it too. Find prospective customers, not necessarily to the point at which they will sign a deal, but till where there is a clear path to getting them. I advocated for a transition towards vision models in our OCR pipeline ([1](https://www.aryn.ai/post/summarize-images-in-documents-with-docparses-new-genai-feature), [2](https://www.aryn.ai/post/vision-ocr-and-new-text-extraction-settings-in-docparse)). To sell leadership on the need I used customer liked features that would be improved (summarizing images), and promised to take a tiered approach with customer validation at each step. Getting projects that you pitch and lead is crucial, and pushing that will help you supercharge your growth. This access to the whole funnel can only really happen in an early stage startup, so use that to your advantage.

## How does a team succeed?

Startups fail a lot, no suprises there. But what's the best way to avert that future? It's perhaps easier to answer what not to do. First, don't blame anyone. Even if there is a clear party at fault, and especially not if you think it is yourself. Blame is contagious, pollutes the working environment, encourages distrust, and discourages growth. When Aryn looked like it lost a large customer that I had worked on getting to success, I put the onus on myself. I was pushed back on, since deal collapses are often due to internal discussions out of one's control. This was validated after talking to them, and we've been able to pivot them into another product, ensuring they don't fall out of the funnel. Blame would have encouraged defeat earlier!                                                                                                                                           

On the flip side, getting to success comes from recognizing skills in one another and being honest about it. It's not useful to be intimidated, the longer you are in that state the less useful you will be. Spending time fixing communication gaps by sitting down together is useful; it may be initially harder to do, but will serve one well in the long run. An early stage company demands a large share of bluntness, so I've found allowing for that early in your working relationship to be very useful.

These are but a few learnings from this year, and I'm excited for what's in next year's list. If you have questions or are interested in chatting, I'd love to hear from you. I'm reachable at [me@karansampath.com](mailto:me@karansampath.com) or on [X](https://x.com/karan_sampath). 

If it wasn't clear, I'm glad that I chose this path.
