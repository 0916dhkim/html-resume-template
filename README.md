# HTML/CSS Resume Template
![split](https://github.com/user-attachments/assets/08eae58b-147e-4e99-a974-0ce18c062e03)

Write your resume with just HTML and CSS! \
Don't waste more of your time trying to make MS Word do what you want. \
If you are already familiar with CSS, then HTML will let you achieve the perfect layout much quicker & easier than Word.

This template is a single HTML file with a bit of CSS in `<head>`. \
`<body>` is plain semantic HTML. No JavaScript involved. \
The simplicity of the `<body>` structure makes the style predictable and easy to tweak if you need to.

If you need the PDF version, please open the HTML document in your browser and print the page in PDF.

Check out the live version here: https://0916dhkim.github.io/html-resume-template/

## How to Use This Template

1. Download the [index.html](./index.html) file ![image](https://github.com/user-attachments/assets/6a5c0a11-b5a6-4056-830f-2b5e8e4e44da)
2. Replace the name & edit the links. (Don't forget the `href`s!) ![image](https://github.com/user-attachments/assets/cafe8300-8b86-4b3c-8d15-77bf68a8f1c5)
3. Edit each resume entries. `<h3>` is an entry title, `<h4>` is a subtitle, and you can optionally add `<time>` in the title. Bullet points go under `<ul>`. ![image](https://github.com/user-attachments/assets/6b11812f-0976-4546-aaf0-21a162817f49)
4. Customize the color theme. Note that the resume is always in light mode with white background when printed. ![image](https://github.com/user-attachments/assets/a409a868-0e78-411c-b79d-f2ede5bfe41d)

## How to Convert HTML to PDF

1. After editing the HTML file as instructed above, open it in your browser.
2. Print the page (save as PDF) <img width="1281" alt="image" src="https://github.com/user-attachments/assets/5da00ea3-2905-4d64-8ab3-7b5ba4271558" />
3. (Optional) Uncheck "headers and footers". Check "background graphics" in case you don't see some colors. <img width="1241" alt="image" src="https://github.com/user-attachments/assets/3086f6c1-f385-4e4e-8b40-e5447d93c487" />
4. (Optional) If you see any section overflowing into the next page, add `class="nobreak"` attribute to that section to prevent page break.

## That's All

This template is meant to be used as a starting point. \
I encourage you to play with the CSS in this template and really make it yours.

The only special sauce here is the `@media print {}` queries to customize how the resume gets printed on paper.

Have fun!
