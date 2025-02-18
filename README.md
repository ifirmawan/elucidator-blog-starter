<div align="center">
<h1>Elucidator blog starter</h1>

<p>Blog starter build with Vue 3 + Vite + Typescript</p>

![banner-elucidator](https://i.ibb.co/d4hScjv/banner.png)

</div>

# Introduction

Elucidator blog starter is a starter blog built with [Vuejs 3](https://v3.vuejs.org/), [Vite](https://vitejs.dev/), and [Typescript](https://www.typescriptlang.org/). You can create publish your post just with markdown file. This starter has so many features for develop your own blog and it's fast ⚡. If you have some experience in vuejs and want to create a personal blog, you can use this starter for create your own blog. If you get bored with this design, you can create your own design. Not to forget, this css framework blog starter was built with [WindiCSS (Next generation utility-first CSS framework)](https://windicss.org/).

# Features

Elucidator blog starter has several features such as:

- Utilities Vue Composition API using [Vueuse](https://vueuse.org/)
- Document head manager for Vue 3 [Vueuse head](https://github.com/vueuse/head)
- Next generation utility first CSS framework using [WindiCSS](https://windicss.org)
- Style with [SCSS](https://sass-lang.com/)
- File system based route generator using [Vite Plugin Pages](https://github.com/hannoeru/vite-plugin-pages)
- Auto importing component using [Vite Plugin Component](https://github.com/antfu/vite-plugin-components)
- Markdown with Vue for Vite using [Vite Plugin Md](https://github.com/antfu/vite-plugin-md)
- Access thousands icons as Vue component in Vite using [Vite Plugin Icons](https://github.com/antfu/vite-plugin-icons)
- Progress bar like youtube, github, etc using [Nprogress](https://github.com/rstacruz/nprogress)
- Code syntax highlighter using [Prismjs](https://prismjs.com/)
- Comment the article using [Vue Disqus](https://github.com/evillt/vue-cusdis)
- Share your article using [Vue Social Sharing](https://github.com/nicolasbeauvais/vue-social-sharing)
- Typescript support :D
- Dark mode support :D

# Components

In this blog starter, we have several components to easier own your blog, and if you have an idea to add some components, you can make a pull request in this repository on github.

- Articles Component
- Latest Component
- Share Component
- Tag Component
- To Top Button
- Pagination

# Comment System

Since this starter use disqus for comment system, first you should get the shortname, you can get the shortname from the official website [disqus](https://disqus.com/) and if you have the shortname, make sure you have to fill the value in the `.env` file. For more detail, you can read the documentation from [Vue Disqus](https://ktquez.github.io/vue-disqus/).

# Usage and Installation

## Development

I used pnpm for the package manager, you can adjust with your favorite package manager.

```bash
pnpm dev
```

## Build

```bash
pnpm build
```

After finish the build process, you will see dist folder successfully generated.

# Working with Docker

## Prerequisites

1. Docker Desktop

You can follow the installation instructions here [https://docs.docker.com/desktop/](https://docs.docker.com/desktop/)
## Run app on docker

1. Build container

```
docker-compose up -d
```

2. Open your browser and go to

```
http://localhost:3000
```

<details>
  <summary>If you want to change the port, see instructions here</summary>
  <ol>
    <li>
        Edit manually Dockerfile at line 32 <br/>
        <code>
        EXPOSE 3000 
        </code>
    </li>
    <li>
        Rebuild container with command <br/>
        <code>
        docker-compose up --build
        </code>
    </li>
  </ol>
</details>

3. Done, try it!


# About The Name

Elucidator is a kirito's sword from the anime [Sword Art Online(SAO)](https://anilist.co/anime/11757/Sword-Art-Online/), and I like that anime, therefore i named this template with Elucidator :D.

# Contributing

Want this project make better? you can contributing in this project to, contribution are welcome :D

# License

Code licensed under [MIT License](https://raw.githubusercontent.com/satyawikananda/elucidator-blog-starter/main/LICENSE?token=AH44ZFFKVJSTLJ3SXJUPKHDA3VAJG).

# Credit

This starter was heavily inspired by [Anthony Fu's](https://github.com/antfu) [Vitesse](https://github.com/antfu/vitesse).

---

![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)
![forthebadge](https://forthebadge.com/images/badges/made-with-typescript.svg)
![forthebadge](https://forthebadge.com/images/badges/made-with-vue.svg)
