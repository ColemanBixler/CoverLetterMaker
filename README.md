# AI Cover Letter Maker
A Simple AI Cover Letter Maker using python with GPT 3.5 by Coleman Bixler

## Outline
- User input taken from simple application built using tkinter
- Uses openai API in order to get GPT to generate a cover letter using the inputted information
- Then, GPT's response is turned into a cover letter using python-docx

## How to use:
1. Install Python 3 and the following libraries:
    - openAI
    - tkinter
    - python-docx
2. Change the code in gptGeneration.py from "[Your-key]" to your personal openAI key
3. run "python3 coverletterMake.py"
4. Enter the requested information into the program (look at the format in sample-input.txt to see how you might want to format your information)
5. Your new cover letter should be completed!

## Sources
- https://towardsdatascience.com/creating-a-cover-letter-generator-using-python-and-gpt-3-297a6b2a3886
    - Provided inspiration for the project and was a good starting point to follow
- https://python-docx.readthedocs.io/en/latest/
    - Provided an easy way to transform GPT's generated cover letter into an actual usable cover letter with proper formatting
- https://platform.openai.com/docs/guides/gpt/function-calling
    - Provided good instruction on how to use GPT with the python openAI API 
