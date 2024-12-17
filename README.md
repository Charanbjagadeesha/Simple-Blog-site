# Blog Website 🚀

A fully functional **blog website** built using **Django** for the backend and **HTML/CSS** for the frontend. This project was completed in just **30 minutes** as a part of a coding challenge to create a dynamic blog application with default content.

## Features ✨

- **Dynamic Blog Posts**: Fetches and displays blog posts stored in a database.
- **Beautiful Frontend**: Clean and responsive user interface crafted with HTML and CSS.
- **Default Content**: Pre-seeded default blog posts for quick setup and demonstration.
- **Extensible Architecture**: Built using Django's MVT (Model-View-Template) pattern for scalability.

## Technologies Used 🛠️

- **Backend**: Django (Python)
- **Frontend**: HTML5, CSS3
- **Database**: SQLite (default Django database)

## How to Run Locally 🖥️

Follow these steps to set up and run the project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/blog-website.git
   cd blog-website
   
2. Set Up a Virtual Environment:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate

3. Install Dependencies:
   ```bash
   pip install -r requirements.txt
   
4. Apply Migrations:
   ```bash
   python manage.py makemigrations
   python manage.py migrate

5. Run the Server;
   ```bash
   python manage.py runserver

6. Visit the App: Open your browser and go to http://127.0.0.1:8000/ to view the blog website.

## Default Blog Posts 📝
The application includes the following pre-seeded blog posts:

- <b>Introduction to Django:</b> A quick guide to Django and its features.
- <b>CSS Tips for Beautiful UIs:</b> Tips for creating visually appealing designs.
- <b>Why Learn Python:</b> Exploring the versatility of Python programming.

## Future Enhancements 🚀
- **User Authentication:** Allow users to log in and create their own blog posts.
- **Comment System:** Enable readers to leave comments on posts.
- **Categories and Tags:** Add features for better organization and filtering.
- **Responsive Design Improvements:** Optimize for mobile and tablet screens.
- **Deployment:** Host the application on Heroku, AWS, or other platforms.
- **Rich Text Editor:** Integrate a WYSIWYG editor for advanced post formatting.

## Contributing 🤝
Contributions are welcome! If you’d like to improve this project, feel free to fork the repository and submit a pull request.

## License 📜
This project is licensed under the MIT License.
