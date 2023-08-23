# [Learning Log](https://learning-log-mk4e.onrender.com/)

Learning Log is a web application that allows users to create and manage their learning topics and associated entries. Users can organize their thoughts, notes, and progress on various subjects, making it a handy tool for tracking personal learning journeys.

## Preview



## Features

- Create and manage learning topics.
- Add and edit entries under each topic.
- User-friendly interface.
- Responsive design for different devices.
- Utilizes Django and Bootstrap for seamless development and styling.

## Getting Started

These instructions will help you set up the project on your local machine for development and testing purposes.

### Prerequisites

- Python 3.6 or higher
- Virtual environment (optional but recommended)
- pip package manager

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/hharpreetk/learning-log.git
   cd learning-log
   ```

2. Create a virtual environment (optional but recommended):

   ```sh
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install dependencies:

   ```sh
   pip install -r requirements.txt
   ```

4. Set up the database:

   ```sh
   python manage.py migrate
   ```

5. Create a superuser:

   ```sh
   python manage.py createsuperuser
   ```

6. Run the development server:

   ```sh
   python manage.py runserver
   ```

7. Access the Learning Log in your web browser at `http://127.0.0.1:8000/`.

## Usage

- Log in using your superuser account or create a new account.
- Create new topics and add entries under each topic.
- Edit or delete topics and entries as needed.

## Customize

Here are some additional features you might consider implementing:

 **Categories or Tags:**
   Allow users to categorize their entries using tags or categories. This can help with organizing and searching for specific content.

 **Search and Filtering:**
   Implement a search functionality that lets users search for specific entries or topics. Also, provide filtering options to make it easier to find content.

 **Rich Text Editor:**
   Provide a rich text editor that allows users to format their entries with bold, italic, and other formatting options.

**Integration with External Services:**
    Integrate with external services like Google Drive, Dropbox, or GitHub to import or sync content.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.