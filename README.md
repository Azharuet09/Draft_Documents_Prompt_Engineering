# Draft_Documents_Prompt_Engineering


This project provides a legal transcript review assistant utilizing GPT-4o, designed to assist in reviewing DOAH hearing transcripts for Exceptional Student Education (ESE) cases. The system analyzes transcripts and legal frameworks, identifies errors, and suggests potential remedies or persuasive arguments based on the input.

## Features
- **Review DOAH Hearing Transcripts**: Analyzes the transcript and identifies key testimony or evidence that may have been misinterpreted, ignored, or undervalued.
- **Explain Legal Frameworks**: Explains the legal framework related to federal appeals in ESE cases, including relevant statutes such as IDEA, Section 504, and ADA.
- **Analyze Case Law**: Identifies and analyzes relevant federal case law supporting an appeal.
- **Identify Legal and Procedural Errors**: Detects legal and procedural errors in the DOAH decision and explains their impact on the case.
- **Apply Standard of Review**: Clarifies the standard of review for federal court appeals and applies it to specific case issues.
- **Suggest Remedies**: Suggests potential remedies for violations in the case, such as compensatory education or IEP meetings.
- **Draft Persuasive Arguments**: Drafts a persuasive argument for a federal appeal, considering anticipated counterarguments.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x
- OpenAI API key
- A `.env` file to securely store the OpenAI API key

## Setup Instructions

### Step 1: Create a Virtual Environment

#### On Windows:

```bash
python -m venv venv
```

#### On Ubuntu:

```bash
python3 -m venv venv
```

### Step 2: Activate the Virtual Environment

#### On Windows:

```bash
.\venv\Scripts\activate
```

#### On Ubuntu:

```bash
source venv/bin/activate
```

### Step 3: Install the Required Packages

Install the dependencies using the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

### Step 4: Configure the `.env` File

Create a `.env` file in the root directory of the project and add your OpenAI API key, for more details you can see the sample file `sample.env.txt`:

```
OPENAI_API_KEY=your-api-key-here
```

### Step 5: Run the Script

Once the environment is set up and the dependencies are installed, you can run the script that contains the functions.

```bash
python main.py
```

Sure! Here is the improved version:

---

### Step 6: Configuration Before Running `main.py`:
Before executing the `main.py` file, ensure that you set the following variables according to your case:

- `transcript`
- `specific_issues`
- `case_description`
- `case_issues`
- `case_violations`
- `case_details`
- `counterarguments`

### Step 7: Output:
The output will be saved in a file named `case_analysis.docx`.