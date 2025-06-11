# Resume Grading System using NLP 🧠📄

This project automates the process of resume evaluation by using Natural Language Processing (NLP). It compares resumes against predefined job descriptions and scores them based on the relevance of the skills mentioned.

## 🚀 Features

- Reads and processes resume PDFs
- Extracts keywords and filters out stopwords
- Compares resume content with job-specific skills
- Calculates a skill match score
- Displays matched keywords for transparency

## 📌 Technologies Used

- **Python**
- **NLTK (Natural Language Toolkit)**
- **Regular Expressions**
- **Jupyter Notebook**

## 🧰 Libraries

- `nltk`
- `re`
- `collections.Counter`
- `numpy`

## 📂 Project Structure

## 📊 How It Works

1. **Preprocessing**: Cleans text, tokenizes, removes stopwords.
2. **Keyword Extraction**: Picks the most relevant tokens.
3. **Matching**: Compares extracted resume keywords with job role-specific keywords.
4. **Scoring**: Outputs a percentage match and a list of overlapping skills.

## 🧪 Job Roles Included

- Data Scientist
- Software Engineer
- Project Manager *(extendable)*

## 📈 Output Example

 'Job Role': 'data scientist',
 'Grade': 'C',
 'Skill Match Score': 0.42,
 'Matched Skills': 'experience, expertise, learning, like, machine, proficiency, python, strong, tools, understanding',
 'Feedback': 'Fair match. Add more relevant skills and experience.


## 🔮 Future Enhancements

- GUI or Web App version
- Support for more job roles
- Resume feedback suggestions

## 🙋‍♀️ Author

**Muskan Shaik**  
Aspiring AI Engineer | Web Developer  
https://www.linkedin.com/in/muskan85

---

Feel free to star ⭐ the repo if you find it useful!

