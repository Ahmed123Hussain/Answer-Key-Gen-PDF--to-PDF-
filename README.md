This Project delivers end-to-end solution for Answer key generation task. 
It takes a pdf of questions/question paper as input and returns answer key/solutions as output in pdf format.
Try it out!






Inspiration
The countless hours spent searching for accurate and reliable answer keys for previous year question papers was the primary catalyst for this project. The frustration of encountering incorrect or incomplete solutions was a common experience shared by students, educators, and aspirants alike. I envisioned a platform that could eliminate this hassle and provide a dependable solution.

What it does
It provides the asnwer key pdf for students to enjoy hassle free experience.

How we built it
The project involved several key steps:

PDF Processing: I employed libraries like PyPDF2 and pdfplumber to extract text from the input PDF.
Image Preprocessing: For question papers with images, I utilized OpenCV to preprocess images, enhance clarity, and extract relevant text.
Text Extraction:OCR techniques were implemented using libraries like Tesseract OCR to convert images into text format.
LLM API: I leveraged advanced LLM models and techniques to understand the questions, search for relevant information, and generate accurate answers.
Answer Formatting: The generated answers were meticulously formatted and integrated into a new PDF document.
Challenges we ran into
Developing a robust Answer Key Generator was not without its hurdles:

Accuracy:Ensuring the accuracy of generated answers was the biggest challenge. Factors like handwriting variations, complex question structures, and ambiguous language posed significant obstacles. PDF Complexity: Handling diverse PDF formats, including scanned documents, tables, and complex layouts, required meticulous attention to detail. Computational Resources: The project demanded substantial computational power due to the intensive nature of image processing and NLP tasks. Time Constraints:The hackathon environment imposed strict deadlines, necessitating efficient problem-solving and prioritization.

Accomplishments that we're proud of
Despite these challenges, I persevered and developed a functional prototype capable of generating answer keys for a variety of question papers. This project has the potential to revolutionize the way students and educators access solutions, saving them time and effort.
