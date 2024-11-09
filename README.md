# لعبة أُفق (Aufq) 

# Table of Contents

- [📌 Introduction](#-Introduction)
- [🚩 What is the problem ?](#-what-is-the-problem-?)
- [💡 What is our solution ?](#-What-is-our-solution-?)
- [🤖 Our Methodolgy ](#-Our-Methodolgy)
  - [✅ Data](#-Data)
  - [📈 Evaluation](#-Evaluation)
- [⭐ Sustainability](#-Sustainability)
- [⚠️ Conclusion and Results](#-Conclusion)
- [🧩 Future work ](#-Future-work-)

# 📌 Introduction

“Afuq” is an interactive educational app specifically designed to open up new horizons of imagination for children. The app allows kids to become part of the story, where they can make decisions that influence the course of events, creating a unique and enjoyable learning experience. It aims to inspire children through exciting adventures filled with heroes and surprises, making learning both fun and interactive.

 # 🚩 What is the problem ?

Many children struggle with a lack of interest in reading and learning due to traditional methods that may be rigid or non-interactive, leading to a loss of motivation. Additionally, some children lack environments that stimulate creativity and critical thinking, which are important for developing their intellectual and personal skills. Furthermore, parents and educators face challenges in providing engaging educational activities that foster language, reading, and thinking skills in an enjoyable and captivating way.

 # 💡 What is our solution ?

1.Enhancing Children's Motivation to Read: 
“Afuq” offers interactive stories that allow children to become part of the narrative, increasing their excitement for reading and exploring events. They feel like they play an active role in shaping the story’s progression.

2. Encouraging Critical and Creative Thinking:  
By providing multiple choices and puzzles within the story, the app encourages children to think in different ways and make decisions, strengthening their critical and creative thinking skills.

3.Providing an Interactive Learning Experience:  
Instead of static content, "Afuq" offers an immersive experience where children can interact with characters and choose various paths, making learning enjoyable and breaking down the barrier between education and entertainment.

# 🤖 Our Methodolgy

The process of story generation using artificial intelligence is an exciting field within AI and Natural Language Processing.

## ✅ Data

We utilize a combination of internally generated datasets through data    scraping and a dataset generator, along with  datasets that include a variety of labeled children’s stories reflecting cultural and educational themes relevant to our application.

## 📈 Evaluation

**Introduction to Evaluation:**

In this context, accuracy is measured through semantic evaluation, which aims to assess how well the generated story aligns with the expected standards of quality, meaning, context, and structure. Our goal is to use semantic similarity as a metric to evaluate how closely the generated story matches the expected or required story.

**Semantic Evaluation of Story Generation:**

In this evaluation, we attempt to measure how well the meaning and content align between the expected stories (which are predefined as a standard) and the generated stories by the model. This evaluation helps determine how well the model can produce story content that meets the cognitive and aesthetic expectations.

**The evaluation was applied as follows:**

**1.Preparation:**

A set of expected stories was pre-prepared. These stories covered a wide range of domains such as fiction, history, adventures, and children's stories.
The expected stories were collected manually via data scraping or automated story generation tools, ensuring they aligned with the user’s expected patterns.

**A.Story Generation:**
The AI model (Aalam) was used to generate stories based on prompts or initial inputs provided to the model.
**B.Sentence Embeddings:**
The "SentenceTransformer" model (such as all-MiniLM-L6-v2) was used to convert both expected and generated stories into numerical representations that could be compared.
**C.Similarity Calculation:**
Cosine similarity was applied between the embeddings of each expected story and the generated story to calculate how well their meanings matched.
**D.Semantic Accuracy:**
Similarity was calculated across all generated and expected stories, resulting in a semantic accuracy percentage that reflects how closely the generated stories align with the expected stories.

**2.Evaluation and Results:**
**A.Semantic Accuracy:**
Upon applying the evaluation, we achieved a semantic accuracy of 95.16% by comparing the generated stories with the expected ones. This indicates that the model was able to generate stories that closely matched the required content in terms of both meaning and context.

**3.Analysis:**
**A.Achieving High Alignment:** The high cosine similarity between the generated and expected stories reflects the model's ability to mimic narrative patterns and produce story content that matches the expectations.
**B.Model Strength:** The model demonstrated a strong ability to generate rich content and meaningful narratives based on the input context. Additionally, the diversity in generated stories reflects the model's flexibility in adapting to different narrative styles.
**C.Future Improvements:** Despite the high alignment, there may still be minor differences in fine details or creative treatment that could be improved in some cases.

**4.Recommendations for Improvement:**
**A.Training the Model on More Stories:** It is crucial to improve the model by using a larger and more diverse dataset of stories from various fields to enhance generation accuracy in different contexts.
**B.Cultural Understanding Training:** Some stories may require cultural or social context-specific adjustments that can be improved to enhance the accuracy of the generated content.

**5.Conclusion:**
By evaluating the semantic accuracy of story generation, we were able to measure how successful the model was in producing content that aligns with expectations. This method proves effective in applications requiring creative content generation such as children’s stories, novels, or interactive narratives

# ⭐ Sustainability

The "Afuq" project aims for long-term sustainability through various approaches that support the app’s growth and continuity, providing lasting educational value for users.

### 1.Continuous Updates and Content Development.
     - To keep children engaged, "Afuq" is regularly updated with new stories, diverse characters, and puzzles that align with evolving interests and educational needs.
     - The team focuses on creating customized content that adapts to advancements in interactive learning, enhancing the app’s quality and educational benefit.

### 2.Expanding Educational Partnerships.
     - The project seeks partnerships with schools and educational institutions to offer the app as an innovative educational tool, broadening its impact and ensuring sustainability across diverse learning environments.
     - Collaborations with institutions help tailor the app’s development to modern educational standards and requirements.

### 3.User Interaction and Performance Evaluation. 
     - User feedback is gathered periodically to improve content quality and interactive experience, allowing continuous adjustments that meet user needs.

### 4.Data-Driven Learning.
     - "Afuq" utilizes data analysis to understand children’s learning behaviors and interactions with stories, enabling content customization that suits each age group’s levels and abilities.
     - Ongoing data analysis informs content strategies, making the app flexible and responsive to the changing educational needs of children.

### 5.Financial Sustainability.
      - The project is supported by a flexible subscription model, making it accessible for families at an affordable cost, which helps achieve financial stability and ensures ongoing app development aligned with user needs.
      - The project also aims to benefit from funding and partnerships to support future app development without compromising educational quality.
The goal of sustainability in "Afuq" is to create an interactive educational experience that continues to deliver educational value while staying aligned with advancements in digital learning technologies.
      -  Free and Paid Versions: Offering a free version of the game with additional features available through in-app purchases can contribute to financial sustainability.
      -  Diverse Revenue Streams: In addition to paid subscriptions, embedded advertisements or partnerships with educational organizations can support ongoing development funding.

# ⚠️ Conclusion and Results

The "Afuq" project has successfully reached a significant milestone in its development and testing phase. After extensive evaluation and integration of various components, including the user interface design, the story generation model, and data analysis techniques, the application has shown promising results. 
Here is a summary of the key achievements and future directions:

**User Interface Design:** The interface has been finalized and has received positive feedback for being engaging and easy to use for children. The design encourages exploration and interaction, ensuring that the app provides an enjoyable experience for young learners.

**Story Generation Model:** The model for story creation has been integrated successfully, with the system producing stories that align well with the desired outcomes of personalization and engagement. Initial tests suggest the mechanism for story generation is functioning as intended, with the ability to adapt to individual user preferences. The semantic accuracy of 95.16% further underscores the model's ability to deliver meaningful content.

**User Feedback and Testing:** Early-stage testing with a small group of users indicated that the app engages children effectively, enhancing their educational experience. The feedback collected is invaluable for further refining the app and ensuring its alignment with user needs. It also provides important insights into usability and areas for improvement.

**Sustainability and Future Growth:** The project is focused on long-term sustainability by utilizing a flexible subscription model, expanding partnerships with educational institutions, and continuously adapting content to suit evolving educational needs. Data-driven strategies ensure that the app remains responsive to users' learning behaviors, while financial sustainability is supported by strategic funding and partnerships.

Overall, the "Afuq" project has made great strides in creating an interactive, educational, and engaging platform for children. The successful integration of the story generation model, the positive reception of the user interface, and the high level of semantic accuracy all point to a promising future for the app. As the project progresses, continuous iterations and enhancements will ensure that "Afuq" remains a valuable educational tool, providing lasting impact and value for its users.

# 🧩 Future work

Although the project has made significant progress, ongoing user testing and feedback will remain central to its continued growth. Future updates of the app will focus on further enhancing the educational content, expanding its reach, and ensuring that it stays in line with the latest trends in interactive learning. To foster the long-term growth and development of "Afuq" as an engaging educational tool, several key enhancements are planned to enrich the user experience and broaden its impact. 
The following outlines the future vision for the "Afuq" app:

### 1.Expanding the Story Library.
      - Develop a broader range of stories suitable for different age groups and reading levels, including more complex narratives for older children.
      - Add culturally diverse stories and characters to build an inclusive library that introduces children to various traditions and values.

### 2.Advanced Interactive Features.
     - Introduce more complex decision points and branching paths that allow children to explore multiple story endings.
     - Integrate augmented reality (AR) elements to make stories more immersive, allowing children to interact with the story’s environment in real life.

### 3.Personalized Learning Paths.
     - Utilize AI to tailor story content based on difficulty level, vocabulary, and educational goals aligned with each child's progress and preferences.
     - Provide personalized feedback to guide children in improving their comprehension and problem-solving skills.

### 4.Dashboard for Parents and Teachers. 
     - Develop a dashboard that allows parents and teachers to monitor children’s progress, reading levels, vocabulary growth, and critical thinking skills.
     - Enable parents to customize content based on each child's learning needs and development areas.

### 5.Social Interactive Features.
     - Add a safe, monitored social feature where children can share their favorite stories or outcomes and discuss them with friends.
     - Implement cooperative play options where children can solve puzzles or make story decisions together, enhancing teamwork and social learning.

### 6.Multi-language Support.
     - Expand language options in the app to support bilingual education, allowing children from diverse linguistic backgrounds to benefit from "Afuq."
     - Create stories that help children learn new languages through context-driven vocabulary within the story.

### 7.Cross-Platform Accessibility.  
     - Develop versions compatible with various devices, including tablets, computers, and VR headsets, to make "Afuq" accessible across different platforms.
     - Enable offline story access, allowing children to continue learning without needing an internet connection.

### 8.Integration of "Afuq" into School Activities.
     - Introduce "Afuq" as an interactive educational activity suitable for use in schools to enhance reading, critical thinking, and creativity skills.
     - Design educational modules that integrate with school curricula, giving teachers a resource for classroom activities.
