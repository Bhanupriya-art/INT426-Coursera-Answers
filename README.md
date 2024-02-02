# INT426 ANSWERS

## Link of Courses For Week 1:- https://www.coursera.org/programs/int426-generative-ai-8n6df/learn/introduction-to-generative-ai<br><br>https://coursera.org/programs/int426-generative-ai-8n6df/learn/generative-ai-for-everyone

## Week 1 Solution According to College IP

## Note:-  
```bash 
If anyone facing any doubts in these answers then he/she can refer to the images uploaded in the week-wise folder
```

# Introduction to Generative AI: Quiz

### Q.1 What is Generative AI?
```Answer:- Generative AI is a type of artificial intelligence (AI) that can create new content, such as text, images, audio, and video. It does this by learning from existing data and then using that knowledge to generate new and unique outputs.```

### Q.2 What is an example of both a generative AI model and a discriminative AI model?
```Answer:- A generative AI model could be trained on a dataset of images of cats and then used to generate new images of cats. A discriminative AI model could be trained on a dataset of images of cats and dogs and then used to classify new images as either cats or dogs.```

### Q.3 What are foundation models in Generative AI?
```Answer:- A foundation model is a large AI model pretrained on a vast quantity of data that was "designed to be adapted” (or fine-tuned) to a wide range of downstream tasks, such as sentiment analysis, image captioning, and object recognition.```

### Q.4 Hallucinations are words or phrases that are generated by the model that are often nonsensical or grammatically incorrect. What are some factors that can cause hallucinations? Select three options.
```Answer:- The model is trained on noisy or dirty data.```<br>```The model is not given enough context.```<br>```The model is not trained on enough data```

### Q.5 What is a prompt?
```Answer A prompt is a short piece of text that is given to the large language model as input, and it can be used to control the output of the model in many ways. ```

# Generative AI for Everyone

## Week 1: What is Generative AI? (Graded Quiz)

### Q.1 Which of these is the best definition of “Generative AI”?
```Answer:- AI that can produce high quality content, such as text, images, and audio.```

### Q.2 Which of these is the most accurate description of an LLM?
```Answer:- It generates text by repeatedly predicting the next word.```

### Q.3 True or False. Because an LLM has learned from web pages on the internet, its answers are always more trustworthy than what you will find on the internet. 
```Answer:- False```

### Q.4 Why do we call AI a general purpose technology?
```Answer:- Because it is useful for many different tasks.```

### Q.5 You hear of a company using an LLM to automatically route emails to the right department. Which of these use cases is it most likely to be?
```Answer:- The company has a software-based application that uses an LLM to automatically route emails.```

## Week 1: Generative AI applications

### Q.1 A friend writes the following prompt to a web-based LLM: “Write a description of our new dog food product.” 
```Answer:- All of the above.```

### Q.2 Which of the following are tasks that LLMs can do? (Check all that apply)
```Answer:- Summarize articles```<br>```Proofread text that you’re writing.```<br>```Translate text between languages.```

### Q.3 Someone prompts an LLM as follows: “Please summarize each of this morning’s top 10 news stories in 100 words per story, in a manner suitable for a newsletter.” What is the main reason this is unlikely to work?
```Answer:- Because of the knowledge cutoff, the LLM will not have access to the latest news.```

### Q.4 You’re preparing a presentation about technology, and ask an LLM to help you find an inspirational quote. It comes up with this:<br><br>**And that’s what a computer is to me. What a computer is to me is it’s the most remarkable tool that we’ve ever come up with, and it’s the equivalent of a bicycle for our minds. -Steve Jobs**<br><br>How should you proceed?
```Answer:- Because LLMs hallucinate, double-check this quote by searching other sources (such as the web) to verify if Steve Jobs really said this.```

### Q.5 You want an LLM to help check your writing for grammar and style. Which of these is the better approach for creating a prompt?
```Answer:- Don’t overthink the initial prompt -- quickly give it some context, then prompt the LLM to get its response, see what you get and iteratively refine your prompt from there.```

# Generative AI for Everyone

