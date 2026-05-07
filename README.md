# New-Project

A simple and elegant Python console application for collecting user information and storing it in an Excel file. Perfect for quick data entry tasks!

## 📋 Description

This project is a straightforward Python script that prompts users to enter their first name, last name, and ticket number via the console. The collected data is then appended to an Excel spreadsheet (`names.xlsx`) for easy storage and management. It's ideal for scenarios like event registrations, surveys, or any situation requiring organized name collection.

## ✨ Features

- **User-Friendly Input**: Prompts for first name, last name, and ticket number.
- **Excel Integration**: Automatically creates or updates an Excel file with the data.
- **Data Persistence**: Appends new entries without overwriting existing data.
- **Cross-Platform**: Runs on any system with Python installed.
- **Simple Setup**: Minimal dependencies for quick deployment.

## 🚀 Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/GitHubSvetlana/New-Project.git
   cd New-Project
   ```

2. **Install Dependencies**:
   Ensure you have Python 3.x installed. Then install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**:
   ```bash
   python app.py
   ```

## 📖 Usage

1. Launch the app by running `python app.py`.
2. Enter your first name when prompted.
3. Enter your last name when prompted.
4. Enter your ticket number when prompted.
5. The app will update `names.xlsx` with your information and confirm the action.
6. The Excel file will open automatically for review.

Example interaction:
```
Enter your first name: John
Enter your last name: Doe
Enter your ticket number: 123
Excel file 'names.xlsx' has been updated with your details!
```

## 📋 Requirements

- Python 3.6 or higher
- `openpyxl` library (included in `requirements.txt`)

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

For questions or suggestions, feel free to reach out via GitHub issues.

---

*Made with ❤️ using Python and openpyxl.*
