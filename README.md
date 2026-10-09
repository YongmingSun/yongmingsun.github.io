# Yongming Sun — Personal Academic Website

Source for [Yongming Sun's academic website](https://yongmingsun.github.io), hosted on GitHub Pages with Jekyll.

The site has three main pages: Home, Research, and CV.

- `_pages/about.md`: short biography and portrait.
- `_data/research.json`: selected publications and all working papers, grouped into two main research strands. Each field has a `groups` array containing a heading and its `papers`; `secondary: true` puts Other research in a collapsed section. Paper records preserve titles, author order, publication status, original Chinese titles, and links.
- `_pages/cv.md`: full web CV, including presentations, projects, and skills.
- `_layouts/academic.html`, `_includes/research-list.html`, and `assets/css/academic.css`: shared layout and responsive styling.
- `images/yongming-sun.png`: supplied portrait, unchanged.

Update paper details in the research data file. English translations of Chinese-language papers are accompanied by the original titles. Publication details and manuscript statuses are carried over from the existing website.

Research features five selected publications; the CV retains the complete list of thirteen journal articles. All twelve working papers remain on Research. Digital Technologies, Firms & Labor leads with the AI and skills projects, followed by Behavioral & Cognitive Decision-Making. Other research has less prominence and is collapsed by default.

Old Publications links redirect to Research; Talks and Projects links redirect to CV. Template demonstration pages and collections are excluded from publication. Their original source files remain in the repository.

