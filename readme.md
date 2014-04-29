# Ladies Learning Code HTML Slides

Awesome, you're going to be creating content for Ladies Learning Code!

We try to do all our slide decks in HTML, because it's easy for learners to follow along in their browsers in the workhop or at home. You only need a basic understanding of HTML to create and edit slides.

## Instructions

### Getting set up:

1. Download the .zip file of this repository or clone it to your computer
2. Rename the folder with the name of your workshop (conventionally starting with "LLC-" and separating words with dashes)
3. Open up index.html in your favourite code editor
4. Customize the first slide with the name of your workshop and information about yourself and other instructors
5. Begin creating slides!

### Creating Slides

Every `<section>` element creates a new slide. Each slide can contain regular HTML markup, like paragraphs, lists, images, etc.

### Customizing Slides

You can customize slides by adding classes to the `<section>` element. There is a default `center` class which centers content vertically and horizontally.

### Adding images

To add images to your slides, save the image to the *content/images* folder then include them as you would in any HTML document.

```
<img src="content/images/imagename.png" />
```

### Using Markdown

If you would prefer to write your slide content in Markdown, you can add the data attribute `data-markdown` to a `<section` tag.

```
<section data-markdown>

  ## Markdown content

</section>
```

### Customizing CSS

If you would like to customize the appearance of your slides, you can add your own CSS in *framework/css/overrides.css*.

## Adding project files

If you will be distributing project/demo files with your workshop, please create a folder called *project* in the root directory and place your files there.

## Publishing your Slides

If you are comfortable with Git, commit your changes, and push to a repository on your own Github account or to the ladieslearningcode organization if you have access.

If you are not comfortable with Git, create a .zip archive of your workshop and send it to whoever you've been in contact with at Ladies Learning Code.

**Note** Please update this readme.md file with information that will be useful to workshop attendees! For example, see the [Introduction to HTML and CSS Repo](https://github.com/ladieslearningcode/LLC-HTML-CSS). If you would like others to contribute to your content, create a contributing.md file in the root directory of your repo, including steps for contributors.

## Publishing your Slides to gh-pages

To host your slides for free on Github, you can use Github Pages.

1. Create a new local branch on your repository called "gh-pages" which contains the same content as your master branch. `git checkout -b gh-pages`
2. Push your gh-pages branch to github `git push origin gh-pages`
3. Your slides should then be viewable at username.github.io/repository-name

For example, this demo template is hosted at [tessalt.github.io/LLC-Slides-Template](http://tessalt.github.io/LLC-Slides-Template)