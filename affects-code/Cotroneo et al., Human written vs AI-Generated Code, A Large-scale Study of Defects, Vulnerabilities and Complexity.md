#security #code-quality 

focus on the difference between human and ai code in 3 factors:
- Code defects
- code security analysis
- complexity


the dataset they use is called HMCorp, which was taken from another study, which curated it using 17k Github projects and 500K+ coding samples, by taking the "human" version of the function, reading the docstring and generating a GPT counterpart.
- the problem? who knows if the original wasn't gpt generated lol. they did generate the answers in april 2023, using gpt 3.5 turbo. ok perhaps in april 2023 (or before when they collected the samples), ai code wasnt as popular. 
- is the docstring detailed enough to give llms a chance to generate the right function? it would've been nice if unit tests can be created for the samples, and ensuring that the gpt generated code can pass the unit-test too.
- the dataset originally was used to distinguish between human and ChatGpt generated code. using it for code quality checks between human vs AI is extending its usage. 

im leaving the study wihtout much focus b/c the ai model used is gpt 3.5, which is pretty old now 

---

i think we need to look at case studies. thats the best step forward. the google case study by paradis was the closest we got to what we're looking for

case study is difficult b/c adopting ai is sometimes not a binary process. we can prob look at something for enterprise
