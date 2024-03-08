SIMPLE is a very basic programming language, it is not meant to be used for complicated things.

Print Command:

Syntax: Print = <text>
Description: Prints the specified text to the output.

PrintEquation Command:

Syntax: PrintEquation = <equation>
Description: Evaluates the specified equation and prints the result to the output.

MultipleChoice Command:

Syntax: MultipleChoice = <choice1>; <choice2>; ... / <correct_answer_index>
Description: Provides a multiple-choice question with the given choices and the correct answer index.
User should enter "*" when prompted after running the command to select their answer.

General Syntax Rules:

Each command should be on a separate line.
Commands and their parameters are separated by an equal sign (=).
Choices in the MultipleChoice command should be separated by semicolons (;).
Correct answer index in the MultipleChoice command should be provided after the forward slash (/).

User Input:

After running the code, a prompt will appear for the user to input their answer to the multiple-choice question.
The user should enter their answer in the format "*" (e.g., "*2" for answer index 2).
Output Display:

If the user enters the correct answer, the output will display "Correct!".
If the user enters an incorrect answer, the output will display "Incorrect!".
If the user skips the question (by canceling the prompt), the output will indicate "Question skipped".

The End
