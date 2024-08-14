Features

- Upload job descriptions and resumes in PDF format.
- Process resumes to extract names, emails, and text content.
- Calculate the similarity between the job description and each resume.
- Rank resumes based on similarity percentage.
- Download the ranked resumes in a CSV file.

## :wrench: Setup and Usage


1. Install dependencies (Install the latest libraries instead of the specific ones mentioned in the txt file):
   ```sh
   pip install -r requirements.txt
   ```

2. Run the Flask app:
   ```sh
   python app.py
   ```

3. Access the app in your web browser at `http://localhost:5000`.

## :file_folder: Directory Structure

```
├── app.py
├── static/
│   └── styles.css
├── templates/
│   └── index.html
├── uploads/             # Uploaded resumes will be saved here
├── requirements.txt
├── README.md
└── .gitignore
```





