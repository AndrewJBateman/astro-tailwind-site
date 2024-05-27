# :zap: Astro Tailwind Site

* Astro Tailwind CSS static website to market a holiday home with excellent SEO & lighthouse score
* **Note:** to open web links in a new window use: _ctrl+click on link_

![GitHub repo size](https://img.shields.io/github/repo-size/AndrewJBateman/astro-tailwind-site?style=plastic)
![GitHub pull requests](https://img.shields.io/github/issues-pr/AndrewJBateman/astro-tailwind-site?style=plastic)
![GitHub Repo stars](https://img.shields.io/github/stars/AndrewJBateman/astro-tailwind-site?style=plastic)
![GitHub last commit](https://img.shields.io/github/last-commit/AndrewJBateman/astro-tailwind-site?style=plastic)

## :page_facing_up: Table of contents

* [:zap: Astro Tailwind Site](#zap-astro-tailwind-site)
  * [:page\_facing\_up: Table of contents](#page_facing_up-table-of-contents)
  * [:books: General info](#books-general-info)
  * [:camera: Screenshots](#camera-screenshots)
  * [:signal\_strength: Technology](#signal_strength-technology)
  * [:floppy\_disk: Setup](#floppy_disk-setup)
  * [:computer: Code Examples](#computer-code-examples)
  * [Project structure](#project-structure)
  * [:cool: Features](#cool-features)
  * [:clipboard: Status \& To-Do List](#clipboard-status--to-do-list)
  * [:clap: Inspiration](#clap-inspiration)
  * [:file\_folder: License](#file_folder-license)
  * [:envelope: Contact](#envelope-contact)

## :books: General info

* Built with Astro framework, CSS and JavaScript with Bootstrap 5 CSS and Javascript
* Server-Side Rendering for very fast content rendering, minimal javascript and no need for a backend server
* TBA...Perfect performance, Perfect scores on accessibility, best practices and SEO.
* **Image Optimization** (using new **Astro Assets** and **Unpic** for Universal image CDN).
* Generation of **project sitemap** based on your routes.
* **Analytics** built-in Google Analytics, and Splitbee integration.
* CSS and Javascript are minimised to reduce initial render/First Contentful Paint time.

## :camera: Screenshots

![Example screenshot](./imgs/home.png).

## :signal_strength: Technology

* [Astro Framework v4](https://astro.build/)
* [Tailwind CSS v3](https://tailwindcss.com/) styling
* [JPG to WebP Converter](https://www.freeconvert.com/jpg-to-webp) to create new image formats that result in a higher Lighthouse score
* [PurifyCSS Online](https://purifycss.online/) - remove unused CSS code from your stylesheets
* [Online CSS Minifier Tool and Compressor](https://www.toptal.com/developers/cssminifier)
* [Online JavaScript Minifier Tool and Compressor](https://www.toptal.com/developers/javascript-minifier)
* [Boxy SVG: Online scalable graphics generator](https://boxy-svg.com/)

## :floppy_disk: Setup

| Command               | Action                                             |
| :-------------------- | :------------------------------------------------- |
| `npm install`         | Installs dependencies                              |
| `npm run dev`         | Starts local dev server at `localhost:3000`        |
| `npm run build`       | Build your production site to `./dist/`            |
| `npm run preview`     | Preview your build locally, before deploying       |
| `npm run format`      | Format codes with Prettier                         |
| `npm run lint:eslint` | Run Eslint                                         |
| `npm run astro ...`   | Run CLI commands like `astro add`, `astro preview` |

## :computer: Code Examples

* tba

```html
          <div class="carousel-item active">
            <picture>
              <source
                type="image/webp"
                class="d-block w-100"
                srcset="./images/bg/house-front.webp"
                alt="house front view"
              />
              <source
                type="image/jpeg"
                class="d-block w-100"
                srcset="/images/bg/house-front.jpg"
                alt="house front view"
              />
              <img
                src="/images/bg/house-front.jpg"
                class="d-block w-100"
                alt="house front view"
              />
            </picture>
            <div class="carousel-caption col-md-6 col-10 col-offset-md-6">
              <h1>Terracota</h1>
              <p class="carousel-image-text">
                Una vivienda moderna, muy bien equipada y muy confortable. En
                este alojamiento se respira tranquilidad: ¡relájate con toda la
                familia!
              </p>
            </div>
          </div>
```

## Project structure

```text
/
├── public/
│   ├── _headers
│   └── robots.txt
├── src/
│   ├── assets/
│   │   ├── favicons/
│   │   ├── images/
│   │   └── styles/
│   │       └── tailwind.css
│   ├── components/
│   │   ├── blog/
│   │   ├── common/
│   │   ├── ui/
│   │   ├── widgets/
│   │   │   ├── Header.astro
│   │   │   └── ...
│   │   ├── CustomStyles.astro
│   │   ├── Favicons.astro
│   │   └── Logo.astro
│   ├── content/
│   │   ├── post/
│   │   │   ├── post-slug-1.md
│   │   │   ├── post-slug-2.mdx
│   │   │   └── ...
│   │   └-- config.ts
│   ├── layouts/
│   │   ├── Layout.astro
│   │   ├── MarkdownLayout.astro
│   │   └── PageLayout.astro
│   ├── pages/
│   │   ├── [...blog]/
│   │   │   ├── [category]/
│   │   │   ├── [tag]/
│   │   │   ├── [...page].astro
│   │   │   └── index.astro
│   │   ├── index.astro
│   │   ├── 404.astro
│   │   ├-- rss.xml.ts
│   │   └── ...
│   ├── utils/
│   ├── config.yaml
│   └── navigation.js
├── package.json
├── astro.config.mjs
└── ...
```

## :cool: Features

* Lighthouse score & pagespeed perfect
* Simple routing..Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

## :clipboard: Status & To-Do List

* Status: In work
* To-Do: Add sections: header, footer, inicio, acerca, fotos, ubicacion, zona, contacto.

## :clap: Inspiration

* [Anna Monus: 9 tricks to eliminate render blocking resources](https://blog.logrocket.com/9-tricks-eliminate-render-blocking-resources/)
* [Maddy Osman: The Ultimate List of Web-Safe HTML and CSS Fonts](https://blog.hubspot.com/website/web-safe-html-css-fonts)
* [Rohith Sasanken: Types of SEO Keywords You MUST Know in 2023](https://www.linkedin.com/pulse/types-seo-keywords-you-must-know-2023-rohith-sasanken/)
* [icolorpalette.com](https://icolorpalette.com/download/palette/136393_color_palette.jpg) combination of terracotta and olive tree leaf green.

## :file_folder: License

* This project is licensed under the MIT License - see the LICENSE file for details.

## :envelope: Contact

* Repo created by [ABateman](https://github.com/AndrewJBateman), email: `gomezbateman@yahoo.com`
* Connect with me on [LinkedIn](https://www.linkedin.com/in/andrewbateman/), [Twitter](https://twitter.com/AndrewBateman) or [GitHub](https://github.com/AndrewJBateman)
* Open issues for feedback and suggestions or to report any bugs or errors. Contributions are welcome!
