# SiriC's Blog

This is the source code for [SiriC's Blog](https://sirichiu.github.io/), a personal blog built with [Hugo](https://gohugo.io/).

## 🚀 About

This blog shares my notes and projects related to:
- Software Engineering
- Signal Processing
- Data Science
- Biomedical Ultrasound

## 🛠️ Tech Stack

- **Static Site Generator:** [Hugo](https://gohugo.io/)
- **Theme:** [Tranquilpeak](https://github.com/kakawait/hugo-tranquilpeak-theme)
- **Deployment:** GitHub Pages

## 🏃‍♂️ Quick Start

1.  **Install Hugo:**
    Follow the instructions in the [Hugo Documentation](https://gohugo.io/getting-started/installing/).

2.  **Clone the repository:**
    ```bash
    git clone --recurse-submodules https://github.com/siriChiu/siriChiu.github.io.git
    cd siriChiu.github.io
    ```

3.  **Run the local server:**
    ```bash
    hugo server
    ```
    The site will be available at `http://localhost:1313/`.

## 📦 Deployment / Publishing

This project uses **GitHub Actions** for automated deployment. You do **not** need to manually build the `public/` directory or push it to the `gh-pages` branch.

### 🚀 How to Publish

1.  **Draft your post:** Create and edit your content. Ensure `draft: false` in the front matter.
2.  **Commit and Push:** Push your changes to the `main` branch.

    ```bash
    git add .
    git commit -m "New post: your post title"
    git push origin main
    ```

3.  **Automatic Build:**
    - GitHub Actions will interpret the push to `main`.
    - It will automatically build the static site (generating `public/` folder).
    - It will deploy the generated files to the `master` branch.
    - Your changes will be live on `https://sirichiu.github.io/` shortly.

## 👤 Author

**Siri Chiu**
- Software Engineer
- 醫工 ✕ 電子 ✕ 資訊