# Job Listing Platform

Welcome to the Job Listing Platform! This README file provides an overview of the platform and guides you on how to set it up on your Laravel installation.

## Description

The Job Listing Platform is a comprehensive application that simplifies the process of searching and exploring job opportunities. It offers a user-friendly interface for users to browse and discover various job listings.

## Features

- Main Dashboard: The platform's main dashboard provides a visually appealing layout with a prominent title, descriptive paragraph, search form, and supplementary text. Users can utilize the search form to find specific information or perform targeted searches based on their job preferences.
- Tags and Job Listings: The platform showcases a list of tags that serve as clickable links. Users can filter job listings by clicking on a tag of interest. The active tag is visually highlighted to indicate the current selection. Job listings are presented as clickable elements, displaying essential details such as the associated company's logo, job title, company name and location, relevant tags, and the time since the listing was created.
- User Authentication: To access additional features and personalized functionalities, users can log in using the provided login form. The form includes input fields for email address, password, a "Remember Me" checkbox, and a "Forgot Password" link for password recovery. Successful authentication grants users access to their personalized dashboard.
- Employer Dashboard: The platform offers a dedicated dashboard for employers, providing a comprehensive overview of their job listings. Each listing is represented as a clickable element and includes details such as the associated company's logo, job title, company name and location, relevant tags, the time since the listing was created, and the number of times the "Apply" button has been clicked.
- Job Listing Details: Clicking on a job listing opens a detailed page showcasing comprehensive information about the specific job opportunity. The page includes the job title, associated tags, a detailed description of the job opportunity, the company's logo, company name and location, and an "Apply" button that redirects users to the appropriate application page.
- Job Posting: Employers can post job listings by filling out a comprehensive form. The form includes input fields for email address, full name, password (if not logged in), job title, company name, company logo upload, location, link to apply, tags, and listing content (supports Markdown). Employers can choose to highlight their job post for additional visibility, with an associated cost. Payment details can be entered for posting the job listing.

## Usage

To set up the Job Listing Platform on your Laravel installation, follow these steps:

1. Clone the repository to your local machine.
2. Install the necessary dependencies by running `composer install`.
3. Copy the `.env.example` file to `.env` and configure the database settings in the `.env` file.
4. Generate an application key by running `php artisan key:generate`.
5. Create symbolic links for storage and public assets by running `php artisan storage:link`.
6. Run the database migrations and seed the database with sample data by running `php artisan migrate --seed`.
7. Start the Laravel development server by running `php artisan serve`.
8. Access the Job Listing Platform through your preferred web browser.

## License

The Job Listing Platform is released under the MIT License. Feel free to use, modify, and distribute the platform as per the terms of the license.