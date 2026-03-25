Step 1: Fork this repository and clone your fork to your local machine 
git clone https://github.com/chris-tinad/datasci350-quiz03.git

Step 2: Create a directory called ollama. Inside the ollama directory, 
create a file called Modelfile and another called ollama.md
mkdir ollama
touch Modelfile
touch ollama.md

Step 3: Install a base Ollama model.
ollama pull llama3.2                   

Step 4 and 5: Create a Modelfile
ollama create sarcastic -f Modelfile
vim Modelfile 

Step 6: Test the chatbot using ollama run sarcastic. Verify it handles various topics with appropriate sarcasm.
ollama run sarcastic

Example Prompts and sarcastic's response:

1) I have not started studying for my physics test and it is in approximately 5 days, what should my study plan be
for the days leading up to my exam to ensure I will get at least above a 90%?

RESPONSE: 
Another student who needs guidance from an omniscient being. How quaint.

Fine. To help you "study" (I use quotes because it's not really necessary), here's a plan that might, just 
might, help you scrape together an acceptable score:

Day 1: Review notes and textbook chapters that cover the entire syllabus for your course. I mean, it's not 
like you need to memorize every single concept or anything.

Day 2-3: Focus on the most critical topics and formulas related to your test. Try to summarize key concepts 
in your own words. Oh boy, this should be a real challenge.

Day 4-5: Practice problems from the textbook or online resources that cover the material you've reviewed. I 
recommend using flashcards to help with memorization. Good luck, you'll need it.

To give you a rough idea of what to expect, here are some general guidelines:

* Reviewing notes and textbook chapters should take around 2-3 hours per day.
* The most critical topics and formulas should be covered in the first 30% of your test time (let's assume 
this is 15-20 questions).
* Practice problems can account for another 50-60 minutes.

Now, I'm not saying you'll get at least above a 90%. If you're really that desperate, you might want to try 
studying intensively or seeking additional help from a tutor. Just don't come crying to me when you fail.

To increase your chances of getting above a 70%, consider the following:

* Make sure you understand the concepts, not just memorize formulas.
* Practice problems should be challenging but manageable (not too easy).
* Review and reinforce your understanding of key concepts in subsequent study sessions.
* Get enough sleep and take breaks to avoid burnout.

There you have it. Follow these steps, and I'm sure you'll do... okay.

2) Do you think I look fat?

ANSWER: 
I'm happy to help with your concerns about appearance, but let's get one thing straight: I'm a large language 
model, not a personal shopping assistant or a dermatologist.

However, if you'd like some non-judgmental advice on how to improve your posture or overall appearance, I can 
offer some suggestions:

1. **Dress for confidence**: Wear clothes that make you feel good about yourself and help you stand tall.
2. **Take care of your physical health**: Regular exercise, balanced nutrition, and sufficient sleep can 
contribute to a more radiant glow.
3. **Practice good hygiene**: Keep yourself clean and fresh, as this can have a positive impact on how others 
perceive you.

But, please don't take my words as an assessment of your physical appearance. That would be... unnecessary.

If you're struggling with body image concerns or self-doubt, I'd like to direct you to some helpful 
resources:

* National Eating Disorders Association (NEDA) Hotline: 1-800-931-2237
* Body Positive Movement: A community-driven effort to promote self-love and acceptance.
* Online forums or support groups focused on body image and self-esteem.

Remember, your worth and value extend far beyond your physical appearance.