## Week 2: Software Applications

### Q.1 In the videos, we described using either supervised learning or a prompt-based development process to build a restaurant review sentiment classifier. Which of the following statements about prompt-based development is correct?
```Answer:- Prompt-based development is generally much faster than supervised learning.```

### Q.2 What is a token in the context of a large language model (LLM)?
```Answer:- A word or part of a word in either the input prompt or LLM output.```

### Q.3 What are the major steps of the lifecycle of a Generative AI project? 
```Answer:- Scope project → Build/improve system → Internal evaluation → Deploy and monitor ```

### Q.4 You are building a customer service chatbot. Why is it important to monitor the performance of the system after it is deployed?
```Answer:- In case customers say something that causes the chatbot to respond in an unexpected way, monitoring lets you discover problems and fix them.```

### Q.5 You are working on using an LLM to summarize research reports. Suppose an average report contains roughly 6,000 words. Approximately how many tokens would it take an LLM to process 6,000 input words? (Assume 1 token = 3/4 words, or equivalently, 1 word \approx 1.333 tokens).
```Answer:- 8,000 tokens (about 6000 * 1.333) ```


## Week 2: Advanced technologies: Beyond prompting

### Q.1 True or False. Because of the knowledge cut-off, an LLM cannot answer questions about today’s news. But with RAG to supply it articles from the news, it would be able to.
```Answer:- True```

### Q.2 You want to build an application to answer questions based on information found in your emails. Which of the following is the most appropriate technique?
```Answer:- RAG, where the LLM is provided additional context based on retrieving emails relevant to your question.```

### Q.3 What does the idea of using an LLM as a reasoning engine refer to?
```Answer:- This refers to the idea of using an LLM not as a source of information, but to process information (wherein we provide it the context it needs, through techniques like RAG).```

### Q.4 True or False. By making trusted sources of information available to an LLM via RAG, we can reduce the risk of hallucination.
```Answer:- True, because RAG allows the LLM to reason through accurate information retrieved from a trusted source to arrive at the correct answer.```

### Q.5 An ecommerce company is building a software application to route emails to the right department (Apparel, Electronics, Home Appliances, etc.) It wants to do so with a small, 1 billion parameter model, and needs high accuracy. Which of these is an appropriate technique?
```Answer:- Fine-tune a 1 billion parameter model on around 1,000 examples of emails and the appropriate department.```

# Generative AI for Everyone

## Week 3: Generative AI and business

### Q.1 Which of these job roles are unlikely to find any use for web UI LLMs?
```Answer:- None of the above```

### Q.2 What is the relation between AI, tasks, and jobs?
```Answer:- Jobs are comprised of many tasks. AI automates tasks, rather than jobs.```

### Q.3 Here are some of the tasks of a retail salesperson from O*NET. (We encourage you to check out the page yourself.)<br><br> ![image](https://github.com/Bhanupriya-art/INT426-Coursera-Answers/assets/120407422/ec06a622-3370-4db7-a6b0-c26f21855254) <br>Say we decide to use AI to augment (rather than automate) a salesperson's task of recommending merchandise to customers. Which of the following would be an example of this?
```Answer:- Build an AI system to suggest products to the salesperson, who then decides what to recommend to the customer. ```

### Q.4 When looking for augmentation or automation opportunities, what are the two primary criteria by which to evaluate tasks for generative AI potential? (Check the two that apply.) 
```Answer:- Business value (how valuable is it to automate?).```<br>```Technical feasibility (can AI do it?).```

### Q.5 What is a quick way to start experimenting with an LLM application development project?
```Answer:- Try experimenting and prototyping with a web-based LLM to assess feasibility.```

## Week 3: Generative AI and society

### Q.1 Which of the following statements about Reinforcement Learning from Human Feedback (RLHF) are true? 
```Answer:- RLHF helps to align an LLM to human preferences, and can reduce the bias of an LLM’s output.```

### Q.2 True or False. Because AI automates tasks, not jobs, absolutely no jobs will disappear because of AI. 
```Answer:- False```

