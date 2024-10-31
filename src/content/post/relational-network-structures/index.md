---
title: "Relational Network Structures"
description: "Relational network structures refer to the complex, interconnected systems that represent entities (nodes) and their interactions (edges) within a defined context."
publishDate: "08 August 2024"
tags: ["Art-of-war"]

---

## Relational Network Structures

When we think about relational networks the most obvious one is social graphs - according to wiki:

> The concept was originally called sociogram. The term was popularized at the Facebook F8 conference on May 24, 2007, when it was used to explain how the newly introduced Facebook Platform would take advantage of the relationships between individuals to offer a richer online experience

Social graphs are essentially just a database of our contacts when you add some UI/UX you get social apps like Facebook etc... I am severely using reductionism to make this point and by no means is my poor attempt at sarcasm shade at Zuck.

## Tiktok

But with the advent of Tiktok it has shown us that there are other networks just as poignant such as the Interest graph. Said so wonderdully by Deepak Nayal

> The great thing about interest graph is that, unlike a social graph, I do not need to know you in order to connect to you. This brings out the subtleties of human nature.

That led me to go further down looking to find more relational networks, network science is very interesting and so is the observed phenomenon of the preferential-attachment a direct result of power laws which states in any given network, new nodes or links tend to preferentially attach to nodes that already have the highest number of connections. And I just came to realisation the reason why these are called scale-free networks is a direct results of fractal behaviour - as regardless of the network size the ratio of nodes with a few connections to nodes with many connections remains constant = power law can be observed at any size of distribution.

## Types of graphs

And here's the table - by no means exhaustive 

| Network Structure       | Description                                                                                                                                                                                      |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Social Graph            | Represents relationships among individuals, where nodes are users and edges indicate connections or interactions. Useful for analyzing social dynamics and identifying influencers.               |
| Interest Graph          | Maps users' interests and preferences, linking users to their shared interests. Useful for personalized content recommendations and connecting like-minded individuals.                          |
| Affinity Graph          | Illustrates emotional connections between users based on shared experiences or sentiments. Ideal for creating resonant marketing strategies and enhancing engagement.                           |
| Behavioral Graph        | Captures user actions (e.g., posts, comments) with associated frequency and context. Useful for understanding engagement patterns and informing UX design.                                        |
| Communication Graph     | Shows communication patterns between users, focusing on interaction frequency and type. Analyzes information flow, identifying key communicators and influencers.                                |
| Transaction Graph       | Represents financial exchanges between users, with nodes as users and edges as transactions. Useful for analyzing e-commerce trends and detecting trusted users.                                 |
| Content Graph           | Displays relationships between content pieces and user interactions, such as likes or shares. Useful for content discovery, recommendations, and identifying trending topics.                    |
| Trust Graph             | Shows trust relationships among users, highlighting endorsements or trust scores. Ideal for reputation systems and enhancing credibility on social platforms.                                     |
| Knowledge Graph         | Maps interconnections among information entities, illustrating relationships between topics or concepts. Useful in educational settings and for research purposes.                              |
| Activity Graph          | Tracks user activity over time, monitoring engagement frequency and interaction types. Helps identify user retention trends and engagement, enabling targeted interventions.                     |
| Collaboration Graph     | Represents collaborative relationships, showing how users interact on projects or tasks. Useful for analyzing teamwork dynamics and identifying key contributors.                                |
| Influence Graph         | Highlights influence relationships, showing how users impact each other's opinions or behaviors. Useful for identifying influencers and analyzing trend propagation.                             |
| Event Graph             | Visualizes event participation, showing users who attend or engage in specific events. Useful for planning events and understanding attendee interests.                                          |
| Sentiment Graph         | Maps users' sentiments towards topics or entities, showing positive or negative opinions. Useful for analyzing public opinion and tailoring marketing strategies.                               |
| Demographic Graph       | Displays user demographics (age, location, gender) and connections between these groups. Helps target specific audiences and understand community diversity.                                    |
| Network Evolution Graph | Illustrates changes in user relationships over time, capturing growth or reduction in connections. Useful for studying social dynamics and community evolution.                                |
| Activity Stream Graph   | Shows a sequence of user interactions in timeline form, capturing engagement across the platform. Useful for analyzing user journeys and identifying opportunities for improvement.             |


One of the issues with tiktoks interest graph is the disconnection from your social graph. That begs the question is their a happy marriage or should it be a divorce/estranged relationship.

Thanks to o1 doing some consulting I think I have found a hybrid using the affinity graph:

The Affinity Graph shares the most overlap with both the Interest Graph and the Social Graph due to its focus on shared experiences, emotional connections, and preferences, bridging elements from both graphs:

## The Future

Interest Graph Overlap:

Like the Interest Graph, the Affinity Graph centers around common preferences and shared interests, connecting users based on what they enjoy or find relatable.
It goes a step further by emphasizing not just shared topics but the emotional bonds and resonances between users, creating a deeper layer of understanding about user alignment.
Social Graph Overlap:

Similar to the Social Graph, the Affinity Graph captures connections between individuals, but it differentiates by focusing specifically on the quality and intensity of these connections, highlighting emotional and value-based links rather than just interactions.
This overlap is especially useful for identifying close-knit groups or communities where shared values and strong emotional resonance are key, which is common in social contexts like fan communities or friendship circles.

In essence, the Affinity Graph combines interest-based connections with social bond quality, offering a nuanced view that incorporates elements of both social structure and shared passions.

But also lets not forget the experience graph