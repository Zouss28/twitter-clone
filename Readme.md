# Django Twitter Clone

## Overview

Welcome to the Django Twitter Clone! This project is a simple Twitter clone built using the Django web framework. It provides a basic platform for users to post tweets, follow other users, and engage in a simplified version of the Twitter experience.

## Features

- **User Authentication**: Users can create accounts, log in, and log out.
- **Tweet Posting**: Authenticated users can post tweets.
- **Follow/Unfollow Users**: Users can follow and unfollow each other.
- **Profile Pages**: Each user has a profile page displaying their tweets.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Python (3.7 or higher)
- Django

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Zouss28/twitter-clone.git
    ```

2. Navigate to the project directory:

    ```bash
    cd twitter-clone
    ```

3. Install dependencies:

    ```bash
    pipenv install
    ```

4. Apply migrations:

    ```bash
    python manage.py migrate
    ```

5. Create a superuser account:

    ```bash
    python manage.py createsuperuser
    ```

6. Run the development server:

    ```bash
    python manage.py runserver
    ```

7. Open your browser and go to [http://localhost:8000/](http://localhost:8000/) to view the application.

## Usage

1. Log in using your superuser account or create a new account.
2. Explore the app by posting tweets, following other users, and checking your timeline.

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m "Add new feature"`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.


## Acknowledgments

- Thanks to the Django community for providing an excellent web framework.
- Inspiration from https://github.com/codingforentrepreneurs.