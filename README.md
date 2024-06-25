# AnimeWorld

AnimeWorld is a Django-based e-commerce web application focused on providing a platform for buying anime posters. It includes functionalities for managing anime content, user accounts, and facilitating online transactions.

## Features

- **User Authentication**: Secure user registration and authentication system for managing customer accounts.
  
- **Anime Posters Store**: Browse, search, and purchase a variety of anime posters.
  
- **Categories and Tags**: Organize posters by anime series, genres, or tags for easy navigation.
  
- **User Profiles**: Personalized profiles for customers to track orders, manage favorites, and update account details.
  
- **Shopping Cart**: Add posters to a shopping cart for easy checkout.
  
- **Order Management**: View order history and status updates.
  
- **Responsive Design**: Mobile-friendly interface for seamless browsing and purchasing on any device.

## Project Structure

- **manage.py**: Django script for administrative tasks.
- **animeworld/**: Main settings and configurations for the Django project.
- **accounts/**: Manages user accounts, including authentication and profile management.
- **category/**: Handles categorization of anime posters, such as genres or tags.
- **store/**: Core functionality for the e-commerce store, including listing and displaying posters.
- **templates/**: HTML templates for the frontend.
- **static/**: Contains static files like CSS, JavaScript, and images.

## Installation

1. Clone the repository:

   ```
   git clone <repository_url>
   ```

2. Install dependencies:

   ```
   pip install -r requirements.txt
   ```

3. Apply database migrations:

   ```
   python manage.py migrate
   ```

4. Load initial data (if any):

   ```
   python manage.py loaddata <fixture_file>
   ```

5. Start the development server:

   ```
   python manage.py runserver
   ```

6. Access the application in your web browser at `http://localhost:8000/`.

## Usage

- Register an account or log in to browse and purchase anime posters.
- Navigate through categories or use search functionality to find specific posters.
- Add posters to your shopping cart and proceed to checkout securely.
- View and manage orders through your profile dashboard.
- Enjoy the collection of anime posters available for purchase!

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or create a pull request.

## License

This project is licensed is reserved by suryapratapsahu

---
