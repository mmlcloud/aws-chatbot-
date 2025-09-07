# Chatbot Folder Documentation

This folder contains files that power the recruiter chatbot demo.

1. **demo.html**
   - A simple HTML interface to simulate chatbot interaction
2. **transcript.txt**
   - Sample chat messages for Lambda to read from
3. **readme.md**
   - Explains file purpose and structure

Lambda function reads these files from S3 and returns responses via API Gateway.
