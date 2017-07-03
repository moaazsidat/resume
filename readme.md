# Resume Template

I designed my first resume using Illustrator. Then I gave Sketch a shot. I even tried LaTeX. None of these fit the programmatic, and stylistic control I wanted to have over my resume. Using Pug (Jade) to build a template for my resume gave me finer control over layout and styling, as well as the ability to add conditionals.

I wrote this template for myself quite a while back. Feel free to use it however you see fit. If you do use it, all I ask is for you to shout at [me on Twitter](https://twitter.com/moaazsidat) 🙌. If you have any questions, simply plop in an issue.

[Here's my latest resume generated from this template](http://moaazsidat.com/resume/MoaazSidat_resume.pdf).

## Requirements
* [pug-cli](https://github.com/pugjs/pug-cli)
* [sass](http://sass-lang.com/install)

## Usage

### Templating
To use this template, you'll need to have the [Pug CLI](https://github.com/pugjs/pug) and [sass](http://sass-lang.com/install). 

1. Fork and clone the repo
2. `cd resume`
3. `pug -p resume.pug < resume.pug > resume.html`

You may use `pug -w .` to watch for changes and render automatically.

### Styling
`sass --watch sass/resume.scss:stylesheets/resume.css`

### Generating a PDF
If I need to generate a PDF, I usually open the file in my browser, and print as PDF. Could use something like `html-pdf` or `pug-pdf` if you prefer a command line tool, but really haven't found myself needing that for now.

## Contributors
* [Jacob Willemsma](https://github.com/jacobwills)

## License
MIT