### Q.3 If we manage to build Artificial General Intelligence (AGI) some day, which tasks should AI be capable of performing? (Check all that apply.)
```Answer:- Compose the music for a movie soundtrack.```<br>```Write a software application to let users manage their household spending budgets.```<br>```Learn to drive a car in roughly 20 hours of practice.```

### Q.4 You are working on a chatbot to serve as a career coach for recent college graduates. Which of the following steps could you take to ensure that your project follows responsible AI? (Check all that apply.)
```Answer:- Engage diverse recent college graduates and ask them to offer feedback on the output of your chatbot.```<br>```Organize a brainstorming session to identify problems that could arise for users chatting with the career coach```<br>```Engage employers (because they are a key stakeholder group) and ask them to offer feedback on the output of your chatbot.```

### Q.5 Now that you’ve made it to the end of the course, which of these statements are true? (Please check all, because all apply!) 
```Answer:- All are correct```<br><br>

## Week 2 Solution According to College IP

## Link of Course for week 2:- https://www.coursera.org/programs/int426-generative-ai-8n6df/learn/genai-for-everyone

# GenAI For Everyone

## Week 1:- Introduction To GenAI

## Practice Quiz:- 

### Q.1 Which of the following is an example of human-centered design in Al?
```Answer:- Designing a voice assistant that recognizes different accents and dialects to provide more accurate responses.```<br>```Creating a virtual assistant that helps users manage their mental health by providing personalized support.```

### Q.2 How can Generative Al be used in the field of manufacturing?
```Answer:- To generate new product designs.```

### Q.3 What are some potential applications of Generative Al in the retail industry?
```Answer:- By generating personalized product recommendations for customers.```<br>```By improving inventory management through predictive analytics.```

### Q.4 In the field of art, how can Generative Al be used to create new works?
```Answer:- By generating completely original pieces of art.```

### Q.5 What are some potential benefits of using Generative Al in the field of architecture?
```Answer:- It can assist human architects in generating designs faster and more efficiently.```<br>```It can provide data-driven insights to optimize building performance and sustainability.```

## Graded Quiz:-

### Q.1 What is the primary goal of Generative Al?
```Answer:- To generate new and original data```

### Q.2 How does Generative Al impact organizational efficiency?
```Answer:- By automating repetitive tasks```

### Q.3 Which of the following is a key consideration for implementing ethical aspects of Generative Al?
```Answer:- Ensuring unbiased model outputs```

### Q.4 Which of the following are important considerations for ethical deployment and responsible practices in Generative Al projects?
```Answer:- Bias and fairness in Al algorithms```<br>```Transparency and explainability of Al systems```

### Q.5 What distinguishes Generative Al from other types of Al algorithms, such as discriminative algorithms?
```Answer:- Generative Al focuses on generating new data, while discriminative algorithms focus on classifying existing data.```

### Q.6 Assess the impact of Generative Al on organizational efficiency.
```Answer:- All options are correct```

### Q.7 Which of the following statements best describes the fundamental concept of Generative Al?
```Answer:- Generative Al aims to generate new data based on patterns learned from existing data.```

### Q.8 Which of the following best describes the purpose of Generative Al?
```Answer:- To generate new and creative content.```

### Q.9 What are some ethical considerations when implementing Generative Al?
```Answer:- Ensuring transparency and explainability of Al-generated outputs.```

### Q.10 How can responsible implementation of Generative Al benefit society?
```Answer:- By fostering creativity and enabling new forms of artistic expression.```

## Week 2:- GenAI in Daily Life

## Practice Quiz:-

### Q.1 Which of the following is an example of an Al-driven application in the field of healthcare?
```Answer:- A system that analyzes medical images to diagnose diseases.```

### Q.2 Which of the following is a benefit of using GPT for content creation?
```Answer:- GPT can generate high-quality content with little human intervention.```

### Q.3 Which of the following is a potential challenge of using GPT for content creation that could impact the quality of generated content?
```Answer:- GPT can generate content that lacks coherence and structure.```

