# Author Website — [Author Name]

A clean, responsive author website built with HTML, Tailwind CSS, and vanilla JavaScript. Designed to showcase books, biography, press mentions, and contact information.

## 📚 Features

- **Responsive Design** – Looks great on desktop, tablet, and mobile
- **Book Showcase** – Display books with covers, descriptions, and purchase links
- **Author Bio** – About section with photo and biography
- **Press & Reviews** – Testimonials and media mentions
- **Newsletter Signup** – Simple email collection (frontend demo)
- **Events Calendar** – Upcoming book signings and appearances
- **Contact Form** – Demo contact form with validation

## 🛠️ Tech Stack

- HTML5
- Tailwind CSS (CDN)
- Vanilla JavaScript
- Font Awesome icons

## 📁 Project Structure

```
author-website/
├── index.html          # Homepage
├── books.html          # Books listing page
├── about.html          # Author biography
├── contact.html        # Contact form
├── css/
│   └── style.css       # Custom styles
├── js/
│   └── main.js         # Interactive elements
└── assets/
    ├── images/         # Book covers, author photo
    └── favicon.ico
```

## 🚀 Getting Started

### Prerequisites

- Any modern web browser
- Live server (recommended)

### Installation

1. **Download or clone** the repository
```bash
git clone https://github.com/yourusername/author-website.git
```

2. **Navigate** to the project folder
```bash
cd author-website
```

3. **Open** `index.html` in your browser or use a live server
```bash
# Using VS Code Live Server extension
# Or run: npx live-server
```

## 📖 Pages Included

| Page | Description |
|------|-------------|
| Home | Hero section, featured book, latest news |
| Books | Complete bibliography with buy links |
| About | Author bio, photo, awards |
| Contact | Email form, social links, events |

## 🎨 Customization

### Change Colors
Edit Tailwind classes in HTML or override in `css/style.css`

### Add Books
Update the books array in `js/main.js`:
```javascript
const books = [
  {
    title: "Book Title",
    cover: "assets/images/cover.jpg",
    description: "Book description...",
    buyLink: "https://amazon.com/..."
  }
];
```

### Update Author Info
Edit the about section in `about.html`

## 📱 Responsive Breakpoints

| Device | Breakpoint | Layout |
|--------|-----------|--------|
| Mobile | < 640px | Single column |
| Tablet | 640px - 1024px | Two columns |
| Desktop | > 1024px | Multiple columns |

## 🔧 Future Enhancements

- [ ] Backend integration for contact form
- [ ] Blog / news section
- [ ] Mailing list integration (Mailchimp API)
- [ ] SEO optimization
- [ ] Dark mode toggle

## 📄 License

MIT – Free for personal and professional use

## 🙏 Acknowledgments

- Tailwind CSS
- Unsplash for placeholder images
- Font Awesome icons

---

**Live Demo:** [mashaamauthor.vercel.app](https://mashaamauthor.vercel.app)  
**Author Portfolio:** [mashaamauthor.com](https://mashaamauthor.com)
