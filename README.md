# User Guideline: AI Batch Sheet Generator

## Important Rules
1. **Use separate chats** for each step: Question Setup, Answer Verification, and Solution Setup.
2. **Browser Print Settings:** When saving as PDF in Google Chrome:
   - Destination: **Save as PDF**
   - Margins: **Default**
3. **If AI stops mid-way:** Output token limits may cause the AI to stop before completing the code. Simply reply: **"Continue from where you stopped"**.

## Step 1: Question Setup

1. Open a new chat.
2. Upload the question images.
3. Paste the prompt from question_prompt.md file (make sure to replace `[Subject]` and `[Chapter Name]`):

## Step 2: Verify Answers

1. Open a **new chat**.
2. Upload the `HTML` file generated in Step 1.
3. Paste the prompt from veriy_answer_prompt.md file.


## Step 3: Solution Setup

1. Open a **new chat**.
2. Upload the verified `HTML` question file from Step 1.
3. Paste the prompt from solution_prompt.md file.