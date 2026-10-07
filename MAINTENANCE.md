# Updating this profile

Edit `README.md` for the GitHub profile and `resumes/Hrudayangam-Mehta-Resume.tex` for the resume. Keep shared facts consistent with the website source in [Hrudayangam-Mehta/Hrudayangam-Mehta](https://github.com/Hrudayangam-Mehta/Hrudayangam-Mehta).

To rebuild the resume, install Python and a TeX distribution providing `pdflatex`, then run:

```sh
python -m pip install -r requirements-resume.txt
python scripts/build_latex_resume.py
```

In VS Code, Ctrl+Shift+B runs the same build. The script preserves the editable LaTeX source and checks PDF text and overflow. Commit both the `.tex` and compiled `.pdf` after changes. The build also writes an ignored plain-text companion and log.

The PDF in this repository matches the current resume prepared for the portfolio. Changes here do not automatically deploy the separate website repository.
