# 🖥️ HW - Create Server

A Node.js web server that serves a styled HTML page.

## 📋 Task Requirements

1. Create a project folder.
2. Create a `templates` sub-folder within the project folder.
3. Create a `page.html` file that looks like the attached image. Since we don't know how to send images yet, create the display using characters of different sizes and color zones. Matching design is mandatory. Use internal CSS.
4. Create an `app.js` file that creates a server sending the file to the FrontEnd.

![Result image](https://images-na.ssl-images-amazon.com/images/S/compressed.photo.goodreads.com/books/1403170838i/20901022.jpg)

## 🚀 How to Run

```bash
node app.js
```
Then open your browser at `http://localhost:3000`

## 💡 Solution Approach

The solution uses:
- `http` module to create a web server
- `fs` module to read the HTML file
- Serves the content of `templates/page.html` to the client

## 👥 Students

- Bshara Karkaby [49-2]
- Moner Makhouly [49-2]

---

**Happy coding!** 💻✨
