# Inspiration
People forget their dreams quickly. Dream Catcher helps capture and visualize dreams, making them memorable.

# What it does
Quickly record your dreams through customized questions, capturing the essence of each experience. 🌙🕹️🌠
Generating a vivid image of the dream, bringing it to life in a way words alone cannot.💡💎🎥

# How we built it
## Generation Model
Used LangChain for processing, GPT-4o Mini for NLP, Amazon Titan for image generation

## Front End
Next.js was used for the frontend.

## Back End
AWS services (EC2, S3, Lambda, DynamoDB) for backend and storage. 

# Product
![Screenshot 2024-11-17 at 8 37 01 AM](https://github.com/user-attachments/assets/fb950b8a-3575-44bc-aefa-79bbd3c14151)
![Screenshot 2024-11-17 at 8 38 02 AM](https://github.com/user-attachments/assets/a8573173-d045-4956-9b48-b86dfa8b9fe5)

# Challenges we ran into
- AWS Complexity: We had little prior experience with AWS, and setting up advanced services like Lambda was challenging. The learning curve for AWS services was steep, especially when trying to integrate Lambda for serverless computing.
- Lambda: Managing serverless functions efficiently while maintaining performance was difficult. Lambda’s cold start times and resource management posed some challenges.

## Accomplishments that we're proud of
- Successfully deployed all services, integrating AWS services like EC2, S3, Lambda, and DynamoDB to create a fully functional backend.
- Real-time dream recording and automatic image generation.
- Seamless processing using LangChain and GPT-4o Mini for dream analysis.

## What's next for DreamCatcher
Dream big
