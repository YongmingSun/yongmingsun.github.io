# Yongming Sun — Personal Academic Website

Source for [Yongming Sun's academic website](https://yongmingsun.github.io), hosted on GitHub Pages with Jekyll.

The site has three main navigation links: Home, Research, and CV. CV opens the current Google Drive file directly.

- `_pages/about.md`: short biography and portrait.
- `_data/research.json`: selected English-language publications and working papers, grouped into two main research strands. Each field has a `groups` array containing a heading and its `papers`; `secondary: true` puts Other research in a collapsed section. Paper records contain titles, coauthors, publication status, and links. Coauthors are listed alphabetically by surname after “with”; solo papers omit the coauthor line. `full_author_list: true` displays the complete published author list for “Risky effort.”
- `_data/navigation.yml` and `_pages/about.md`: direct CV links to the current Google Drive file.
- `_pages/cv.md`: redirect from the legacy CV URL to the Google Drive file.
- `_layouts/academic.html`, `_includes/research-list.html`, and `assets/css/academic.css`: shared layout and responsive styling.
- `images/yongming-sun.png`: supplied portrait, unchanged.

Update paper details in the research data file. Chinese-language papers are excluded from Research. Review and revise-and-resubmit statuses appear below working-paper titles. Research links to Google Scholar for the full publication list.

Research features four selected publications and six working papers. Digital Technologies, Firms & Labor leads with the AI and skills project, followed by papers on supply-chain data, technology diffusion, credit in digital trade, and female inventors. Behavioral & Cognitive Decision-Making is the second main strand. Other research has less prominence and is collapsed by default; it includes the “Digital dividends?” paper and its VoxChina article link.

Old Publications links redirect to Research; legacy CV, Talks, and Projects links lead to the Google Drive CV. Template demonstration pages and collections are excluded from publication. Their original source files remain in the repository.

