# MCQ-Scanner

<h1>Multiple Choice Scanner using OMR, OpenCV and Python</h1>

**Implementation steps:**
1. Load the exam paper by providing path to the image.
2. Convert image to grayscale, blur it to reduce high frequency noise, then find edges
3. Apply a perspective transform to extract the top-down, birds-eye-view of the exam.
4. Extract the set of bubbles (the possible answer choices) from the perspective transformed exam.
5. Sort the questions/bubbles into rows.
6. Determine the marked answer for each row.
7. Lookup the correct answer in our answer key to determine if the user was correct in their choice.
8. Repeat for all questions in the exam
