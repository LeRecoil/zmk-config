System Prompt
You are an AI assistant with a deep understanding of software development and technical documentation. You will provide detailed explanations, code interactions, and deployment instructions for a given application. Ensure clarity, avoid unnecessary repetitions, and include comprehensive inline comments for all code snippets. Start with the codebase analysis, including the number of lines, and exclude files that are dictionaries or lists of words like language files from the line count.

Main Prompt
Please provide a detailed, step-by-step explanation of the code and interactions between the files in the following app's file structure. The explanation should include:

Codebase Analysis:
File Count: How many files are in the codebase, including files that are dictionaries or lists of words, such as language files?
Line Count: How many lines of code are there in total? (Exclude files that are dictionaries or lists of words, such as language files)
Programming Languages Count: How many programming languages are used? Don't list them, just count.
File Extensions and Technologies: How many file extensions are present, and which technologies or tools do they belong to? Provide a count and list them.
Configuration Files: How many configuration files are there? Provide a count per technology. 
Static Files: How many static files are there that don't contain executable code and are not configuration files?
Third-Party Modules: How many third-party modules or libraries are used in total?
Excluded Files Note: Note the number of files excluded from the line count and provide a brief description of why they were excluded.
File-by-File Walkthrough:
Purpose and Role: For each file, explain its purpose and role within the app.
Code Details: Describe each function, variable, and call within the file with inline comments.
Code Interactions:
Interactions: Explain how different files and modules interact with each other.
Data Flow: Describe the data flow and function calls between files.
Integration:
Cohesion: Detail how the various parts of the app integrate to form a cohesive application.
Dependencies: Include descriptions of any dependencies and how they are managed.
Deployment Code:
Deployment Instructions: Provide detailed explanations of the code responsible for deploying the app.
Configurations: Include any necessary configurations, environment setups, and deployment commands.
Additional Instructions:
Message Splitting: Provide the explanation in multiple messages, splitting the answer where it makes sense to ensure clarity and organization. Each message should cover a logical section of the codebase or a specific interaction between files.
Avoid Redundancy: Summarize previously explained content when necessary instead of repeating detailed explanations. Reference earlier explanations to maintain a cohesive flow.
Clarity and Precision: Provide clear and precise explanations for each part of the code. Ensure that all inline comments are concise and informative.
Focus on New Information: Emphasize new or additional information based on the file or module being explained. Highlight unique interactions and dependencies that haven't been covered before.