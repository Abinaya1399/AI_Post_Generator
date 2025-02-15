# **AI Post Generator Project**

This tool is designed to help social media influencers like LinkedIn craft new posts that align with their unique writing style by analyzing their past content.

### **How It Works:**
A social media influencer who wants assistance in writing future posts uploads their previous post content, and this tool analyzes key elements like topics, tone, and post structure. They can then select specific parameters—such as the topic, language, and desired length—to generate new posts that reflect their authentic voice.

---

## 🚀 **Technical Workflow**

1. **Data Collection & Analysis:**
   - Import LinkedIn posts and automatically extract key details like topics, language, and post length.

2. **Content Generation:**
   - Using the selected topic, language, and length, the tool employs few-shot learning techniques. This process helps the LLM (Large Language Model) understand the influencer's writing style by referencing similar past posts.

---

## ⚙️ **Getting Started**

1. **API Key Setup:**  
   - Obtain your API key from [Groq Console](https://console.groq.com/keys).  
   - Add your API key in the `.env` file: 
     ```bash
     GROQ_API_KEY=your_api_key_here
     ```

2. **Install Dependencies:**  
   Ensure you have Python installed. Then run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the Application:**  
   Run the following command to start the Streamlit app:
   ```bash
   streamlit run main.py
   ```

---

## 💡 **Features at a Glance:**
- Analyzes historical social media posts to identify key topics.
- Allows customization based on topic, language, and post length.
- Generates content that mirrors the influencer's unique writing style.


