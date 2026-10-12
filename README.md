Netflix India Landing Page CloneA responsive landing page clone of Netflix India built using HTML5 and CSS3. This project replicates the landing interface of Netflix India, including the hero section, trending content carousel, feature showcase sections with embedded video frames, dynamic FAQ accordion, and footer navigation.Table of ContentsFeaturesDemo / PreviewTech StackProject StructureGetting StartedKey ComponentsAccessibility & Best PracticesLicenseFeaturesHero Section: High-impact call-to-action banner with language selector, sign-in redirection, and email submission form.Trending Now Carousel: Displays top trending titles in India numbered 1 through 6 with lazy-loading enabled for optimal performance.Feature Sections: Highlights key service features (TV streaming, offline downloads, multi-device support, and Kids profiles) with responsive video overlays.FAQ Accordion: Interactive section using native semantic HTML <details> and <summary> elements.Footer: Full footer structure matching Netflix India's link layout and language dropdown.Responsive Layout: Designed to scale smoothly across mobile, tablet, and desktop viewports.Tech StackHTML5: Semantic elements (<header>, <nav>, <section>, <article>, <details>, <footer>) for structural integrity and accessibility.CSS3: Custom styles for layout, overlays, typography, and responsive design (located in style.css).Project Structure.
├── index.html   # Main HTML markup
├── style.css    # Main stylesheet
└── logo.svg     # Netflix logo asset
Getting StartedPrerequisitesNo external build tools or framework dependencies are required. All you need is a web browser.Installation & Running LocallyClone the repository:git clone https://github.com/your-username/netflix-india-clone.git
Navigate into the project folder:cd netflix-india-clone
Open the project:
Simply double-click index.html or open it using your preferred browser:# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
Alternatively, you can run it using a local server extension such as Live Server in VS Code.Key ComponentsSectionDescriptionHeader / HeroContains branding, language switcher, sign-in CTA, pricing highlights, and membership email form.Trending NowHorizontal collection showcasing trending titles with rank badges.Features GridAlternating image/video and text blocks explaining platform features.FAQNative expandable <details> elements for frequently asked questions.FooterMulti-column links directing to official Netflix help and informational pages.Accessibility & Best PracticesSemantic Tags: Native tags (<nav>, <article>, <details>) are used throughout to ensure better screen reader navigation.ARIA Attributes: Attributes like aria-label and aria-hidden are included for interactive controls and decorative elements.Performance: loading="lazy" attribute added to title thumbnail images to improve initial page load speed.Media Optimization: Videos are set to autoplay, loop, muted, and playsinline for seamless inline playback across desktop and mobile devices.LicenseThis project is created for educational and learning purposes only. Netflix is a registered trademark of Netflix, Inc.
