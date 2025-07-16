# Sleek & Modern Portfolio Template

A free, open-source, single-page portfolio template designed for developers, designers, and creators. It's built with pure HTML, CSS, and a sprinkle of JavaScript to be lightweight, easy to customize, and visually appealing.

**Created by [Kartik Sohal](https://github.com/Kartik-Sohal)**

![Portfolio Template Preview](https://staging-jubilee.flickr.com/65535/54657881717_5503541d93_b.jpg) 
<!-- SUGGESTION: Take a screenshot of your customized portfolio and upload it to a site like imgur.com, then replace the URL above to show a preview! -->

---

## Features

-   **Sleek, Modern Design:** A dark theme with a clean layout that makes your projects pop.
-   **Fully Responsive:** Looks great on all devices, from mobile phones to desktop monitors.
-   **Easy to Customize:** All customizable content is clearly marked with `<!-- CHANGE THIS: ... -->` comments in the HTML.
-   **Minimalist & Lightweight:** No heavy frameworks or libraries, ensuring fast load times.
-   **Smooth Scroll Animations:** Subtle fade-in effects as you scroll, powered by the Intersection Observer API.
-   **Free to Use:** Licensed under the MIT License.

---

## How to Use

Getting started with this template is incredibly simple. Follow these steps to make it your own.

### Step 1: Get the Files

You can either:
-   **Fork this repository** to your own GitHub account.
-   **Use it as a template** by clicking the `Use this template` button on GitHub.
-   **Download the ZIP** or clone the repository to your local machine:
    ```bash
    git clone https://github.com/Kartik-Sohal/sleek-portfolio-template
    ```

### Step 2: Customize the Content (`index.html`)

Open the `index.html` file in a text editor. All the sections you need to edit are marked with comments like this:

`<!-- CHANGE THIS: ... -->`

Here’s a checklist of what to change:
-   **Page Title:** In the `<head>`, change the `<title>` to your name.
-   **Navigation & Hero:** Update your name and professional tagline in the `<header>` and hero section.
-   **About Me:** Write your personal introduction and add a URL to your profile picture. A square image (e.g., 500x500 pixels) works best.
-   **Projects:** This is the most important section!
    -   Fill in the details for the three example project cards.
    -   To **add a new project**, simply copy and paste the entire `<div class="project-card">...</div>` block.
    -   Remember to update the project titles, descriptions, technology tags, and links (to the live demo and source code).
-   **Contact Information:** Add your email address in the `mailto:` link and update the social media links (LinkedIn, GitHub, etc.).
-   **Footer:** Change "Your Name" in the copyright notice. The watermark credit should remain as is.

### Step 3: Customize the Style (Optional)

If you want to change the main color of the portfolio:

1.  Open the `style.css` file.
2.  At the very top, in the `:root` section, change the hex code for `--primary-color`.

    ```css
    :root {
        /* CHANGE THIS: This is the main accent color for buttons, links, and highlights. */
        --primary-color: #00bfa5; /* Change this to your favorite color! */
    }
    ```

---

## Deployment

Once you've customized your portfolio, you can host it for free using several services:

-   **[GitHub Pages](https://pages.github.com/):** The easiest way. If your repository is named `your-username.github.io`, your portfolio will be live at that URL as soon as you push your changes.
-   **[Netlify](https://www.netlify.com/):** Simply drag and drop your project folder into the Netlify dashboard.
-   **[Vercel](https://vercel.com/):** Connect your GitHub repository for seamless, automatic deployments every time you push a change.

---

## License

This project is licensed under the **MIT License**. You are free to use, modify, and distribute this template, but please keep the watermark in the footer to credit the original author. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

-   Template created by **[Kartik Sohal](https://github.com/Kartik-Sohal)**.
-   Fonts provided by **[Google Fonts](https://fonts.google.com/)**.
-   Inspiration from modern, minimalist web design trends.