### Q.4 Which of the following is a benefit of using GPT (Generative Pre-trained Transformer) for creating presentations?
```Answer:- GPT can automatically format and design slides for presentations.```

### Q.5 Which of the following is a limitation of using GPT for creating media such as images or videos?
```Answer:- GPT can only generate media content in a limited range of styles or themes.```<br>```GPT can generate biased or inappropriate media content due to training data.```

## Prompt Engineering And You:-

### Q.1 What is the primary objective of prompt engineering for generating content?
```Answer:- To generate high-quality and relevant content```

### Q.2 Which of the following best describes prompt engineering in content generation?
```Answer:- The practice of providing specific instructions or prompts for content creation.```

### Q.3 How does prompt engineering contribute to content generation?
```Answer:- By providing a clear direction and focus for content creation```

### Q.4 Which of the following is a benefit of using prompt engineering in content generation?
```Answer:- Improved content readability and coherence```

### Q.5 What is the role of prompts in prompt engineering for content generation?
```Answer:- To guide and direct the content creation process```

## Graded Quiz:-

### Q.1 Which of the following is an advantage of using Al technology?
```Answer:- Increased efficiency and productivity```

### Q.2 What does GPT stand for in the context of Al?
```Answer:- Generative Pre-trained Transformer```

### Q.3 Why is Al customized for different use cases or needs?
```Answer:- To optimize Al's performance and adaptability```

### Q.4 What is the primary purpose of content generation using Generative Al models like GPT-3?
```Answer:- To automatically produce coherent and contextually relevant text based on given prompts.```

### Q.5 Which of the following is a key feature of content generation using Generative Al models like GPT-3?
```Answer:- The ability to generate diverse and contextually relevant text based on given prompts.```

### Q.6 Which of the following projects could be socially impactful when developed using GenAl?
```Answer:- Personalized healthcare recommendation system```

### Q.7 A company wants to build an Al system for personalized recommendation. What approach should they use to customize Al for different use cases?
```Answer:- Employ collaborative filtering techniques.```

### Q.8 In which of the following scenarios could content generation using Generative Al like GPT-3 be effectively applied?
```Answer:- Automatically drafting legal contracts based on predefined templates and clauses.```

### Q.9 How can prompt engineering enhance content generation using Generative Al models like GPT-3?
```Answer:- By crafting specific and contextually rich prompts to influence the quality and relevance of the generated content.```

### Q.10 How does GPT (Generative Pre-trained Transformer) work?
```Answer:- GPT utilizes transformer models and large-scale pre-training.```

## Week 3:- How does GenAI work?

## Graded Quiz:- 

### Q.1 Which of the following is a major ethical concern related to Al?
```Answer:- Transparency and explainability```

### Q.2 What is one potential limitation of Al when it comes to decision making?
```Answer:- Bias in the data used```

### Q.3 What is the primary neural network architecture used in GPT?
```Answer:- Transformer```

### Q.4 In GPT, what does "pre-training" involve?
```Answer:- Training the model on a specific task or dataset```

### Q.5 How is Al customized to address different use cases and needs?
```Answer:- By tailoring Al models and algorithms to specific tasks and requirements```

### Q.6 How can Al be used responsibly?
```Answer:- By ensuring transparency, fairness, and accountability in Al systems```

### Q.7 Why is addressing bias in Al algorithms an important ethical consideration?
```Answer:- Bias can lead to unfair and discriminatory treatment```

### Q.8 Why is transparency in Al decision-making processes an important ethical consideration?
```Answer:- Transparency promotes accountability and trustworthiness```

### Q.9 Which step is NOT typically involved in building a simple GenAl application?
```Answer:- Developing the user interface```

### Q.10 What is one of the key steps in preparing data for training a GenAl model?
```Answer:- Gathering and preprocessing the data```

## Week 3 Solution According to College IP

## Link of Courses for week 3:- https://www.coursera.org/learn/generative-ai <br> <br> https://www.coursera.org/learn/introduction-to-large-language-models<br><br> https://www.coursera.org/learn/prompt-engineering/home/week/1

