# 📝 Todo Apps - Modern Task Management Application

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

A beautiful, modern, and responsive Todo List application built with vanilla JavaScript. Manage your daily tasks efficiently with an intuitive user interface and local storage persistence.

## ✨ Features

- ✅ **Add Tasks** - Create new tasks with title and deadline
- 🎯 **Mark as Complete** - Track your progress by marking tasks as done
- 🔄 **Undo Completion** - Changed your mind? Undo completed tasks easily
- 🗑️ **Delete Tasks** - Remove tasks you no longer need
- 💾 **Local Storage** - Your tasks are automatically saved in your browser
- 📱 **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- 🎨 **Modern UI/UX** - Clean and intuitive interface with smooth interactions

## 🚀 Demo

Simply open `todoapps/index.html` in your browser to see the application in action!

## 🛠️ Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with Flexbox and custom animations
- **Vanilla JavaScript** - No frameworks, pure JavaScript implementation
- **LocalStorage API** - Client-side data persistence
- **Google Fonts (Raleway)** - Beautiful typography

## 📂 Project Structure

```
todoApps/
├── todoapps/
│   ├── index.html              # Main HTML file
│   ├── css/
│   │   └── style.css           # Application styles
│   ├── js/
│   │   └── script.js           # Application logic
│   └── assets/                 # Icons and images
│       ├── check-outline.svg
│       ├── check-solid.svg
│       ├── undo-ouline.svg
│       ├── trash-fill.svg
│       ├── trash-outline.svg
│       └── native/             # Additional icon variants
└── README.md                   # Project documentation
```

## 💻 Installation & Usage

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required!

### Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/ketsar28/todoApps.git
   cd todoApps
   ```

2. **Open the application**
   ```bash
   # Simply open the HTML file in your browser
   # On Linux/Mac:
   open todoapps/index.html

   # On Windows:
   start todoapps/index.html

   # Or you can use a local server:
   # Using Python 3
   python -m http.server 8000

   # Using Node.js (if you have http-server installed)
   npx http-server
   ```

3. **Start managing your tasks!**
   - Add a new task by filling in the form
   - Click the check button to mark tasks as complete
   - Use the undo button to move tasks back to the active list
   - Delete tasks permanently using the trash button

## 📖 How It Works

### Key Features Implementation

**Data Structure**
```javascript
{
  id: <timestamp>,
  task: <string>,
  timestamp: <date>,
  isCompleted: <boolean>
}
```

**Core Functions**
- `addTodo()` - Adds new task to the list
- `addTaskToCompleted()` - Marks task as completed
- `undoTaskFromCompleted()` - Reverts completed task
- `removeTaskFromCompleted()` - Permanently deletes task
- `saveData()` - Persists data to localStorage
- `loadDataFromStorage()` - Retrieves saved tasks on page load

### Browser Compatibility

- Chrome (v90+)
- Firefox (v88+)
- Safari (v14+)
- Edge (v90+)

## 🎨 Screenshots

The application features:
- A clean purple and white color scheme
- Responsive layout that adapts to different screen sizes
- Interactive buttons with hover effects
- Shadow effects for depth and modern appearance

## 🔧 Customization

You can easily customize the appearance by modifying `css/style.css`:

- **Color Scheme**: Change the primary color in the `header` and `.btn-submit` sections
- **Font**: Replace Google Fonts import with your preferred font family
- **Layout**: Adjust container width and spacing in the `.wrapper` and `.container` classes

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/ketsar28/todoApps/issues).

## 📱 Connect With Me

Feel free to reach out and connect with me on various platforms:

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-ketsar28-181717?style=for-the-badge&logo=github)](https://github.com/ketsar28/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ketsar_Ali-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/ketsarali/)
[![Instagram](https://img.shields.io/badge/Instagram-ketsar.aaw-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/ketsar.aaw/)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-ketsar-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/ketsar)
[![Streamlit](https://img.shields.io/badge/Streamlit-ketsar28-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://share.streamlit.io/user/ketsar28)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-Contact_Me-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://api.whatsapp.com/send/?phone=6285155343380&text=Hi%20Ketsar!)

</div>

### 📬 Social Media Links

- **GitHub**: [https://github.com/ketsar28/](https://github.com/ketsar28/)
- **LinkedIn**: [https://www.linkedin.com/in/ketsarali/](https://www.linkedin.com/in/ketsarali/)
- **Instagram**: [https://www.instagram.com/ketsar.aaw/](https://www.instagram.com/ketsar.aaw/)
- **HuggingFace**: [https://huggingface.co/ketsar](https://huggingface.co/ketsar)
- **Streamlit**: [https://share.streamlit.io/user/ketsar28](https://share.streamlit.io/user/ketsar28)
- **WhatsApp**: [Contact Me](https://api.whatsapp.com/send/?phone=6285155343380&text=Hi%20Ketsar!)

## 📄 License

This project is licensed under the MIT License - see below for details.

---

<div align="center">

### 📜 Copyright

**Copyright © 2025 Ketsar Ali. All rights reserved.**

This project was created and developed by **Ketsar Ali**.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

**Made with ❤️ by [Ketsar Ali](https://github.com/ketsar28/)**

*If you find this project useful, please consider giving it a ⭐ on GitHub!*

</div>
