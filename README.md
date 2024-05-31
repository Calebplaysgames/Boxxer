Boxxer © 2024 by Caleb Ray is licensed under CC BY-NC-SA 4.0 

Boxxer is an AI Chatbot & Assistant that I am attempting to put on the level of ChatGPT
Altho Chatgpt can write essays, my chatbot is more of an assistant and I am attempting to teach it mathematics, and all kinds of stuff.
Boxxer does not have access to google or the internet, so unlike chatgpt being able to add its own answers and questions, mine has to be human taught.
my goal is to add not just "question" and "answer" but also "type".

"type" would be so that it can categorize stuff to come up with a generalized answer based on other knowledge.

Right now it uses a confidence level to tell if it needs an answer input or not, it is set to .7 cause it was being a little wierd with the words "you" and "im"
so when you put "who are you" but it knew the term "im happy" it would overlap and it would tell you its happy instead of boxxer, but with .7 I havent ran into the issue yet.
.7 = 70% confidence
if it happens to not have any answer, itll just readout for you to tell it the answer to what your question was.
Questions arent actually just questions but their just the thing the you tell it. so if you say "hello" then the answer back should be "hello" and you tell it, but
it seems it starts filling its own answers in after a while, and its not even deep learning level.

Plans:
- Multiple Languages
- Internet Based Uploading (Optional, so there would be 2 versions of boxxer, Internet, and not internet
  - Internet version would only upload the .json file to the cloud and add it to the primary .json file so that next time it gets updated, it has a bigger list of answers.
- "type" in json so that if there are general greetings, and you tell it "hello" but it doesnt know the answer you can tell it "Greeting" and itll just assign hello, with all the other greetings,
- "emotion" in json, words automatically assign to "neutral" but if it is not sure, then itll ask for the emotion between "angry" "joyful" "sad" "surprised" "crazy" "anxious" or "Disgusted".
- Use existing words in a sentance that it has seen before to level out the grounds, so if you say "wow you know a lot" it can identify "know a lot" and you can tell it "have a lot of knowledge" and itll be able to add that with another answer like 
"I see you are surprised that I have a lot of knowledge"

I honestly dont know where to begin to make it ask the more complicated questions like question types, so if you know how to add more, shoot me a message on discord "JustCaleb" or username "pineapplequartz"
