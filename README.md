# BCS-Hackathon

**Inspiration**
The inspiration behind our project traces back to the time before we started the BCS program, when each of us found ourselves struggling with the challenge of accessing answers to program-related questions. These resources were scattered across various platforms such as websites, Reddit threads, and Discord channels, necessitating lengthy and exhaustive searches. Recognizing the need for a centralized solution to streamline this process, we conceptualized and developed BCS Pal!

**What it does**
BCS Pal is a Discord AI Chatbot designed for the UBC BCS program. This chatbot serves as a virtual assistant, designed to swiftly address program-related queries to enhance accessibility and productivity for our fellow classmates and future BCS students. With the chatbot, we aim to alleviate the struggles we once faced and foster a more cohesive and supportive learning environment within our community.

**How we built it**
The AI chatbot was created using the Langchain framework designed for developing applications powered by language models. Combining this with an OpenAI API and unstructured data specific to the BCS program, we developed a Discord Bot capable of answering program-related questions. Along with a functional frontend landing page

**Challenges we ran into**
While using React in Visual Studio Code, we attempted to use the Framer Motion animated library to implement a Parallax Effect. We attempted to track the scroller using the useTransform hook to transform the scroll position into a value that could then be applied to our component. This would allow us to implement the effect based on scroll position, but a problem arose when we had difficulties transitioning the scroll position into a value.

**Accomplishments we are proud of**
One of the issues we overcame was accurately troubleshooting the Parallax issue. With the help of one of the very friendly mentors at the event, Marc, we were able to discover the root cause which was the way the background code was architected. After re-arranging the code, we were finally able to make use of the useScroll function which allowed the Parallax function to do its job as it was now actually detecting the scroll values.

**What we learned**
Utilizing OpenAI API integration in our Discord Bot
Development of functional frontend website using React
Creation of dynamic visual elements using Three.js to enhance visual appeal
What's next for BCS Pal
One key future step for BCS Pal involves integrating memory capabilities into the chatbot. By storing conversation history, BCS Pal will be able to recall past interactions, enhancing the user experience by providing continuity and context.