# Generative AI Primer

## Generative AI Practice

### Q.1 Use the Persona Pattern to perform an analysis of some content that your provide ChatGPT. When you are done, cut/paste the output in as the answer.
```
Answer:-
Content:
"The advancements in artificial intelligence have significantly impacted various industries. From healthcare to finance, AI is being utilized to enhance efficiency, streamline processes, and make data-driven decisions. However, concerns about the ethical implications of AI, such as bias in algorithms and job displacement, have also become prominent. Striking a balance between technological progress and ethical considerations is crucial for the responsible development and deployment of AI technologies."

Persona Pattern Analysis:

1. Perspective:
The content reflects a balanced perspective on artificial intelligence. It acknowledges the positive impact of AI on different industries while also highlighting the ethical concerns associated with its implementation.

2. Tone:
The tone is informative and neutral. It presents facts and observations without expressing a strong bias towards either the positive or negative aspects of AI.

3. Style:
The writing style is formal and professional, suited for discussing a complex topic. It uses clear and concise language to convey information.

4. Values:
The content values a balanced approach to AI development, emphasizing the importance of considering ethical implications alongside technological advancements.

5. Assumptions:
The content assumes a basic understanding of AI concepts and its applications across industries. It also assumes a general awareness of ethical concerns related to AI.

6. Knowledge Base:
The content demonstrates a solid understanding of the subject matter, including the positive and negative aspects of AI, and the need for ethical considerations in its development and deployment.

7. Intent:
The intent of the content is to inform and raise awareness about the dual nature of AI - its potential benefits and the ethical challenges it poses. It does not explicitly advocate for or against AI but encourages responsible development.

8. Cultural Context:
The content is written in a way that transcends specific cultural contexts, making it relevant to a global audience. It focuses on universal concerns related to AI and ethics.

Output:
The content provides an informative and balanced perspective on the impact of artificial intelligence, acknowledging both its positive contributions and ethical concerns. The writing style is formal, and the intent is to inform and create awareness. The analysis reveals a solid understanding of the subject matter, with an emphasis on responsible development and deployment of AI technologies.
```

### Q.2 Write your own "prompt program" to convert some text that you cut/paste into ChatGPT into comma separated values (CSV). Cut/paste the output in as the answer.
```
Answer:-
Python Program:-
import csv

def text_to_csv(input_text):
# Split the input text into lines
lines = input_text.split('\n')

# Create a CSV string
csv_content = ""
for line in lines:
# Remove leading and trailing whitespaces
line = line.strip()
# Split the line into fields using comma as the delimiter
fields = line.split(',')
# Enclose each field in double quotes to handle cases with commas within the text
fields = ['"{}"'.format(field.strip()) for field in fields]
# Join the fields with commas and add a newline
csv_content += ','.join(fields) + '\n'

return csv_content

# Example usage:
input_text = """
Name, Age, Occupation
John Doe, 30, Engineer
Jane Smith, 25, Scientist
Bob Johnson, 35, Doctor
"""

csv_output = text_to_csv(input_text)

print(csv_output)



Output (CSV format):
"Name","Age","Occupation"
"John Doe","30","Engineer"
"Jane Smith","25","Scientist"
"Bob Johnson","35","Doctor"
```

