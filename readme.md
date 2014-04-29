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

Every `&lt;section>` element creates a new slide. Each slide can contain regular HTML markup, like paragraphs, lists, images, etc.

### Customizing Slides

You can customize slides by adding classes to the `&lt;section>` element. There is a default `center` class which centers content vertically and horizontally.

### Adding images

To add images to your slides, save the image to the *content/images* folder then include them as you would in any HTML document.

```
&lt;img src="content/images/imagename.png" />
```

### Using Markdown

If you would prefer to write your slide content in Markdown, you can add the data attribute `data-markdown` to a `&lt;section` tag.

```
&lt;section data-markdown>

  ## Markdown content

&lt;/section>
```

### Customizing CSS

If you would like to customize the appearance of your slides, you can add your own CSS in *framework/css/overrides.css*.

## Adding project files

If you will be distributing project/demo files with your workshop, please create a folder called *project* in the root directory and place your files there.

## Publishing your Slides

If you are comfortable with Git, commit your changes, and push to a repository on your own Github account or to the ladieslearningcode organization if you have access.

If you are not comfortable with Git, create a .zip archive of your workshop and send it to whoever you've been in contact with at Ladies Learning Code.