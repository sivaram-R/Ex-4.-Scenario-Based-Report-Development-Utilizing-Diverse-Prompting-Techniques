# Ex-4.-Scenario-Based-Report-Development-Utilizing-Diverse-Prompting-Techniques

**Objective:**
The goal of this experiment is to design and develop an AI-powered chatbot that can handle customer inquiries, provide support, and improve customer experience in a retail environment. Create prompts using various AI prompting techniques to guide your experiment, data collection, analysis, and report creation.

---

## Aim:

To design and develop an AI-powered chatbot using diverse prompting techniques that can handle customer inquiries, provide support, and enhance customer experience in a retail environment.

---

## Algorithm:

**Step 1: Problem Definition**

* Identify the retail environment scenario (e.g., online clothing store).
* Define customer needs (product inquiries, order status, returns, complaints).

**Step 2: Data Collection**

* Gather frequently asked questions (FAQs), support scripts, and product data.

**Step 3: Prompting Techniques Selection**

* Choose diverse AI prompting methods (Zero-shot, Few-shot, Chain-of-Thought, Role prompting, Persona-based, Instruction-based, Self-consistency).

**Step 4: Prompt Design & Experimentation**

* Construct different prompts for the same scenario using each technique.
* Collect chatbot outputs for comparison.

**Step 5: Evaluation**

* Compare outputs for **correctness, coherence, personalization, tone, and customer satisfaction**.

**Step 6: Report Generation**

* Document the **process, outputs, and analysis** into a structured report.

---

<img width="866" height="587" alt="image" src="https://github.com/user-attachments/assets/dd3829a4-a13e-49b2-9ab0-1e491cc95026" />  

---

## Prompt:

“Develop a scenario-based report on designing and implementing an AI-powered chatbot for retail customer support. Apply diverse prompting techniques (Zero-shot, Few-shot, Role-based, Chain-of-Thought, Persona-based, Instruction-based, and Scenario-based)."

---

<img width="1109" height="638" alt="image" src="https://github.com/user-attachments/assets/68c3e77e-e39c-425f-9d1b-6f98b9e63b8c" />  

---

## Output:

### 1. Zero-Shot Prompting

**Prompt:**
"You are a chatbot for a retail clothing store. A customer asks: 'Where is my order?' Respond politely."

**Output:**
"Hello! Could you please provide your order ID so that I can check the status for you?"

**Result:**

* Zero-shot prompting works well for **simple queries**.
* However, it may **lack personalization** and detailed information.

---

### 2. Few-Shot Prompting

**Prompt:**
"Example 1: Customer: 'Do you have size M in blue shirt?' → Chatbot: 'Yes, size M in blue is available.'
Example 2: Customer: 'When will my delivery arrive?' → Chatbot: 'Your delivery will arrive in 2–3 business days.'
Now, Customer: 'Can I return a product I bought last week?'"

**Output:**
"Yes, you can return your product within 30 days of purchase. Would you like me to guide you through the return process?"

**Result:**

* Few-shot improves **accuracy and compliance with policy**.
* More customer-friendly than zero-shot.

---

### 3. Chain-of-Thought Prompting

**Prompt:**
"Step-by-step, think about how a chatbot should answer a customer asking: 'I want to buy shoes under \$50.'"

**Output:**
"First, check product database. Filter items under \$50. Provide top options.
Response: 'Sure! Here are some shoes under \$50: Casual Sneakers (\$45), Running Shoes (\$48), and Sandals (\$39). Would you like to see more?'"

**Result:**

* Ensures **structured, logical answers**.
* Best for **complex reasoning queries**.

---

### 4. Role Prompting

**Prompt:**
"Act as a customer service representative of TrendyWear Store. A customer asks: 'How do I track my order?'"

**Output:**
"Hello, thank you for shopping with TrendyWear. To track your order, please visit our website and enter your tracking ID on the 'Track My Order' page. Would you like me to send you the link?"

**Result:**

* Improves **professional tone, empathy, and trust**.

---

### 5. Persona-Based Prompting

**Prompt:**
"You are a friendly fashion advisor chatbot. A customer asks: 'What should I wear for a beach party?'"

**Output:**
"For a beach party, I recommend light and airy clothes. A floral shirt with shorts or a sundress would be perfect. Don’t forget sunglasses and flip-flops for comfort!"

**Result:**

* Makes chatbot **engaging and human-like**.
* Best for **advisory or lifestyle queries**.

---

### 6. Self-Consistency Prompting

