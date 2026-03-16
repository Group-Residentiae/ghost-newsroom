# Newsroom

Newsroom is a minimalist Ghost blog theme for writers and creators—perfect for sharing stories, publishing insights, and growing your audience.

## Useful links

**Demos: https://newsroom.highfivethemes.com/**

**Documentation: https://highfivethemes.gitbook.io/newsroom-user-documentation**

## Features

1. Dark mode with option for dark mode publication logo
2. Custom Archive (All Posts), Authors, Categories (tags), Post with sidebar, Post with overlapping, Post with overlapping and sidebar, Account, Sign In/Up, Error 404 and Membership pages
3. Customizable border-radius for buttons, inputs, images, containers
4. Translation support
5. 18 layout options for homepage sections
6. 3 Header layout options
7. Optional image lightbox with zoom for posts

## Installation instructions

1. Go to **Settings > Design & branding** from the admin menu
2. Click **Change theme**
3. Then click the **Upload theme** button in the upper right corner
4. Click inside the upload box to select a **newsroom.zip**, or drag-and-drop the **newsroom.zip** into the upload box
5. Once uploaded, click **Activate** to activate the theme

## Theme structure

The main templates files are:

- [`default.hbs`](default.hbs) - The main template file
- [`index.hbs`](index.hbs) - Used for the home page
- [`post.hbs`](post.hbs) - Used for individual posts
- [`custom-post-with-sidebar.hbs`](custom-post-with-sidebar.hbs) - Used for individual posts
- [`custom-post-with-overlapping.hbs`](custom-post-with-overlapping.hbs) - Used for individual posts
- [`custom-post-with-overlapping-and-sidebar.hbs`](custom-post-with-overlapping-and-sidebar.hbs) - Used for individual posts
- [`page.hbs`](page.hbs) - Used for individual pages
- [`archive.hbs`](archive.hbs) - Used for Archive (All Posts) page
- [`tag.hbs`](tag.hbs) - Used for tag archives
- [`author.hbs`](author.hbs) - Used for author archives
- [`custom-authors-page.hbs`](custom-authors-page.hbs) - Used for publication's Authors page
- [`custom-categories-page.hbs`](custom-categories-page.hbs) - Used for publication's Categories (Tags) page
- [`error-404.hbs`](error-404.hbs) - Used for 404 Error page
- [`custom-sign-in.hbs`](custom-sign-in.hbs) - Used for custom Sign In page
- [`custom-sign-up.hbs`](custom-sign-up.hbs) - Used for custom Sign Up page
- [`custom-membership-page.hbs`](custom-membership-page.hbs) - Used for custom Memberships page
- [`page-account.hbs`](page-account.hbs) - Used for custom Account page

## Development guide

**Newsroom** theme provides a first-class development experience out of the box.

### Setup

To see realtime changes during development, symlink the **Newsroom** theme folder to the `content/themes` folder in your local Ghost install.

```bash
ln -s /path/to/newsroom /ghost/content/themes/newsroom
```

Restart Ghost and select the **Newsroom** theme from **Settings**.

From the theme's root directory, install the dependencies:

```bash
npm install
```

If Node isn't installed, follow the [official Node installation guide](https://nodejs.org/).

### Start development mode

From the **Newsroom** theme folder, start development mode:

```bash
npm run dev
```

Changes you make to your styles, scripts, and Handlebars files will show up automatically in the browser. CSS and Javascript will be compiled and output to the `built` folder.

Press `ctrl + c` in the terminal to exit development mode.

### Build, zip, and test your theme

Compile your CSS and JavaScript assets for production with the following command:

```bash
npm run build
```

Create a zip archive:

```bash
npm run zip
```

Use `gscan` to test your theme for compatibility with Ghost:

```bash
npm run test
```

## Copyright & License

Copyright (c) 2025 HighFiveThemes - Released under the MIT license.
