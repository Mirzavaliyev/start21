# 📚 Start21 Education Center – Official Website

This is a modern, responsive, and mobile-friendly landing page developed for **Start21**, an English and SAT preparation center based in Uzbekistan.

The website is fully static (HTML, CSS, JavaScript) and includes sections such as course overviews, teacher profiles, certification slides, and an integrated contact form that connects with a Telegram bot.

---

## 🚀 Features

- ✅ Fully responsive layout (Tailwind CSS)
- ✅ SwiperJS-powered carousels for:
  - Courses
  - Certificates
  - Branch locations
- ✅ Contact & registration form with **Telegram Bot API** integration
- ✅ Teacher profiles with Alpine.js interactivity
- ✅ Embedded YouTube video & Yandex Maps
- ✅ Clean, modern design with icons (Font Awesome)

---

## 🛠 Technologies Used

| Tech            | Purpose                        |
|-----------------|--------------------------------|
| **TailwindCSS** | Responsive UI styling          |
| **SwiperJS**    | Carousel / slider components   |
| **Font Awesome**| Icons                          |
| **Alpine.js**   | Lightweight interactivity      |
| **HTML5**       | Page structure                 |
| **JavaScript**  | Form handling, bot API         |
| **Telegram Bot**| Form submissions               |

---

## 📂 Folder Structure

/start21-website/
├── images/ # Logos, teacher photos, certificates
├── index.html # Main page
├── README.md # Project documentation

yaml
Copy
Edit

---

## 📩 Telegram Bot Integration

The registration form on the site sends data directly to a Telegram group or admin via a bot.

### Replace the following in `index.html`:

```js
const botToken = "YOUR_BOT_TOKEN";
const chatId = "YOUR_CHAT_ID";
You can get your bot token from @BotFather and use @userinfobot to find your chat ID.

✅ Deployment
You can deploy this website easily using:

GitHub Pages

Netlify

Vercel

CPanel hosting (static file upload)

Firebase Hosting

📸 Screenshots
Add screenshots here if possible:

Landing page

Courses slider

Teachers section

Registration form

Telegram notification example

✍️ Author
Shavkatjon

Python & Django Developer

English Teacher

Telegram Bot Developer

🇺🇿 Uzbekistan

📄 License
This project is for educational and demo purposes only. Commercial use requires explicit permission from the author.
