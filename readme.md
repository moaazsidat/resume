# Resume Template

I designed my first resume using Illustrator. Then I gave Sketch a shot. I even tried LaTeX. None of these fit my evolving needs. Because I wanted finer control over layout and styling, as well as the ability to add conditionals, I decided to use Pug and sass to build a template for my resume. 

I wrote this template for myself quite a while back. Feel free to use it however you see fit. If you do use it, all I ask is for you to shout at [me on Twitter](https://twitter.com/moaazsidat) 🙌. If you have any questions, simply plop in an issue.

[Here's my latest resume generated from this template](http://moaazsidat.com/resume/MoaazSidat_resume.pdf).


## Usage

### Templating
To use this template, you'll need to have the [Pug CLI](https://github.com/pugjs/pug) and [sass](http://sass-lang.com/install). 

1. Clone the repo
2. `cd resume`
3. `pug -p resume.pug < resume.pug > resume.html`

### Styling
`sass --watch sass/resume.scss:stylesheets/resume.css`

### Generating a PDF
If I need to generate a PDF, I usually open the file in my browser, and print as PDF. Could use something like `html-pdf` or `pug-pdf` if you prefer a command line tool, but really haven't found myself needing that for now.

## Contributers
* [Jacob Willemsma](https://github.com/jacobwills)

## License
MIT