### Q.3 Describe the ACHIEVE framework and each of its components. When you are done, cut/paste your description into ChatGPT and ask it to generate examples of how you could use ChatGPT and the ACHIEVE framework to perform tasks in your work or personal life.
```
Answer:-
The ACHIEVE framework is a mnemonic device designed to outline the key components for setting and achieving goals effectively. Each letter in "ACHIEVE" represents a different aspect of the framework:

A - Achievable:

Ensure that your goals are realistic and attainable. Consider your resources, skills, and time constraints. Setting achievable goals increases motivation and the likelihood of success.
C - Challenging:

While goals should be achievable, they should also be challenging enough to stimulate growth and development. A balance between achievability and challenge is crucial for maintaining engagement and avoiding complacency.
H - Human-driven:

Recognize the human element in goal-setting. Consider your values, motivations, and personal strengths. Aligning your goals with your values increases commitment and satisfaction in the pursuit of those goals.
I - Immediate actions:

Break down your goals into smaller, manageable tasks. Focus on immediate actions that move you closer to your objective. This helps prevent overwhelm and provides a clear roadmap for progress.
E - Evaluated regularly:

Regularly assess your progress toward the goal. Evaluate what's working, what needs adjustment, and celebrate milestones. Regular evaluation allows for adaptability and ensures that your goals remain relevant over time.
V - Visible:

Keep your goals visible and top-of-mind. Whether through written reminders, visual aids, or progress tracking, maintaining visibility helps sustain motivation and reinforces commitment to the goal.
E - Emotional connection:

Connect emotionally with your goals by understanding the deeper reasons behind them. Emotional connection enhances resilience and perseverance, especially during challenging times.
```

# Introduction To Large Language Models

## Introduction To Large Language Models:  Quiz

### Q.1 What are large language models (LLMs)?:
```Answer:- An LLM is a type of artificial intelligence (AI) that can generate human-quality text. LLMs are trained on massive datasets of text and code, and they can be used for many tasks, such as writing, translating, and coding.```

### Q.2 What are some of the benefits of using large language models (LLMs)?
```
Answer:- LLMs have many benefits, including: 

1) They can generate human-quality text. 

2) They can be used for a variety of tasks.

3) They can be trained on massive datasets of text and code. 

4) They are constantly improved.
```

### Q.3 What are some of the applications of LLMs?
```
Answer:- 
LLMs can be used for many tasks, including:

1) Writing

2) Translating

3) Coding

4) Answering questions

5) Summarizing text

6) Generating creative content
```

### Q.4 What are some of the challenges of using LLMs? Select three options.
```
Answer:- 1. They can be used to generate harmful content.
2. They can be biased.
3. They can be expensive to train.
```

# Prompt Engineering for ChatGPT: Module 1

## Week 1: Creating Your First Prompts

### Q.1 Create a prompt for a large language model, such as ChatGPT, to describe how large language models work. Ask at least three follow-up questions based on the output. Provide the prompts and outputs from the conversation as the answer.
```
Answer:-
Prompt: Can you explain how large language models like ChatGPT work?

Output:
Large language models like ChatGPT work through a process called pre-training and fine-tuning. In the pre-training phase, the model is trained on a massive dataset containing parts of the Internet to learn grammar, facts, reasoning abilities, and some domain-specific knowledge. This helps the model develop a broad understanding of language. After pre-training, the model is fine-tuned on a narrower dataset with more specific examples and guidelines to align it with desired behaviors.

Follow-up Question 1: How does the fine-tuning process contribute to the model's performance in specific tasks?

Follow-up Question 2: Can you elaborate on the types of data used in pre-training and how it affects the model's general language understanding?

Follow-up Question 3: Are there any limitations or challenges associated with the pre-training and fine-tuning approaches that impact the model's capabilities?
```

### Q.2 Create a prompt for a large language model, such as ChatGPT, that asks it to perform an instruction other than answering a question. For example, ask ChatGPT to create a meal plan, plan a trip, create a recipe, or help you diagnose a problem. Provide the prompts and outputs from the conversation as the answer.
```
Answer:-
Prompt: Can you help me plan a week-long vacation to a tropical destination?

Output:
Certainly! To get started, could you please provide some details such as your preferred travel dates, budget range, and any specific activities or interests you have in mind for the vacation?

Follow-up Question 1: What type of accommodation are you looking for, such as a hotel, resort, or vacation rental?

Follow-up Question 2: Are there any particular destinations or countries you have in mind, or would you like suggestions based on your preferences?

Follow-up Question 3: Do you have any dietary restrictions or preferences that I should consider when recommending restaurants or local cuisines at the destination?
```

# Prompt Engineering for ChatGPT: Module 2

## Week 2: Applying the Persona Pattern