**Prompt:**
"Suggest the best product return policy explanation. Generate multiple responses and choose the most helpful one."

**Output:**

1. "You can return products within 30 days with the receipt."
2. "We accept returns within 30 days of purchase for unused items. You can request a refund or exchange."
3. "Products can be returned within 30 days. Please keep the receipt and original packaging."

**Final Response:**
"We accept returns within 30 days for unused items with the receipt and packaging. You can request a refund or exchange."

---

### Outputs of Chatbot Using Diverse Prompting Techniques

**1. Zero-Shot Prompting Output**
Customer Query: "Where is my order?"
Chatbot Response:
"Hello! Could you please provide your order ID so I can check the status for you? Once I have that, I can give you the exact delivery update."

**2. Few-Shot Prompting Output**
Customer Query: "Can I return a product I bought last week?"
Chatbot Response:
"Yes, you can return your product within 30 days of purchase. Please make sure the item is unused and in its original packaging. Would you like me to share the return request link with you?"

**3. Chain-of-Thought Prompting Output**
Customer Query: "I want to buy shoes under \$50."
Chatbot Response:
"Sure! Let me check. Filtering shoes under \$50... Here are a few options: Casual Sneakers – \$45, Running Shoes – \$48, Sandals – \$39. Would you like me to show you more designs in this price range?"

**4. Role Prompting Output**
Customer Query: "How do I track my order?"
Chatbot Response:
"Hello, thank you for shopping with TrendyWear! You can easily track your order by visiting our website and entering your tracking number on the 'Track Order' page. If you share your order ID, I can fetch the status for you right now."

**5. Persona-Based Prompting Output**
Customer Query: "What should I wear for a beach party?"
Chatbot Response:
"For a beach party, I’d recommend something stylish yet comfortable! A floral shirt with shorts or a flowy sundress would be perfect. Don’t forget your sunglasses, flip-flops, and a light hat to stay cool and trendy!"

**6. Self-Consistency Prompting Output**
Customer Query: "Can you explain the return policy?"

Generated Responses:

* "You can return products within 30 days with the receipt."
* "We accept returns within 30 days of purchase for unused items. You may request a refund or exchange."
* "Products can be returned within 30 days. Please keep the receipt and original packaging."

**Final Optimized Response:**
"Our return policy allows you to return unused items within 30 days of purchase, provided you have the receipt and original packaging. You may choose either a refund or an exchange. Would you like me to guide you to the return page?"

---

## Comparative Analysis Table

<img width="688" height="580" alt="image" src="https://github.com/user-attachments/assets/6402c285-cd3e-4a2c-8d48-e896a26829d6" />  

---

## Result:

### 1. Zero-Shot Prompting Result

* **Observation:** Basic, polite responses but lacks personalization.
* **Strengths:** Fast and easy to use.
* **Weaknesses:** Struggles with complex or ambiguous queries.
* **Overall:** Best for simple FAQs like store hours or order status.

### 2. Few-Shot Prompting Result

* **Observation:** Produces **policy-compliant and accurate** responses.
* **Strengths:** Consistent, better than zero-shot.
* **Weaknesses:** Depends on quality of examples.
* **Overall:** Effective for policy-driven queries like returns.

### 3. Chain-of-Thought Prompting Result

* **Observation:** Structured, logical answers for product search.
* **Strengths:** Great for reasoning tasks.
* **Weaknesses:** Slightly slower, may expose reasoning.
* **Overall:** Best for recommendations and troubleshooting.

### 4. Role Prompting Result

* **Observation:** Professional, empathetic tone.
* **Strengths:** Builds customer trust.
* **Weaknesses:** Can become repetitive.
* **Overall:** Best for customer-facing queries (order tracking, complaints).

### 5. Persona-Based Prompting Result

* **Observation:** Engaging and friendly, great for styling tips.
* **Strengths:** Human-like, boosts customer experience.
* **Weaknesses:** May sacrifice accuracy for friendliness.
* **Overall:** Best for advisory/lifestyle queries.

### 6. Self-Consistency Prompting Result

* **Observation:** Generates multiple answers and selects the best.
* **Strengths:** Reliable and refined responses.
* **Weaknesses:** More resource-intensive.
* **Overall:** Best for **policy or critical queries**.

---

<img width="552" height="738" alt="image" src="https://github.com/user-attachments/assets/b90ec240-3158-42fb-8c21-fe0f0728666d" />  

<img width="895" height="605" alt="image" src="https://github.com/user-attachments/assets/119c4b6a-ebd7-496c-a634-b659884c83ab" />  

