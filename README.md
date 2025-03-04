# AI for Web Development Students

## 🚀 Lesson Overview  
In this lesson, students will learn how to use AI as a **valuable tool** in their bootcamp journey while avoiding over-reliance. They will gain **practical skills in prompt engineering, AI-assisted coding, debugging, testing, and GPT customization**.  

Lesson Objectives:  
- Use AI **pragmatically** without becoming dependent on it.  
- Understand **how to prompt AI effectively** for optimal results.  
- Be able to **design custom GPTs** to fit their workflow.  
- Recognize when AI-generated answers **are suboptimal**.  
- Use AI to **write and improve tests** for their code.  
- Follow a **time-boxed problem-solving** approach before resorting to AI.  
- Compare and experiment with **different GPTs** to find the best fit.  
- Use AI to **generate large data sets** for your projects. 

---

## 📌 Why AI Matters for Web Developers  
AI is revolutionizing software development by enhancing productivity, automating repetitive tasks, and offering intelligent assistance. However, **AI should complement, not replace, fundamental development skills**.  

### **🤔 When Should You Use AI?**  
| Scenario | Use AI? |
|----------|--------|
| Understanding a new concept | ✅ Yes, for quick explanations |
| Writing boilerplate code | ✅ Yes, to speed up development. But be mindful in the begining, as you are learning what "boilerplate" means. |
| Debugging an error message | ✅ Yes, but verify the solution |
| Writing critical project code | ❌ No, AI may generate insecure code and you might not know if it's halucinating |
| Learning a new framework | ❌ No, read official docs instead. AI can provide out of date information. Always check the official docs for latest framework details. |
| Fixing a bug you don't understand | ❌ No, first investigate yourself, check Stack Overflow for people who had the same exact issue. |

---

## 🎯 Key Topics  

### **1️⃣ AI as an Augmentation Tool, Not a Crutch**  
- AI **accelerates** coding but should not replace **core problem-solving skills**.  
- Developers must **understand and validate AI-generated code** before using it.  
- AI should be used **alongside** documentation, Stack Overflow, and human mentors.  

📌 **Exercise (5 min):**  
- Ask AI to generate code for a simple task.  
- Analyze the output: Does it follow best practices? Is it efficient?
- Share your prompt in Slack so that the class can review the prompts together.

---

### **2️⃣ Prompt Engineering for Developers**  
- Writing **clear, specific, and detailed prompts** leads to better AI responses.  
- Use **step-by-step instructions** in your prompts for complex queries.  
- Example:  

  ❌ **Bad Prompt:** "Write a login system."  
  ✅ **Good Prompt:** "Write a secure login system using Express.js and JWT authentication. Include input validation and error handling."  

📌 **Exercise (8 min)::**  
- Compare AI responses(use at least 2 GPTs) to vague vs. detailed prompts.  
- Refine prompts to get **more accurate and useful** results. Take your first prompt and improve it. Compare the results.

---
<!-- TODO: Check if custom GPT options exist for non-paying accounts -->
### **3️⃣ Building & Customizing Your Own GPTs**  
- Students should **explore different GPT models** to find the best fit for their workflow.  
- Custom GPTs can be designed for **specific tasks** (e.g., AI for debugging, AI for refactoring code).  
- Tools like OpenAI’s API and ChatGPT Custom Instructions allow developers to **fine-tune their own AI assistants**.  

📌 **Exercise (10 min):**  
- Research and compare different GPT models (ChatGPT, Claude, Gemini, etc.).  
- In Slack, tell us about their differences.
- Create a custom GPT tailored for a web development task. Show us your prompt.  

---

### **4️⃣ Recognizing When AI Gives a Bad Answer**  
- AI can generate **incorrect, insecure, or outdated** code.  
- Always **verify AI’s answers** against documentation or best practices.  
- Example:  
  - AI-generated code may **miss edge cases** or use **deprecated functions**.  

📌 **Exercise (5 min):**  
- Ask AI to write a function, then review it for errors or inefficiencies.  
- Discuss how to **improve and refactor** AI-generated code.  

---

### **5️⃣ AI for Writing & Testing Code**  
- AI can generate **unit tests** using pure JS, or frameworks like Jest and Mocha.  
- Example prompt:  
  - “Write assertion unit tests for this function that validates a password input”  
- AI-generated tests **must be reviewed** for correctness and completeness.  

📌 **Exercise (15 min):**  
- Use AI to generate unit tests for one of your previous labs. Use `console.assert()` as a testing method. 
- See if you can learn(using AI) how to run the tests and identify **gaps or improvements** using AI.  

---

### **6️⃣ The 15-Minute Rule: When to Ask AI for Help**  
- **Time-boxing problems** prevents over-reliance on AI.  
- Follow this workflow:  

  1️⃣ Spend **15 minutes** trying to solve the problem yourself.  
  2️⃣ Search Google (Stack Overflow, MDN, official docs).  
  3️⃣ Ask a **teacher or mentor** for help.  
  4️⃣ If still stuck, **ask AI**, but verify its solution.  

📌 **Homework Exercise:**  
- Apply the **15-minute rule** to a coding challenge this week before using AI.  
- Reflect on whether AI provided the best solution. 
- Share on Slack when you do that and how it went. 

---

### **7️⃣ Use AI to generate large data sets** that would take way too long to generate yourself.  
- Previously we would either generate our own data sets programatically, or find an API that has the data set we need, until now:  

  1️⃣ Use AI to generate a large data set, such as all pokemons, all countries, trivia game rounds. (How would you word this prompt using what you learned from step 2)
  2️⃣ See the generated data, and fine tune it by adding more properties to each data, such as, "Re-generate the countries data and add country code and capital to each country"  

📌 **Exercise (10 min):**  
- Think about your Unit 1 project game. If it needs any data, go ahead and generate it using AI.
- Google search if the data for your game can come from an external API. (You can use AI to ask it to find the API for you)
- Compare your AI generated data set to the API data set and choose which one to use for your game.

---

## 🔥 Summary & Key Takeaways  
✅ AI is a **powerful tool** but should not replace **fundamental problem-solving skills**.  
✅ Writing **better prompts** leads to **better AI results**.  
✅ Customizing AI models **enhances efficiency**.  
✅ AI-generated code **must be reviewed and optimized**.  
✅ Follow the **15-minute rule** before asking AI for help.  

---

## 🛠️ Additional Resources  
📖 [OpenAI's Guide to Prompt Engineering](https://platform.openai.com/docs/guides/prompt-engineering)  
📖 [Best Practices for AI-assisted Coding](https://www.freecodecamp.org/news/how-to-use-ai-for-coding/)  
📖 [Introduction to Custom GPTs](https://openai.com/gpts/)  

---

## 📢 Discussion Questions  
- Have you ever received **bad AI-generated code**? How did you recognize it?  
- How do you balance **using AI vs. learning through trial and error**?  
- What’s the best way to prompt AI for debugging help?  

💬 **Post your thoughts in the discussion forum!**  

---

## 🎯 Next Steps  
🔹 Experiment with **different GPTs** to see which one fits your needs.  
🔹 Try designing a **custom GPT** for a web development task.  
🔹 Practice writing **better prompts** and refining AI-generated code.  