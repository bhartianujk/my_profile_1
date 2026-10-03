# Dr. Anuj Kumar Bharti — React Academic Portfolio

A responsive, editable academic portfolio built with React, Vite, and Lucide icons. Ready to deploy on Vercel.

## Run locally

```bash
npm install
npm run dev
```

Open the URL displayed by Vite (usually http://localhost:5173).

## Deploy to Vercel (GitHub)

1. Upload all files in this folder to a new GitHub repository, preserving the `src` directory.
2. In Vercel, choose **Add New → Project**, import the repository, and select **Vite**.
3. Use **Build Command** `npm run build` and **Output Directory** `dist`.
4. Click **Deploy**. No API key or backend is needed for this portfolio.

## Customize

- **`src/data.js`**: Update your biography, current position, verified appointment dates, publications, awards, contact email, and social links.
- **`src/styles.css`**: Change colors, fonts, spacing, and layout.
- **`src/main.jsx`**: Edit page sections and navigation.
- **`index.html`**: Edit title, description, and browser theme color.

### Before publishing

This is a starter site based on publicly indexed information discussed in chat. Please verify academic appointments, dates, awards, and publication metadata. Experience details without verified dates are deliberately labeled for review. Publication links are intentionally omitted when an exact article URL is unavailable. The site uses an illustrative brain graphic rather than a personal photograph.

## Build check

```bash
npm run build
```

The generated `dist/` directory is what Vercel serves.
