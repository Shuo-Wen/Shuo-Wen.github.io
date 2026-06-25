# Shuo-Wen's Personal Portfolio Website

Welcome to the repository of my personal portfolio and academic showcase website. This project is a statically generated single-page portfolio built to showcase my academic achievements, research publications, awards, and technical projects.

The website is designed to be highly responsive, lightweight, and structured to present comprehensive credentials (including dynamic elements like image lightboxes and interactive award components) with optimized performance.

---

## 🚀 Key Features

* **Bento Grid Layout:** A modern, structured user interface that balances profile metrics, key achievements, and multimedia showcases.
* **Dual-Format Image Optimization:** Static image assets are available in both high-efficiency modern `avif` formats and high-compatibility `jpg` formats to minimize loading times and bandwidth.
* **Comprehensive Verification:** Integrated directly with verified academic transcripts, publication certificates, and project demos to ensure professional credibility.
* **Mobile Responsive:** Built using robust Flexbox architectures with dedicated media query column-fallbacks ensuring an optimal experience on screens below 640px.

---

## 📂 Repository Structure

Based on the project environment shown in `image_81869e.png`, the directory is organized as follows:

```text
├── avif/                    # High-efficiency next-gen image assets (Optimized for Web performance)
│   ├── 2019_IEEE_SMC_Presentation_edited.avif
│   ├── Microsoft_Imagine_Cup_Taiwan_certificate.avif
│   ├── NTU_outstanding_youth_award_medal.avif
│   └── ...
├── jpg/                     # Legacy image formats ensuring broad cross-browser compatibility
│   ├── 2024_VTS_Best_paper_award.jpg
│   ├── citation_by_nature.jpg
│   ├── Demo Video of cell segmentation.mp4  # Core project video demonstration
│   ├── LLM_system_overall.jpg               # Technical architecture diagram
│   └── ...
├── pdf/                     # Downloadable academic and professional credentials
│   ├── CV_SW_cmprs_small.pdf                # Compressed professional CV
│   ├── NTU_Official_Transcript.pdf          # Official university academic records
│   └── ...
├── index.html               # Main production-ready landing page (incorporating Bento & Flexbox refactor)
└── index_*.html             # Historical design variations and iterative layout testing files

```

---

## 🛠️ Built With

* **HTML5:** Semantic architecture tailored for SEO and ease of navigation.
* **CSS3:** Built with Vanilla CSS utilizing CSS Grid (Bento Layout) and Flexbox for precise alignment.
* **JavaScript:** Lightweight vanilla implementations for dynamic interactions (such as `<details>` formatting and image lightboxes).

---

## 📈 Optimization & Deployment

### Image Asset Strategy

To maintain crisp visual proof without sacrificing Google PageSpeed Insights scores, all critical images are multi-exported. The layout defaults to `.avif` for modern browsers supporting high-efficiency compression, falling back to `.jpg` gracefully when necessary.

### How to Run Locally

1. Clone the repository:
```bash
git clone [https://github.com/Shuo-Wen/Shuo-Wen.github.io.git](https://github.com/Shuo-Wen/Shuo-Wen.github.io.git)

```


2. Navigate to the directory:
```bash
cd Shuo-Wen.github.io

```


3. Open `index.html` in your favorite browser, or serve it using a lightweight local server:
```bash
# If using Python
python -m http.server 8000

```



---

## 📄 License

This project is open-source. Feel free to use the layout and structural concepts as a foundation for your own portfolio website.

```

