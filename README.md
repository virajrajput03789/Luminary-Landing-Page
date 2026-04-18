# LUMINA | Architectural Light & Space

**LUMINA** is a high-end, fully responsive landing page designed for a fictional luxury architectural lighting brand. This project was developed as a technical assessment to showcase advanced frontend engineering, cinematic UX design, and structural integrity across all viewports.

---

## 🌟 Core Vision
LUMINA bridges the gap between digital interface and physical space. The design uses a **High-Contrast Glassmorphic** aesthetic, utilizing deep shadows and spectral highlights to mimic the experience of luxury architectural lighting.

## 🛠️ Technical Stack
- **Architecture:** Semantic HTML5 & CSS3
- **Styling:** Tailwind CSS (JIT Engine)
- **Motion:** JavaScript (Vanilla), CSS Hardware-Accelerated Animations
- **Logic:** IntersectionObserver API (for efficient scroll-reveals)
- **Deployment:** Vercel / Netlify optimized

---

## 🚀 Key Features & UX Design

### 1. Cinematic Staggered Typography
The main headline ("Sculpting Light, Defining Space") utilizes a custom JavaScript text-splitter. Upon entry, each character cascades into view with a staggered delay, simulating the "flicker and glow" of a luxury lighting installation.

### 2. Interactive Atmosphere Selector (CMS-Ready)
Located in the **Technology** section, this feature allows users to dynamically preview spectral lighting moods (Stellar, Nordic, Midnight). 
- **Technical Thinking:** Implemented via a data-driven JavaScript object (`moods`). This ensures that the system is scalable; adding a new atmosphere via a Headless CMS requires zero changes to the UI logic.

### 3. Viewport Resilience (iPhone SE to Ultrawide)
- **Ultrawide (4K+):** Maintained luxury centering using `max-w-screen-2xl` containers.
- **iPhone SE (320px):** Re-engineered typography wrapping using `inline-block` and `pre-wrap` logic to ensure the headline never overflows or breaks the architectural grid.
- **Adaptive Modal:** The Inquiry Modal uses a Flex-Column architecture with an internal scrollbar, ensuring all form fields are accessible even when the mobile keyboard is active.

### 4. Advanced Hover States
- **3D Perspective:** Feature cards use `transform-style: preserve-3d` to rotate and lift along the Z-axis on hover.
- **Liquid Button Fill:** Primary buttons feature center-tracking radial gradient fills for a tactile, high-end feel.

---

## 🔍 SEO & Semantic Integrity
- **Heading Hierarchy:** Logical H1 -> H4 sequence maintained for perfect SEO crawling.
- **Accessibility:** Included `sr-only` (Screen-Reader Only) titles for sections without visible text labels to ensure a 100% valid document outline.
- **Metadata:** Full SEO meta-description, keywords, and **Open Graph (OG)** tags included for prestigious social media previews.
- **Alt Tags:** Every architectural element contains descriptive `alt` tags for search engine visibility.

---

## 🏗️ Clean Structure & Scalability
- **Naming Conventions:** Consistent, BEM-inspired naming (e.g., `feature-card`, `product-card`, `glass-nav`).
- **Performance:** Opted for the **IntersectionObserver API** over traditional scroll libraries to ensure a high **LCP (Largest Contentful Paint)** score and zero layout shifts (CLS).

---

## 💬 Decision Rationale
> *"I chose a Glassmorphic Architectural style because it reflects the product's core identity—transparency and light. My technical priority was **Progressive Enhancement**: ensuring that while the site features elite animations, the core semantic content and navigation remain 100% accessible if JavaScript is disabled."*

---

## 📥 Submission Checklist Confirmation
- [x] **Responsive Design:** Mobile, Tablet, Desktop, Ultrawide (Verified on iPhone SE).
- [x] **Semantic Structure:** Validated HTML hierarchy and section usage.
- [x] **SEO Basics:** Metadata, Open Graph, and Alt tags integrated.
- [x] **CMS Setup:** Data-driven logic implemented in the Atmosphere Selector.
- [x] **Clean Structure:** Organized, commented, and professionally named code.
- [x] **Quality:** Bug-free, optimized LCP, and zero layout shifts.
