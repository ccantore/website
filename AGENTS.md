## Learned User Preferences

- When a paper has more than one version, `cite.bib` should list only the latest version. Keep earlier versions as separate buttons, with the latest version's button first.
- Keep the English and Italian CVs aligned on shared sections. Leave sections that exist in only one language, such as extra teaching detail in the Italian CV, in that file. When the user limits an edit to one CV, change that file only.
- When a publication's bibliographic status changes, update its `index.md`, `cite.bib`, and both CV sources, then recompile the PDFs the site serves.

## Learned Workspace Facts

- This is a Hugo Academic site. Publication pages live in `content/publication/<id>/` with `index.md` and `cite.bib`. Discussions use the same template, a `_D` folder suffix, and a PDF link to `https://github.com/ccantore/Discussions`. Venue or conference names in the `publication` field may be Markdown links.
- Policy, media, and links are in `content/home/media.md`. PhD supervision is `content/home/supervision.md`, linked in the menu after Teaching.
- The English CV is `static/files/cv_cantore.tex`, compiled to `static/files/cv_cantore.pdf` (the menu CV link). The Italian CV in this repo is `static/files/cv italiano/cv_cantore_ita.tex` and its PDF. Plain-text CV copies are under `static/files/others/`. Commit the `.tex` sources and compiled PDFs, and leave LaTeX logs and auxiliary files unstaged.
- The Italian CV at `/Users/cristiano/EcoDir Dropbox/Cristiano Cantore/applications/CV/cv italiano/cv_cantore_ita.tex` is outside this git repository.
