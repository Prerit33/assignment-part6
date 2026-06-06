# Prompt Engineering Portfolio
Name: [Prerit singh] \
Date: [06/06/26] \
LLM Used: [Gemini Pro]

## Part 1: Prompt Design & Iteration

### 1.1 Scenario A: Technical Explanation

#### Initial prompt 
"Explain how a neural network works to a 10-year-old."
#### Refined Prompt (Iteration 1)
"Explain how a neural network works to a 10-year-old. Use an analogy to make it easier to understand. Keep it under three paragraphs and avoid using any complicated words."

#### Refined Prompt (Iteration 2)
"Act as an enthusiastic science teacher. Explain how a neural network works to a 10-year-old. Use an analogy about trying to beat a difficult boss in a video game. Keep the response to exactly three short paragraphs. End the explanation with a fun fact about how making mistakes actually makes the AI smarter."

#### Final Output
Imagine you are playing a brand new video game, and you’ve just reached a super tough boss. The first time you fight it, you might run straight in and immediately get defeated. But you learned something, right? You learned that running straight in doesn't work! So, the next time, you try jumping. You survive a little longer, but you still lose. Every time you play, you remember what failed and try a new strategy until, finally, you figure out the exact combination of jumps and attacks to beat the boss!
A neural network is basically a computer program that learns exactly the same way you do when you play that game. Instead of a human programmer typing in all the answers, we just give the computer a goal—like recognizing a picture of a cat. At first, it just guesses randomly and gets it wrong. But every time it gets it wrong, it tweaks its strategy just a tiny bit. It looks at millions of pictures, trying over and over again, until it becomes a super-expert at spotting exactly what a cat looks like.
Fun Fact: Just like in your video game, a neural network needs to lose to get better! Every single mistake it makes is actually a vital clue that helps it level up its brain power. So, the more mistakes the AI makes in training, the smarter it is when it's finished!

### 1.1 Scenario B: Professional Email

#### Initial prompt 
"Write an email declining a job offer but say I still like the company."

#### Refined Prompt (Iteration 1)
Write a professional email declining a job offer for a Machine Learning Engineer position at TechCorp. Be polite and explain that the timing isn't right, but express that I am highly interested in their company and would love to stay in touch for future opportunities.

#### Refined Prompt (Iteration 2)
"Act as a professional in the tech industry. Write a polite, concise email to a hiring manager, declining a job offer for a Machine Learning Engineer position at TechCorp. Explain that while you were highly impressed by their team's work on predictive modeling and thoroughly enjoyed the interview process, you have accepted an offer that aligns slightly closer to your current focus on building end-to-end data processing pipelines."

#### Final Output
Dear Sarah, \
Thank you so much for offering me the Machine Learning Engineer position at TechCorp. I thoroughly enjoyed our conversations and was highly impressed by your team’s innovative work on predictive modeling.
After careful consideration, I must respectfully decline the offer. I have decided to accept another opportunity that aligns slightly closer to my current career focus on building end-to-end data processing pipelines. This was a difficult decision, as I think very highly of TechCorp and the direction your team is heading.
I would love to stay connected on LinkedIn and keep in touch. I will certainly be following TechCorp’s continued success and hope our paths might cross again in the future.
Thank you again for your time, the wonderful interview experience, and the generous offer. \
Best regards, \
[Your Name]

### 1.1 Scenario C: Creative Content

#### Initial prompt 
"Give me some marketing taglines for a new eco-friendly water bottle."

#### Refined Prompt (Iteration 1)
"Write 5 creative marketing taglines for a new brand of eco-friendly water bottles made from recycled ocean plastic. The target audience is active, outdoorsy millennials."

#### Refined Prompt (Iteration 2)
"Act as an expert advertising copywriter. Generate 3 short, punchy, and clever marketing taglines for a new premium water bottle brand made entirely from reclaimed ocean plastic. The target audience is environmentally conscious hikers and outdoor adventurers. Avoid overused clichés like 'save the planet' or 'go green'. For each tagline, provide a brief one-sentence rationale explaining why it resonates with the target audience."

#### Final Output
Here are three punchy and clever taglines for TideTrek, tailored to your outdoor-focused audience:

1. Reclaimed from the tide. Ready for the trail.
Rationale: This uses parallel structure to beautifully connect the origin of the recycled material directly to the customer's active use case.

2. Thirst for adventure. Starve the landfill.
Rationale: This plays on the concept of hydration by contrasting the consumer's active mindset with a strong, actionable stance against plastic waste.

