# Resume Parser

## Overview
This Resume Parser is a tool designed to automatically extract key information from resumes. It evolved through three stages:

1. **Manual Parsing**: Initially, the parser was created by manually identifying and extracting relevant sections from resumes (e.g., name, skills, education, work experience). This stage provided a baseline understanding of the structure of resumes and the types of information typically found.

2. **NLP Parsing**: Leveraging Natural Language Processing (NLP), the parser was enhanced to automatically identify and extract important entities from resumes. This step allowed for more accurate and efficient parsing of structured and unstructured data, including skills, experiences, and education details.

3. **ChatGPT Parsing**: Finally, the parser was integrated with OpenAI’s ChatGPT to further refine the extraction process. ChatGPT helps in understanding complex and varied resume formats, improving the parser's ability to identify key sections and present the extracted data in a consistent, structured manner. The output is provided in a concise JSON format, containing only the relevant sections, ensuring brevity and precision.

## Features
- Extracts key sections from resumes (name, skills, education, experience, etc.)
- Outputs extracted data in JSON format
- Supports both structured and unstructured resume formats
- Ensures responses stay within a 500-character token limit

## How It Works
1. Input resume text into the parser.
2. The tool uses NLP and ChatGPT to identify and extract relevant information.
3. The result is returned in a structured JSON format, containing only the most important sections of the resume.