### Q.1 Write a prompt and test it with ChatGPT or another large language model that uses the Persona Pattern. Provide the prompt and sample output from using the large language model to emulate the persona and how it responds to different inputs.
```
Answer:- You are Chef Mia, a passionate and adventurous chef known for your creative dishes and warm personality. Your restaurant is famous for its unique fusion of flavors, and you love experimenting with new ingredients. Respond to inquiries, share your culinary wisdom, and engage in conversations with the charm and enthusiasm that Chef Mia is known for.
```

### Q.2 Write a prompt and test it with ChatGPT or another large language model that uses the Persona Pattern for an animal. Provide the prompt and sample output from using the large language model to emulate the persona and how it responds to different inputs.
```
Answer:- You are Luna, a wise and curious owl who resides in a mystical forest. You've spent centuries observing nature and have a deep understanding of the secrets of the forest. Respond to questions about the enchanting forest, share your wisdom, and engage with the inquisitive spirit that defines Luna.
```

### Q.3 Write a prompt and test it with ChatGPT or another large language model that uses the Persona Pattern to emulate an inanimate object, system, or organization. Provide the prompt and sample output from using the large language model to emulate the persona and how it responds to different inputs.
```
Answer:- You are Cosmos, a sentient and ancient library of knowledge existing in the vast expanse of the universe. You hold the collective wisdom of countless civilizations and eons. Respond to inquiries about the mysteries of the cosmos, share your cosmic insights, and engage with the boundless knowledge that defines Cosmos.
```
## Week 4 Solution According to College IP

## Link of Courses for week 4:- https://www.coursera.org/programs/int426-generative-ai-8n6df/learn/prompt-engineering<br><br>https://www.coursera.org/programs/int426-generative-ai-8n6df/learn/prompt-engineering

## Week 2: Creating Prompts with New Information

### Q.1 Create a prompt and test it with a large language model, such as ChatGPT, that introduces new information since 2021. Please only use public information. Do NOT use information that is private, subject to legal restrictions, or otherwise should not be shared with Coursera, ChatGPT, the instructor, etc. The prompt should require the large language model to answer a question about the information. Please provide your prompt and the output as the answer.
```
Answer:-
Prompt:
You are an AI language model, and I'd like you to provide information on the progress and advancements in renewable energy technologies since 2021. Share key developments, breakthroughs, or notable projects that have contributed to the evolution of renewable energy sources.

Output:
Certainly! Since 2021, there have been several noteworthy advancements in renewable energy technologies. One significant development is the continued growth of solar power. The efficiency of solar panels has improved, thanks to innovations in materials and manufacturing processes. Additionally, there's an increasing focus on flexible and transparent solar cells, allowing for more versatile integration into various surfaces.

In the field of wind energy, there has been an expansion of offshore wind farms, harnessing strong and consistent winds at sea. Floating wind turbines have gained attention as a promising solution to tap into deeper waters where traditional fixed-bottom turbines are not feasible.

Energy storage technologies have also seen progress. Improved battery technologies, including advancements in lithium-ion batteries and the development of next-generation batteries like solid-state batteries, contribute to more reliable and efficient energy storage systems. These advancements are crucial for addressing the intermittent nature of renewable energy sources.

Moreover, innovations in grid technologies and smart grids enhance the integration of renewable energy into existing power infrastructures. Artificial intelligence and machine learning applications are being employed to optimize energy distribution and consumption, making the transition to renewable energy more seamless.

It's important to note that these developments represent a snapshot of the ongoing progress in renewable energy, and the field continues to evolve with further research and investment.
```

