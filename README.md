# CrewAI Blood Test Report Analysis API

This API uses the CrewAI framework to analyze blood test reports, search for relevant health articles, and provide personalized recommendations to users via email.

## Setup

1. Install the required libraries: `pip install crewai flask flask_restful flask_cors PyPDF2 pytesseract pillow flask_mail flask_httpauth`
2. Set up the CrewAI framework using the provided documentation and tutorials.
3. Configure the email settings in `app.config`.

## Execution

1. Run the API using `python app.py`.
2. Send a POST request to the `/api/report` endpoint with the blood test report PDF file and user's email address.

## Authentication

The API endpoint is protected with basic authentication. You can implement your own authentication logic using Flask-HTTPAuth.

## Code Structure

The code is organized into the following sections:

* `app.py`: API development using Flask and Flask-RESTful.
* `analyze_report.py`: PDF analysis using PyPDF2 and Tesseract-OCR.
* `email_delivery.py`: Email delivery using Flask-Mail.
* `authentication.py`: Authentication using Flask-HTTPAuth.

## Note

This is a high-level implementation, and you may need to modify the code to fit your specific requirements.