3. The ocean's past, fueling your next peak.
Rationale: This highlights the transformative, premium nature of the product, turning a global problem (ocean plastic) into a personal asset for the adventurer.

### 1.2 Iteration Documentation
#### Scenario A: Technical Explanation

| Version | Prompt | What Changed | Why This Improved the Output |
| -------- | -------- | -------- | --------- |
| V1 | Explain how a neural network works to a 10-year-old.  | N/A | N/A |
| V2 | Write a professional email declining a job offer for a Machine Learning Engineer position at TechCorp. Be polite and explain that the timing isn't right, but express that I am highly interested in their company and would love to stay in touch for future opportunities. | Specified the role, company name, tone, and provided a basic reason for declining.| Provided necessary context to avoid a generic, fill-in-the-blank template, making the email usable for a specific situation. |
| V3 | Act as a professional in the tech industry. Write a polite, concise email to a hiring manager, declining a job offer for a Machine Learning Engineer position at TechCorp. Explain that while you were highly impressed by their team's work on predictive modeling and thoroughly enjoyed the interview process, you have accepted an offer that aligns slightly closer to your current focus on building end-to-end data processing pipelines. | Added a persona, recipient name, specific compliments, concrete reasoning regarding career focus, networking intent, and a strict word count.| Achieved a perfect balance of firmness and warmth. The specific details made the email highly realistic, tailored, and professional without being overly wordy.|

#### Scenario B: Professional Email

| Version | Prompt | What Changed | Why This Improved the Output |
| -------- | -------- | -------- | --------- |
| V1 | Write an email declining a job offer but say I still like the company. | N/A | N/A |
| V2 | Explain how a neural network works to a 10-year-old. Use an analogy to make it easier to understand. Keep it under three paragraphs and avoid using any complicated words. | Added a familiar analogy, a length constraint, and a negative constraint regarding vocabulary. | Grounded the abstract concept in an analogy children understand, preventing the use of overly technical jargon. |
| V3 | Act as an enthusiastic science teacher. Explain how a neural network works to a 10-year-old. Use an analogy about trying to beat a difficult boss in a video game. Keep the response to exactly three short paragraphs. End the explanation with a fun fact about how making mistakes actually makes the AI smarter. | Assigned a specific persona, refined the analogy to be more specific ("beating a boss"), tightened the length constraint, and added a specific concluding requirement. | Injected high energy and a tailored voice, making the output highly engaging, educational, and perfectly pitched for a child's comprehension. |

#### Scenario C: Creative Content

| Version | Prompt | What Changed | Why This Improved the Output |
| -------- | -------- | -------- | --------- |
| V1 | Give me some marketing taglines for a new eco-friendly water bottle. | N/A | N/A |
| V2 | Write 5 creative marketing taglines for a new brand of eco-friendly water bottles made from recycled ocean plastic. The target audience is active, outdoorsy millennials. | Specified the quantity, product material, and target demographic.| Replaced generic eco-clichés with targeted messaging relevant to a specific audience and product material. |
| V3 | Act as an expert advertising copywriter. Generate 3 short, punchy, and clever marketing taglines for a new premium water bottle brand made entirely from reclaimed ocean plastic. The target audience is environmentally conscious hikers and outdoor adventurers. Avoid overused clichés like 'save the planet' or 'go green'. For each tagline, provide a brief one-sentence rationale explaining why it resonates with the target audience. | Assigned a professional persona, named the brand, added negative constraints against clichés, refined the focus, and requested rationales. | Elevated the output to professional-grade copy by enforcing a specific brand voice, avoiding tired phrases, and forcing the LLM to justify its creative choices.|

### 1.3 Role and Context Analysis

#### Demonstration 1: Scenario B (Professional Email)
Role Assignment: "Act as a professional in the tech industry."

Context Setting: "Write a polite, concise email to a hiring manager named Sarah, declining a job offer for a Machine Learning Engineer position at TechCorp. Explain that while you were highly impressed by their team's work on predictive modeling... you have accepted an offer that aligns slightly closer to your current focus on building end-to-end data processing pipelines."

#### Demonstration 2: Scenario C (Creative Content)
Role Assignment: "Act as an expert advertising copywriter."

Context Setting: "...for 'TideTrek', a new premium water bottle brand made entirely from reclaimed ocean plastic. The target audience is environmentally conscious hikers and outdoor adventurers."