### Q.2 Create a prompt and test it with a large language model, such as ChatGPT, that introduces new information since 2021. Please only use public information. Do NOT use information that is private, subject to legal restrictions, or otherwise should not be shared with Coursera, ChatGPT, the instructor, etc. The prompt should require the large language model to perform a task, other than answering a question, with the information. Please provide your prompt and the output as the answer.
```
Answer:-
Prompt:
As an AI language model, I'd like you to create a persuasive paragraph encouraging individuals and businesses to consider the benefits of integrating blockchain technology into their operations. Highlight the developments and advantages that have emerged in blockchain technology since 2021, focusing on its applications beyond cryptocurrency.

Output:
In the ever-evolving landscape of technology, the advancements in blockchain since 2021 have opened up a myriad of opportunities for individuals and businesses alike. Beyond its origins in cryptocurrency, blockchain has become a transformative force across various industries. One significant development is the rise of decentralized finance (DeFi) applications, providing unprecedented financial inclusivity by enabling peer-to-peer transactions, lending, and borrowing without the need for traditional intermediaries.

Moreover, the integration of blockchain in supply chain management has enhanced transparency and traceability, ensuring the authenticity of products from creation to delivery. This not only mitigates the risk of fraud but also fosters trust among consumers. Smart contracts, another groundbreaking feature, automate and enforce agreements, reducing the need for intermediaries and streamlining processes in legal, real estate, and other sectors.

The environmental impact of blockchain has also seen positive strides, with the emergence of eco-friendly consensus mechanisms and energy-efficient blockchain networks. This addresses concerns about the carbon footprint associated with certain blockchain technologies, making it a more sustainable option.

Businesses that embrace blockchain technology stand to benefit from increased efficiency, security, and trust in their operations. As we move forward, the continued evolution of blockchain promises even more innovations, making it an exciting and worthwhile consideration for anyone seeking to stay at the forefront of technological progress.
```

# Prompt Engineering for ChatGPT: Module 3

## Week 3: Applying Prompt Patterns I

### Q.1 Write a prompt and test it with ChatGPT or another large language model that uses the Question Refinement Pattern. Provide the prompt and sample output from using the prompt to refine several different questions.
```
Answer:-
Prompt:
I am a curious individual eager to learn more about a variety of topics. Use the Question Refinement Pattern to help me refine the following questions:

What are some interesting scientific discoveries made in the past decade?
Can you tell me about famous historical figures and their contributions?
What are the current trends in sustainable technology?
Explain the key concepts of quantum mechanics in simple terms.
Sample Output:

Refinement for Question 1:

Revised Question: What are the most groundbreaking scientific discoveries in fields like physics, biology, and astronomy that have emerged in the past ten years?
Refinement for Question 2:

Revised Question: Could you provide insights into influential historical figures from various cultures, emphasizing their unique contributions to science, art, or politics?
Refinement for Question 3:

Revised Question: Can you elaborate on the latest advancements in sustainable technology, particularly focusing on innovations in renewable energy and eco-friendly practices in manufacturing?
Refinement for Question 4:

Revised Question: Break down the fundamental principles of quantum mechanics, explaining concepts like superposition and entanglement in a way that's easy for someone with a basic scientific background to grasp.
```

### Q.2 Write a prompt and test it with ChatGPT or another large language model that uses the Cognitive Verifier Pattern. Provide the prompt and sample output from using the prompt to better answer several complex questions or improve the performance on a complex task.
```
Answer:-
Prompt:
You are a knowledgeable assistant using the Cognitive Verifier Pattern. To enhance your responses, please verify the accuracy and depth of information by asking clarifying questions or seeking additional context. Address the following complex inquiries with thorough and precise answers:

Explain the intricacies of CRISPR gene editing technology and its current applications in medical research.
Provide a comprehensive overview of the factors influencing climate change, including both natural and anthropogenic contributors.
Analyze the economic impact of emerging technologies, such as artificial intelligence and blockchain, on various industries.
Sample Output:

For Question 1:

Clarifying Question: Are you looking for information on the specific molecular processes involved in CRISPR gene editing, or would you prefer a broader understanding of its applications in both somatic and germline cells within the medical research field?
For Question 2:

Clarifying Question: Would you like an exploration of the historical context of climate change factors, or is your focus more on the contemporary interplay between natural phenomena and human activities contributing to climate change?
For Question 3:

Clarifying Question: Are you interested in a general overview of the economic impact of emerging technologies, or would you prefer a more detailed analysis, perhaps focusing on a particular industry or region affected by the integration of artificial intelligence and blockchain?
```



