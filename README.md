# Yongming Sun — Personal Academic Website

Source for [Yongming Sun's academic website](https://yongmingsun.github.io), hosted on GitHub Pages with Jekyll.

The site has three main pages: Home, Research, and CV.

- `_pages/about.md`: short biography and portrait.
- `_data/research.json`: selected English-language publications and working papers, grouped into two main research strands. Each field has a `groups` array containing a heading and its `papers`; `secondary: true` puts Other research in a collapsed section. Paper records preserve titles, author order, publication status, and links.
- `_pages/cv.md`: web CV with English-language journal articles and selected working papers, including presentations, projects, and skills.
- `_layouts/academic.html`, `_includes/research-list.html`, and `assets/css/academic.css`: shared layout and responsive styling.
- `images/yongming-sun.png`: supplied portrait, unchanged.

Update paper details in the research data file. Chinese-language papers are excluded from the public Research and CV publication lists. Review and revise-and-resubmit statuses appear as secondary working-paper details.

Research features three selected publications and six working papers; the CV lists ten English-language journal articles and the same six working papers. Digital Technologies, Firms & Labor leads with the AI and skills project, followed by papers on supply-chain data, technology diffusion, credit in digital trade, and female inventors. Behavioral & Cognitive Decision-Making is the second main strand. Other research has less prominence and is collapsed by default.

Old Publications links redirect to Research; Talks and Projects links redirect to CV. Template demonstration pages and collections are excluded from publication. Their original source files remain in the repository.

