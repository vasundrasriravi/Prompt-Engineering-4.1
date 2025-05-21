# Prompt-Engineering-4.1
# EXP 4 Scenario-Based Report Development Utilizing Diverse Prompting Techniques- Lab Scenario: Smart Health Assistant System
# REGISTER NUMBER: 212222230168
# Description: 
## Background:
You are part of a development team working on an AI-based Smart Health Assistant named "MediGuide" that assists elderly patients in managing chronic diseases like diabetes, hypertension, and arthritis. The assistant must provide tailored health advice, medication reminders, daily tips, and emotional support through natural language conversations.

## Objective:
To develop a scenario-based report that demonstrates how diverse prompting techniques—zero-shot, few-shot, chain-of-thought, role-based, and multi-modal prompts—can be used to optimize MediGuide’s responses across different patient-centered use cases.

# Algorithm:
### Zero-Shot Prompting
### Prompt: 
“Give a health tip for diabetes.”
### Use:
To get direct advice without prior training.

### Few-Shot Prompting
### Prompt:
Example: “I have arthritis.” → “Try light stretching exercises.”  
Now input: “I have joint pain.” 
### Use:
To generalize based on a few examples.

### Chain-of-Thought Prompting
### Prompt:
“Check sugar level → Assess symptoms → Suggest light food.”
### Use:
To guide AI step-by-step in giving medical advice.

### Role-Based Prompting
### Prompt:
“You are a kind nurse talking to an elderly patient.” 
### Use:
To create a soft and caring response style.

### Multi-Modal Prompting
### Prompt:
“Analyze this foot rash image and give advice.”
### Use:
To generate responses based on images and text.

# output
->  “For diabetes, keep your sugar levels in control and eat small meals.”

->  “I see you mentioned joint pain. Try light stretching or consult your doctor.”

->  “I understand you’re feeling dizzy. Please sit and drink some water.”

->  “As a caring assistant, I’m here to help you. Do you want a reminder for your medicine?”

->  “The foot rash appears serious. Please visit a clinic within 24 hours.”

# Result
The MediGuide assistant successfully responded using diverse prompting techniques, offering helpful and relevant advice to elderly patients across various scenarios including symptom checks, emotional support, and medication guidance.
