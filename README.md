# Kalayaan: A Student Expenditure Management System

Kalayaan is a user-friendly expenditure management system designed to help students manage their expenses efficiently. It provides detailed visual insights into their spending habits through pie charts categorized by month, day, and year. The system also allows students to add, delete, and update their expenses effortlessly.

---

## Features

- **Expense Tracking**: Record and track all your expenses in a categorized and organized manner.
- **Data Visualization**: View your spending patterns through intuitive pie charts generated using Chart.js.
- **CRUD Operations**: Easily add, update, and delete expenses.
- **Categorized Reports**: Get expense breakdowns by day, month, and year.
- **User-Friendly Interface**: A clean and responsive interface built with HTML and CSS for seamless interaction.

---

## Technologies Used

### Frontend:
- HTML5
- CSS3
- Chart.js

### Backend:
- Flask (Python framework)

### Database:
- SQLite (or any preferred database backend supported by Flask)

---

## Installation

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)

### Steps to Install

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Kalayaan.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Kalayaan
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Flask application:
   ```bash
   flask run
   ```

5. Open the application in your web browser:
   ```
   http://127.0.0.1:5000
   ```

---

## Usage

1. **Add Expenses**: Enter the expense details such as amount, category, and date.
2. **View Analytics**: View your expenses summarized in pie charts.
3. **Manage Expenses**: Edit or delete expenses as required.
4. **Filter by Timeframe**: View expense summaries for specific days, months, or years.

---

## Project Structure

```
Kalayaan/
|
├── static/           # CSS, JavaScript, and image files
├── templates/        # HTML templates
├── app.py            # Main Flask application
├── models.py         # Database models
├── requirements.txt  # Python dependencies
└── README.md         # Project documentation
```

---

## Future Enhancements

- Add user authentication to secure individual accounts.
- Integrate with external payment systems for automated expense tracking.
- Provide more visualizations such as bar and line charts.
- Add a budgeting feature to set monthly spending limits.

---

## Contribution Guidelines

We welcome contributions from the community! Feel free to submit issues, fork the repository, and create pull requests. Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push them to your fork.
4. Submit a pull request explaining your changes.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

For any questions or feedback, feel free to reach out to:

- **Email**: your-email@example.com
- **GitHub**: [your-username](https://github.com/your-username)