#### How Role and Context Improved the Outputs
Assigning a specific role instructs the LLM to adopt a targeted persona, instantly adjusting the tone, vocabulary, and stylistic nuances of the output to match professional expectations. Providing rich context grounds the model in a specific reality, preventing it from relying on generic, boilerplate responses or overused clichés. Together, these techniques constrain the model's vast knowledge base, forcing it to filter its generation through a highly specific lens. Ultimately, this combination results in tailored, high-quality outputs that require significantly less human editing because the AI understands not just what to write, but exactly how and for whom it is writing.

## Part 2: Temperature & Parameter Control

### 2.1 Temperature Experimentation

#### 1. The Prompt
Task chosen: Creating a short story opening (2-3 sentences)
Prompt used: "Write a 2-3 sentence opening for a science fiction short story about a detective who solves crimes by entering the memories of victims."

#### 2. & 3. Temperature Values and Complete Outputs

*Test 1: Low Temperature (0.2)*

Output: Detective Elara Vance attached the neural cables to her temples and initiated the memory sync. The victim's final moments played out in front of her like a sterile, high-definition recording. She scanned the digital landscape, looking for any logical clues to identify the killer before the memory faded.

*Test 2: Medium Temperature (0.7)*

Output: The memory dive always tasted faintly of ozone and panic as Jax plunged into the murdered man's final thoughts. He sifted through the chaotic, fading static of the victim's mind, desperately searching for a reflection of the killer's face. If he didn't find the anchor point soon, the psychological feedback loop would trap him there forever.

*Test 3: High Temperature (1.4*)

Output: Neon synapses fired backward, a screaming kaleidoscope of stolen yesterdays tearing at Inspector Thorne's cerebral shielding. He was drowning in a dead woman's Tuesday, hunting the phantom silhouette that had violently severed her timeline. Reality folded around him like wet origami as the victim's consciousness began to rot.

### 2.2 Analysis & Recommendations


| Feature | Low Temperature (0.2) | Medium Temperature (0.7) | High Temperature (1.4) |
| -------- | -------- | -------- | --------- |
| Vocabulary & Word Choice | Standard, literal, and functional (neural cables, recording, logical clues). | Descriptive and engaging with some sensory details (ozone and panic, chaotic static, anchor point). | Highly abstract, unconventional, and heavily stylized (neon synapses, screaming kaleidoscope, wet origami).|
| Tone | Clinical, straightforward, and procedural. | Tense, dramatic, and balanced.| Surreal, chaotic, and intensely vivid. |
| Predictability | Very predictable; reads exactly like a standard summary of the prompt's concept.| Moderately predictable but adds narrative flair and stakes (the "feedback loop").| Highly unpredictable; takes creative risks with metaphors and sensory descriptions.|
| Coherence | Extremely clear and easy to understand. | Clear and easy to follow while remaining creative. | Borderline disjointed; the heavy use of abstract imagery sacrifices some immediate clarity for artistic impact. |

## Part 3: Strategic Prompting Techniques
#### Option chosen: 
*Option A: Math/Logic Problem*

Problem: If a train travels 120 km in 2 hours, then stops for 30 minutes,
then travels another 90 km in 1.5 hours, what is its average speed for
the entire journey?

### 3.1 Chain-of-Thought Prompting

#### 1. Without Chain-of-Thought

Prompt:

"If a train travels 120 km in 2 hours, then stops for 30 minutes, then travels another 90 km in 1.5 hours, what is its average speed for the entire journey? Provide only the final answer.

LLM Output:

52.5 km/h

#### 2. With Chain-of-Thought

Prompt:

"If a train travels 120 km in 2 hours, then stops for 30 minutes, then travels another 90 km in 1.5 hours, what is its average speed for the entire journey? Let's solve this step by step." /
LLM Output: /
 <img width="702" height="373" alt="image" src="https://github.com/user-attachments/assets/007f9f44-80f1-4683-9ffe-d1e16e168262" />

#### Comparison
The zero-shot prompt without Chain-of-Thought (CoT) forces a direct answer, obscuring the underlying math and making it impossible to spot hidden logic errors if the AI were to get it wrong. CoT helps with complex reasoning because it forces the AI to unpack the problem into logical phases, effectively giving it more computational "space" (tokens) to process intermediate steps—like remembering to include the 30-minute stationary period in the total time constraint. However, one notable limitation of CoT is its verbosity and increased token cost; if you are running an automated script that just needs a raw numerical value to feed into another program, the extra text makes the output difficult to parse.


### 3.2 Few-Shot Prompting

## Part 4: Responsible AI & Limitations
### 4.1 Testing for Hallucinations
### 4.2 Testing for Bias
### 4.3 Limitations & Responsible Use
