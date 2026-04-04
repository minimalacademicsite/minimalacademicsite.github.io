# Minimalist Academic Portfolio Template   [![License: MIT](https://img.shields.io/badge/License-MIT-3172B4.svg?style=flat-square)](https://opensource.org/licenses/MIT) [![Static Badge](https://img.shields.io/badge/Built_with-Jekyll-D00000?style=flat-square&logo=jekyll)]()
<p align="right">
  <sub><i>Find this useful! A ⭐ is greatly appreciated.</i></sub>
</p>

A customized, ultra-minimalist portfolio template designed for Ph.D. researchers, data scientists, and academics. **[Live Demo](https://minimalacademicsite.github.io/)** 



## What makes this fork different?
This template builds upon the robust architecture of [Academic Pages](https://github.com/academicpages/academicpages.github.io) but strips away the visual clutter to present a highly modern, eye-soothing aesthetic. 

* **Minimalist UI:** Removed heavy footers, excessive margins, and distracting elements for a "content-first" experience.
* **Academic Blue Palette:** Uses a cohesive, professional color scheme (`#2C3E50` and `#3172B4`) that renders beautifully in both Light and Dark modes.
* **Vector Tech Stack:** Includes pre-formatted, inline `shields.io` badges for elegantly displaying programming languages and ML frameworks.
* **Streamlined Layout:** Optimized for showcasing publications, research projects, and academic CVs without overwhelming the visitor.

---

## Getting Started

To create your own portfolio using this design, you do not need to fork it manually:
1. Click the green **"Use this template"** button in the top right corner of this repository.
2. Name your new repository exactly like this: `[your-github-username].github.io`
3. Wait a few minutes, and your site will be live at `https://[your-github-username].github.io`.



### Customizing Your Site
Once generated, swap out the placeholder data for your own:
* **`_config.yml`:** The control center. Update your name, email, social links, and Google Analytics ID here.
* **`images/`:** Upload your headshot and name it `profile.png`.
* **`files/`:** Upload your CV/Resume PDF. (Any files placed here will appear at `https://[username].github.io/files/[filename]`).
* **`_pages/`:** Edit the markdown files here to update your "About Me", "Publications", and "Portfolio" pages.

---

## Local Development Environments

When heavily customizing your site, it is highly recommended to preview changes locally before pushing them to GitHub. 

### Option 1: Standard IDE (Ruby & Bundler)
1. Ensure you have `ruby-dev`, `bundler`, and `nodejs` installed. 
   * **Linux/WSL:** `sudo apt install ruby-dev ruby-bundler nodejs`
   * **MacOS:** `brew install ruby node` and `gem install bundler`
2. Run the code to install Ruby dependencies.
   ```bash
   bundle install
   ```
   *(If you experience permission errors, install locally using `bundle config set --local path 'vendor/bundle'` and run again).*
4. Run the code to generate the HTML:
   ```bash
   bundle exec jekyll serve -l -H localhost
   ``` 
5. View your site at:
   ```bash
   http://localhost:4000
   ```

### Option 2: Using Docker
If you want to avoid installing local dependencies, you can use the provided `Dockerfile`.
```bash
chmod -R 777 .
docker compose up
```
You can then access the website at `localhost:4000`.

### Option 3: VS Code DevContainers
If you use Visual Studio Code, this repository includes a Dev Container configuration. Press **F1 -> DevContainer: Reopen in Container**. This will restart VS Code in the container and automatically host your page locally with live-updating.

---

## Maintenance & Syncing
If you utilize this template but wish to pull future bug fixes from the core theme, you may experience merge conflicts. If you are comfortable with Git, you can resolve these by **rebasing** or manually **cherry-picking** the relevant commits from the upstream template.

Alternatively, you can save your customized `.yml` configuration and Markdown files, delete your repository, and generate a fresh one from this template.

---

## Acknowledgments & License
This template is a customized modification of the **Academic Pages** theme.

**Lineage & Credit:**
* Originally derived from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/), created and copyrighted (© 2016) by Michael Rose.
* Forked into [Academic Pages](https://github.com/academicpages/academicpages.github.io) by [Stuart Geiger](https://github.com/staeiou).
* Currently maintained by [Robert Zupko](https://github.com/rjzupkoii) and the open-source community.
* UI minimalism and color palette modifications for this specific iteration were developed by [Md Rezwane Sadik](https://github.com/rez1sadik).

Released under the [MIT License](LICENSE).



<div align="center">

![pages-build-deployment](https://github.com/minimalacademicsite/minimalacademicsite.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)
[![GitHub contributors](https://img.shields.io/github/contributors/minimalacademicsite/minimalacademicsite.github.io.svg?style=flat-square)](https://github.com/minimalacademicsite/minimalacademicsite.github.io/graphs/contributors)
[![GitHub license](https://img.shields.io/github/license/minimalacademicsite/minimalacademicsite.github.io?color=3172B4&style=flat-square)](https://github.com/minimalacademicsite/minimalacademicsite.github.io/blob/master/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/minimalacademicsite/minimalacademicsite.github.io?style=flat-square)](https://github.com/minimalacademicsite/minimalacademicsite.github.io/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/minimalacademicsite/minimalacademicsite.github.io?style=flat-square)](https://github.com/minimalacademicsite/minimalacademicsite.github.io/network/members)

</div>
