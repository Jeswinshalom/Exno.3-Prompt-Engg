# Experiment 3: Scenario-Driven Report Using Varied Prompt Engineering Methods

**Name:** Jeswin Shalom S  
**Register Number:** 212223060106 

---

##  Aim

The goal of this experiment is to develop a smart chatbot that can assist users with queries such as product issues, order tracking, and general support. By applying different prompt engineering strategies, the chatbot should deliver accurate, natural, and context-aware responses that enhance customer experience and operational efficiency in digital support.

---

##  Algorithm

1. **Query Analysis**  
   Study common customer concerns like order status, product availability, and troubleshooting.

2. **Prompt Classification**  
   Divide prompts into three key types:
   - Simple/direct questions  
   - Data-driven responses  
   - Context-based replies  

3. **Prompt Design**  
   Develop customized prompt formats for each category:
   - Straightforward replies  
   - Tabular responses  
   - Memory-based follow-ups  

4. **Implementation**  
   Incorporate the prompts into an AI chatbot using relevant NLP or AI tools.

5. **Testing & Refinement**  
   Test with varied scenarios and fine-tune for better clarity, accuracy, and flow.

---

##  Prompting Techniques and Use Cases

### 1. Straightforward Prompting

- **Purpose:**  
  Handle basic, single-turn interactions quickly and clearly.

- **Use Cases:**  
  - Checking order status  
  - Return policy  
  - Business hours  

- **Example Template:**  
  > “When a user asks about delivery status, reply with:  
  > _‘Your order is currently being processed and will be delivered soon.’_”

- **Sample Interaction:**  
User: When will my laptop arrive?  
Chatbot: Your order is being processed and should reach you by May 15.


---

### 2. Tabular Format Prompting

- **Purpose:**  
Present structured data like product comparisons or availability in table format.

- **Use Cases:**  
- Product comparison  
- Stock availability  
- Delivery time estimation  

- **Example Table:**

| Product Name   | Availability | Delivery Time       |
|----------------|--------------|---------------------|
| XYZ Headphones | In Stock     | 3–5 business days   |
| ABC Laptop     | Out of Stock | Ships in 2 weeks    |

- **Sample Interaction:**

| Product        | Price     | Stock        | Delivery Time     |
|----------------|-----------|--------------|-------------------|
| HP Pavilion    | ₹45,999   | In Stock     | 3–5 business days |
| Dell Inspiron  | ₹49,000   | Out of Stock | Ships in 2 weeks  |

---

### 3. Contextual (Preceding Message) Prompting

- **Purpose:**  
Continue conversation logically based on earlier messages.

- **Use Cases:**  
- Troubleshooting sequences  
- Personalized support  
- Multi-turn interactions  

- **Example Template:**  
> _“Based on your earlier message about the device, try this next step…”_

- **Sample Interaction:**  
User: My device won’t power on.  
Chatbot: Please press and hold the power button for 10 seconds.  

User: Still not working.  
Chatbot: Since that didn’t help, try charging with another cable. If the issue persists, visit a service center.  


---

## 🛠️ Implementation Steps

1. **Prompt Scripting:**  
 Used placeholders (e.g., `[product]`, `[date]`) for reusable, dynamic replies.

2. **Scenario Testing:**  
 Simulated real-world queries across multiple categories.

3. **Mock Feedback:**  
 Collected responses to rate clarity and helpfulness.

4. **Optimization:**  
 Refined wording, structure, and formatting for improved output.

---

## ✅ Results

The chatbot successfully responded to various types of queries using different prompting strategies:

| Prompt Type           | Strengths                          | Challenges                          |
|------------------------|------------------------------------|--------------------------------------|
| Simple Prompts         | Quick, easy to build               | Limited to basic answers             |
| Tabular Prompts        | Clear comparisons, structured data | Needs formatting support             |
| Contextual Prompts     | Natural flow, personalized feel    | Requires context tracking/memory     |

---

## 🧾 Conclusion

This experiment demonstrated how applying diverse prompting techniques—straightforward, tabular, and context-aware—can significantly improve the effectiveness of an AI chatbot. These techniques enabled:

- Quick and structured answers  
- Smooth, multi-turn conversations  
- Increased user satisfaction and usability

---
