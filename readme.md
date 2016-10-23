# Resume Template

<<<<<<< HEAD
I designed my first resume using Illustrator. Then I gave Sketch a shot. I even tried LaTeX. None of these fit my evolving needs. Because I wanted finer control over layout and styling, as well as the ability to add conditionals, I decided to use Jade and sass to build a template for my resume.
=======
I designed my first resume using Illustrator. Then I gave Sketch a shot. I even tried LaTeX. None of these fit my evolving needs. Because I wanted finer control over layout and styling, as well as the ability to add conditionals, I decided to use Pug and sass to build a template for my resume. 
>>>>>>> 07b11bb... changing use of jade to pug (the new name)

I wrote this template for myself quite a while back. Feel free to use it however you see fit. If you do use it, all I ask is for you to shout at [me on Twitter](https://twitter.com/moaazsidat) 🙌. If you have any questions, simply plop in an issue.

[Here's my latest resume generated from this template](http://moaazsidat.com/resume/MoaazSidat_resume.pdf).


## Usage

### Templating
<<<<<<< HEAD
To use this template, you'll need to have the Jade CLI (renamed to [Pug](https://github.com/pugjs/pug)) and [sass](http://sass-lang.com/install).
=======
To use this template, you'll need to have the [Pug CLI](https://github.com/pugjs/pug) and [sass](http://sass-lang.com/install). 
>>>>>>> 07b11bb... changing use of jade to pug (the new name)

1. Clone the repo
2. `cd resume`
3. `pug -p resume.pug < resume.pug > resume.html`

### Styling
`sass --watch sass/resume.scss:stylesheets/resume.css`

### Generating a PDF
<<<<<<< HEAD
If I need to generate a PDF, I usually open the file in my browser, and print as PDF. Could use something like `html-pdf` or `jade-pdf` if you prefer a command line tool, but really haven't found myself needing that for now.
=======
If I need to generate a PDF, I usually open the file in my browser, and print as PDF. Could use something like `html-pdf` or `pug-pdf` if you prefer a command line tool, but really haven't found myself needing that for now.
>>>>>>> 07b11bb... changing use of jade to pug (the new name)

## License
MIT
