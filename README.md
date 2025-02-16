# AI-Powered Resume Job Matcher

This tool helps job seekers analyze their resumes against job postings by:
- Parsing PDF resumes
- Scraping LinkedIn job postings
- Calculating resume-job matching scores
- Providing AI-powered analysis of fit and suggestions for improvement

## Features

- PDF resume parsing
- Automated LinkedIn job scraping
- TF-IDF based similarity scoring (cosine similarity)
- GPT-3.5 powered analysis of job fit
- Detailed match reports with actionable insights
- CSV export of results

## Setup and Installation

1. Install required dependencies:
```
pip install streamlit requests beautifulsoup4 pandas scikit-learn PyPDF2 python-dotenv openai
```

2. Set up your OpenAI API key
   - Replace OpenAIKey in the code with your actual key

2. Run the script:
```
python aijobmatcher.py
```

## Usage

1. Upload your resume (PDF format)
2. Enter job search parameters:
   - Job title (e.g., "AI Engineer")
   - Location (e.g., "New York, NY")
   - Number of jobs to analyze
3. Review the analysis results in the console and exported CSV file

## Potential Modifications and Improvements

1. Enhanced User Interface
   - Create a Streamlit web interface for better user experience
   - Add visualization of match scores and trends
   - Include interactive job filtering and sorting
   - Implement progress bars for long-running operations

2. Improved Job Matching
   - Add keyword extraction for skills and requirements
   - Implement weighted scoring based on job requirements
   - Include industry-specific terminology matching
   - Add support for multiple resume formats (DOC, DOCX)

3. Extended Data Sources
   - Add support for Indeed, Glassdoor, and other job boards
   - Include company information from company websites
   - Add salary data when available
   - Implement location-based filtering and radius search

4. Advanced Analysis
   - Add skills gap analysis
   - Include industry trends and demand metrics
   - Provide tailored resume improvement suggestions
   - Generate custom cover letter templates based on match analysis

5. Security and Performance
   - Implement rate limiting for API calls
   - Add caching for repeated searches
   - Improve error handling and recovery
   - Add user authentication and result history

## Contributing

Feel free to fork this project and submit pull requests for any improvements you develop.

## License

MIT License - feel free to use and modify for your needs.
