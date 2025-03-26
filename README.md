# Search-Engine-Optimization
# SEO Keyword Research & Site Audit Tool

## Overview
This is a simple Flask web application that provides two key functionalities:
1. **Keyword Research**: Fetches Google autocomplete suggestions for a given keyword.
2. **Site Audit**: Retrieves the title and word count of a given webpage.

## Features
- Uses **Google autocomplete** to suggest relevant keywords.
- Performs a **basic site audit** to analyze webpage title and word count.
- Built with **Flask**, **Requests**, and **BeautifulSoup**.

## Installation
### Prerequisites
Ensure you have Python installed (preferably Python 3.6+). You also need Flask and BeautifulSoup. Install the required dependencies using:
```bash
pip install flask requests beautifulsoup4
```

## Usage
### Running the Application
1. Clone the repository or download the source code.
2. Navigate to the project directory.
3. Run the following command:
   ```bash
   python app.py
   ```
4. Open your browser and go to `http://127.0.0.1:5000/`

### Functionalities
- **Keyword Research**:
  - Enter a keyword in the input field and get autocomplete suggestions from Google.
- **Site Audit**:
  - Provide a URL to analyze its title and word count.

## File Structure
```
/seo-tool
│── templates/
│   ├── index.html    # Main page with input forms
│   ├── results.html  # Displays keyword suggestions or audit results
│── app.py            # Main Flask application
│── README.md         # Documentation
```

## Notes
- Ensure you have an active internet connection for API requests.
- Google may limit autocomplete requests if made frequently.

## License
This project is open-source and available for modification and distribution.

