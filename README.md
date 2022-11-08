![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Guided exercise - IronSkydive 💪 - block and inline level elements

<br>

## Introduction

During this module, you will get familiar with HTML & CSS. Both technologies combined offer you all the tools you need to create a website. HTML without CSS is ugly, and CSS without HTML is... well, nothing!

That is why you will be working on this exercise on multiple occasions during this module. Our end goal is to create a basic HTML & CSS website, where you will practice the various concepts as you are learning them.

<br>

## IronSkydive | The Company Website

Ironhack loves coding, but we also like to practice extreme sports. In a new line of products, we have created a new company called _IronSkydive_. We offer a full skydiving experience.

We are hoping you could help us to create our website because we are swamped starting the company and making sure that all our papers are aligned with the rules. :see_no_evil:

As we mentioned earlier, you'll be working on this exercise through the next couple of lessons, but in the end, your goal is:

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_1f30ebb21258466ca36702d7cdaa0cad.png)

<br>

You will be working on a new pen, so proceed to [CodePen](https://codepen.io/) and create a new pen now. Ready to take the jump?

<br>

![](https://media.giphy.com/media/xT5LMrGIfLuDtRSAMg/giphy.gif)

<br>

### Part 1 - Block Elements

In this part of the exercise, you are going to work with the block elements you learned. You have seen how the semantic block elements help us s to understand our website's composition better. Let's start by creating the basic HTML structure, which will be the following:

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_8f778c8cd703db596d5bb22dae089716.jpg)

<br>

Later on, in the exercise, we are going to distinguish between the different sections we have. Now, let's add a few more block elements inside each element.

### Nav

Inside `<nav>`, create a `<ul>` tag with three elements:

- Day Structure
- Team
- Schedule

These are going to be our menu options.

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_ace26745798b17492d307e0d0c817ea4.png)

<br>

### Header

You have to create two different things here:

- first, create an `<h1>` tag with the text "IronSkydive", then
- under this tag, create a `<h2>` tag with the text "Let the trip begin" and finally
- under these tags, create an `<aside>` tag that will contain a quote.

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_3c0c7f97d3804c728475f52c89f0ec85.png)

<br>

### Section 1

This section has a dark background that will cover the whole width of the website. Later you will add the color to the background, so for now, no need to worry about this.

<!-- To create this effect, later on, we are going to create a container inside the section. This wrapper will be handy to set a specific width and center all the content in the screen when we get to CSS later on. -->

It will contain three `<article>` tags to add the information under the header.

Inside each `<article>`, add an `<h3>` tag for the different titles, and a paragraph for the white text. The result would be something like this:

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_f004e36a2b2bb0dfc02ac008e5d5c97e.png)

<br>

### Section 2

This section is quite similar to the previous one. In this case, the section will contain a `<h3>` title with the text "How do we structure the day?", and then a `<div>` with four different `<article>` tags.

Inside each _article_ tag, for the moment, we are going to have a `<h4>` tag with the article title, and a `<p>` tag with the article content.

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_c810d2f904e4c4e72ad8b9ed055e4b37.png)

<br>

### Section 3

This case is the same as **Section 1** - it will have a dark background, and, as in the previous sections, you have to add a `<h3>` title and a `<p>` with a brief description.

Then, you will create `<div>` tag and add three empty `<article>` tags that will contain the information of each team member. It is enough to have a text indicating the different articles:

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_4bf21e881db9707b671a812c022db35f.png)

<br>

### Section 4

In this section, we have a table that contains the schedule.

Let's start with adding two different `<h3>` headings with the text:

- Schedule
- Schedule a Time Slot

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_cdeeac1a34e5b4f5785ec6f203632b7c.png)

<br>

Now add a table under the first `<h3>` tag, that contains the text "Schedule". Indeed, this table is going to contain the IronSkydive schedule for the week. The format of the table is the following:

| Time          | Monday | Tuesday | Wednesday | Thursday | Friday | Saturday |
| ------------- | ------ | ------- | --------- | -------- | ------ | -------- |
| 9:00 - 11:00  |        |         | X         |          | X      | X        |
| 12:00 - 14:00 |        |         |           |          | X      | X        |
| 15:00 - 17:00 |        |         | X         | X        | X      | X        |

Create the table and add the necessary content to get this result:

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_5c089d05a9df991db3784ba81a880835.png)

<br>

Remember, besides `<table>` tag, you should use `<thead>` with six `<th>` tags for the header rows (six days that IronSkydive operates), and then inside _body_ of the table (`<tbody>`) you should define rows with `<tr>` tags. In the end, you should use `<td>` tags for the content inside the rows.

### Footer

Last but not least, the footer section has to contain just one `<section>` tag. Inside the `<section>`, you have to add several things (described in the correct order):

- `<h5>` with the title "Contact Information".
- [`<address>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/address) element, with the correct information:
  _IronSkydive 33 Rue la Fayette, 75009 Paris, France +33 (0) 619 193 088_
- `<h5>` with the title "Follow Us".
- `<ul>` list with three elements:
  - Twitter.
  - Facebook.
  - Instagram.

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_661b4572e673afb0ce5a419ae78b9ce8.png)

<br>

### Part 2 - Inline Elements

In the second iteration of our exercise, you are going to work with the inline elements you learned. You have seen that we use different tags with different goals. Remember, this is our current project structure:

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_8f778c8cd703db596d5bb22dae089716.jpg)

<br>

You are going to add different inline elements to all the sections we already have.

### Nav

The `<nav>` tag is used to wrap links on our website. Right now, we have just a list of elements. Let's change this, by adding _links_ in each list item.

You have to create three different links, that will be pointing to `#structure`, `#team`, and `#schedule`, respectively:

:bulb: Spoiler: _links_ are _anchor_ tags and represented with `<a>` tag and need to have `href` attribute. :wink:

```html
<a href="#structure">Day Structure</a>
```

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_53837d5c2b9d5e3c537a87079080151e.png)

<br>

### Header

The header of the project is incomplete. First, you need to add a logo to the header. Also, add a _testimonial style quote_ where you currently have filler text.

**First, the logo.** Add an image inside the `<h1>` that loads the following image:

`https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironhack-skydive-logo.png`.

Remember to add a descriptive alternative text, just in case the image doesn't load. A good option would be "IronSkydive Logo".

It is common to find quotes in _italic_ in different places, so this is what we are going to do. Add the quote in italic (using inline elements) inside the `<aside>` element, with the text "The best experience of our lives".
In a new line, this time using a _block_ level element (`<p>`), add the names of the authors. The names will be "Ariel Quiónes & Gonzalo Manrique, Ironhack Founders".

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_0f0563ef2d64bd9a7bdf5d401bca9c16.png)

<br>

### Section 1

In the first section, we have three different articles. Each has an `<h3>` and a `<p>` tag inside. Let's add a link under each paragraph. This link doesn't need to point anywhere.

<br>

:::info
We can create a link without any specific URL by providing a hash in the `href` attribute:
<br>

```html
<a href="#">Link text</a>
```
:::

<br>

Add three links, one in each section, in this order:

- Learn More
- Watch Video
- Register

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_016b92205b14c5a93d86d324547cf86e.png)

<br>

### Section 2

In this section, we have four different articles that contain information about how a typical day at IronSkydive is structured. Let's add some descriptive icons to each section.

The different icons, in the correct order, are:

- `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironskydive-training.png`
- `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironskydive-get-ready.png`
- `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironskydive-fly.png`
- `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironskydive-jump.png`

Remember to add an alternative descriptive text in the `alt` attribute. Each of the sections will have this format with different images:

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_3aa54eab8bec42f35381b704d5c7b06e.png)

<br>

### Section 3

Let's add the team information in the section. You should have three different articles without any information. Inside each article, you will add the team member name in the **bold** text (but this is something you will worry about when we come to the styling). You can use _block_ level tag, `<h4>` to wrap each name. Under the name, you will have to add the team member's photo. You can find the images here:

- **Harold Rothstein**, `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_c18b1c463b80090894237a262dfdfbad.jpg`
- **Susan Phillips**, `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_a18d6123a7c8e75f7e70a4e59b941093.jpg`
- **Taylor Roberts**, `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_7104a331530d1b0611da55093b7dc421.jpg`

Don't forget to add alternative text in case the image doesn't load. These images are quite big, but we will handle this later on through CSS.

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_845dbf46e21d7bb275bdb5b23ff17aa6.gif)

<br>

To finish this section, let's add a `<hr>` between the paragraph and the team members' information.

### Section 4

_Nothing to add_!

### Footer

First, let's format the address. Right now, all the information is in one line. Let's use `<br>` tags to separate the different sections of the address.

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_cf1a7806a1a921e018aa46c428d67a17.png)

<br>

Finally, add links to all the social networks where the users can follow IronSkydive. You can create empty links (with the hash in the `href` attribute), or add links to the social networks. In both cases, a new tab has to be opened when the users click on the links.

<br>

:::info
:bulb: Use the anchor's [`target`](https://html.com/attributes/a-target/) attribute to open a link in a new tab. (the word _target_ is clickable, so feel free to explore a bit - remember, you don't have to memorize anything, know where to find the answers you need.)
:::

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_27057afe7732d2b6f26ce69eb00a63ec.png)

<br><br>

:heart: **Happy coding!**



# Guided exercise - IronSkydive 🎨 - styling (CSS)

<br>

## Introduction

At this point, you got familiar with Cascading Style Sheets (CSS), and you know how to:

- target elements using tags, classes or ids,
- work with font and text properties,
- add colors to text and background.

Remember to open the **CodePen** you created at the beginning of the exercise to do the different iterations of the exercise.

Let's go!

<br>

## IDs

First, you are going to add four ids, one per each `<section>` you have defined. From top to bottom, the ids should be:

- `general-information`
- `structure`
- `team`
- `schedule`

This is going to help us to identify the different sections. This also created something called [internal links](http://www.yourhtmlsource.com/text/internallinks.html). What happens now if you click on the `<nav>` links at the top of the page? It scrolls down automatically to the section! :white_check_mark:

<br>

## General settings for the whole page

Okay, let's start using the CSS tab inside your CodePen project. We will start with setting up the whole page to use the following rule (copy the snippet at the beginning of the CSS tab):

```css
html,
body {
  margin: 0;
  padding: 0;
}
```

This is going to remove all the elements' `margin` and `padding`, or in simple English, will set them to `0`. Why are we doing this? We are doing this to reset some styles that your browser automatically apply to elements, known as _browser default styles_.

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_603c70d5d3664d3cd0d7829c6b0367cb.png)

<br>

:thought_balloon: Don't worry about what `margin` and `padding` properties are right now, we'll discuss them in a bit.

<br>

## Font and text

### font-family

For the whole IronSkydive website, we are going to use a font called `Roboto`. You can find it in `https://fonts.google.com/`, Google repository that hosts a huge number of fonts. Typically you have to go through a process to embed one of these fonts in your site, but we have simplified it for you.

At the very beginning of the CSS tab in your CodePen, copy the following line:

```css
@import url('https://fonts.googleapis.com/css?family=Roboto+Condensed:700|Roboto:100,300,700');
```

Nothing happens yet. It just adds a reference to two different fonts:

- `Roboto`, with weights of 100, 300, and 700.
- `Roboto Condensed`, with weight 700.

You are going to use both of them on your website. So let's change the font for the entire document. The entire document should have text formatted in the following manner:

- font: `Roboto`.
- size: `10px`.
- line height: `3.5em`.
- weight: `300`.

Remember: we can target elements on which we want to apply some styles using class or id or _tag name_.
You can use `body` tag and add these respective CSS properties to it. Once you have defined the font for the document, let's change the behavior of the headers.

You are using headers from 1 to 5, use a _multi selector_ that will select all of them. Inside this selector, you set the font to `Roboto Condensed`. We will modify the size of the headings in a different selector since each of them will be a different size.

```css
/* CSS multiselector example */
h1,
h2,
h3,
h4,
h5,
h6 {
  /*  define font-family here  */
}
```

The result should be something like this:

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_8772412e132f34f5246213a371f16ea5.png)

<br>

### Text properties

Right now all the fonts have the same size, let's change that. First, let's style the headings by including the following properties:

| Heading | Properties                                                                                                                                                                                         |
| ------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `<h1>`  | Size: `9em` <br> Align: `center` <br> Transform: `uppercase`                                                                                                                                       |
| `<h2>`  | Size: `5em` <br> Align: `center` <br> Transform: `uppercase`                                                                                                                                       |
| `<h3>`  | Size: `4.2em` <br> Align: `center` <br> [Line height](https://developer.mozilla.org/en-US/docs/Web/CSS/line-height): `1em`                                                                         |
| `<h4>`  | Size: `1.5em` <br> [Letter spacing](https://developer.mozilla.org/en/docs/Web/CSS/letter-spacing): `0.4px` <br> [Line height](https://developer.mozilla.org/en-US/docs/Web/CSS/line-height): `1em` |
| `<h5>`  | Size: `1.2em` <br> [Line height](https://developer.mozilla.org/en-US/docs/Web/CSS/line-height): `1em`                                                                                              |

Once you apply these styles to the different headers you have, `<h1>` and `<h2>` need more space between them. Let's add more space by setting the `<h2>` `line-height` property to `4em`.

You have already specified all the text styles you need to have on your website.

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_b0f5f1c39886cbe09c75630ca7706c2a.png)

<br>

Great, now let's add some colors to our website.

<br>

## Colors

<br>

Previously, you used the CSS text properties to change the website's appearance, by adding a custom font and sizes, depending on the tag. Now it is time to give it some color!

When you are developing a website, it is a good practice to keep in mind a table with the different colors you are going to use. In this case, the table is:

| Color     | RGB            | Result                                                                                        |
| --------- | -------------- | --------------------------------------------------------------------------------------------- |
| Blue      | `67, 163, 230` | <div style="background: rgb(67, 163, 230); height: 20px; margin: 0 auto; width: 20px;"></div> |
| Dark Blue | `25, 33, 41`   | <div style="background: rgb(25, 33, 41); height: 20px; margin: 0 auto; width: 20px;"></div>   |
| Text      | `0, 0, 0`      | <div style="background: rgb(0, 0, 0); height: 20px; margin: 0 auto; width: 20px;"></div>      |

This table will help you to communicate with your UX/UI design team. When they tell you to apply the `Dark Blue` as a background color, you will know which color it is immediately.

One by one let's describe the changes you have to apply over the different sections we defined on the first iteration of this exercise. Remember the layout we created:

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_8f778c8cd703db596d5bb22dae089716.jpg)

<br>

Open CodePen in your browser, and let's start!

<br>

### Nav

<br>

The end goal for the `nav` bar is next:

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_065124c74d928a12e32e446b759968e3.png)

<br>

Let's start by adding the color. Add `Dark Blue` as a background color.

It is a good practice to use class selectors instead of using HTML tag selectors to define styles. What if you apply a style to the `nav` tag and in the future, you change it to `header`? You would lose all the styles, and change it one by one in the CSS.

Create a selector in your CSS tab called `.nav-bar`, and assign the style described above. Then, assign the class to the `nav` tag in your HTML.

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_320885335d288348997362c44aa6f6b0.png)

<br>

It is working... kind of. We have to set the color of links to white and if you try to set the property `color: white` inside `.nav-bar` class, it won't work because words/links are wrapped inside `a` tags.

We can go in the direction of creating a new class and attach the class to each `li` item inside `<nav>`, or we can go **DRY** (Don't Repeat Yourself) and avoid creating one more class but instead of that, reference the items we want to target through the existing class `.nav-bar`.

```css
.nav-bar a {
  /*  styles to be added here    */
}
```

<!-- Let's create another class, called `nav-bar-item`, and -->

Change the `color` to _white_, `text-decoration` to _none_, and `font-size` to `2em` in order to get the desired result.

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_e03b2f8983da0df77b6e88f973cfc0c5.png)

<br>

In the next iterations, you are going to complete the menu. You are ready to move to the following section.

<br>

### Header

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_e80b0ee85c8f2fb8126befe68b152ab2.png)

<br>

Don't be afraid! It is easier than it seems. First of all, you have to set the [background image](https://developer.mozilla.org/en/docs/Web/CSS/background-image?v=control). The properties of the background image are:

- **url:** `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironhack-skydive-background.jpg`.
- **position:** `0 0`.
- **repeat:** `no-repeat`
- **size:** `cover`.

Remember you should create a class, in this case `header`, and assign it to the `header` tag in your HTML to use this style. Now, just set the `header`'s height to `650px`.

The next step is to change the `h2` color to white, and then add some [`text-shadow`](https://developer.mozilla.org/en/docs/Web/CSS/text-shadow) to it. The `text-shadow` property should have as a value `#020819 8px -20px 9px`.

To finish up this section, change the font-size of the quote. Set it to `2.5em`. Create a `quote` class to do that, and add the class to the `aside` tag in the HTML.

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_c03f57b39ea0d76161156d6e58d91307.png)

<br>

### Section 1

In one of the previous iterations, you added a `general-information` _id_ to this section. Our end goal for this section is:

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_505f90aabf6c0d4e03b4216c07c615f8.png)

<br>

Create a class selector `dark-background`, that applies the following properties:

- background color: dark blue (check out the table at the beginning of this iteration).
- color: white.

Once you have created the class in your CSS, add it to the section. After applying the class, you can see that the text in the `<p>` is tiny, and is not centered. Let's solve this problem.

First, to each paragraph inside the `general-information` section, add a `text` class.

<!-- Then create a multiple selector, that selects all the elements with a `.text` class inside the `#general-information` element. -->

This selector should have the following CSS properties:

- Font size: `2em`.
- Font weight: `100`.
- Text Align: `center`.

Much better. Let's finish this section by adding some styles to the links. The links will look like buttons, and all the links of this section will have the same appearance. It means that you should create a class that applies the necessary CSS properties to a link to look like a button.

<br>

:::info
:bulb: **Why wouldn't we use a button?** Check out [this very concise StackOverflow answer](https://stackoverflow.com/a/25350722/4624718) for a good rule of thumb.
:::

<br>

Let's create a `link-btn` class with the following properties:

- background color: blue (check out the table at the beginning of this iteration).
- color: white.
- font-family: `Roboto Condensed`.
- font size: `2em`.
- [Letter Spacing](https://developer.mozilla.org/en/docs/Web/CSS/letter-spacing): `0.5px`.
- text-align: `center`.
- text-decoration: `none`.

Add the class to the three links you have in the section.

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_7847968ca22bceb75dac295214859d36.png)

<br>

Hmm... It seems we need a way to rearrange our elements and put them in certain positions. This will be the objective of one of the next iterations.

Let's move to the next section.

### Section 2

In the second section, we have added a `structure` id. In this section, you just have to set up the font size and alignment properties.

<!-- You will also remove the `img` width property, and set it in the CSS. -->

Create a `service-box` class in the CSS, with the following properties:

- Font Size: `1.7em`.
- Text Align: `center`.

Assign this class to each `article` inside the `structure` section.

Now, create new multiple selectors for all the `img` classes, inside the `service-box` class.

:+1: Spoiler: Similar what you already did with the links in the navbar, here we will have the following:

```css
.service-box img {
  /*  styles to be added  */
}
```

Add a property inside to set the width of these images to `125px`.

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_85b85fdc98c951967b3554ee821cbfaa.png)

<br>

### Section 3

The most important goal in writing quality CSS is to create classes we can reuse. In this section, we again have dark blue as the background color. You previously have created a `dark-background` class and now add this class to the `team` section.

Now, you have to create two different classes — one for the text of the section, and another one for the team member names. The first class, `section-text`, will have set the font size to `1.9em`, and the text should be aligned to the `center`.

On the other hand, the `member-name` class will set the font size to `1.5em`, with a font weight of `700`. Add the first class to the `p` in the HTML, and the second class to all the `h4` tags.

To avoid properties overwriting other classes, create a multiple selector to set these classes specifically inside the `team` id element:

```css
#team .section-text {
}
#team .member-name {
}
```

Also, let's take care of the images in this section. As we can see they are super large. Let's use multiple selectors to target the `img` tags inside `#team` and set the:

- width to 250px and
- height to 180px.

:+1: Spoiler:

```css
#team img {
  /* styles to be added here */
}
```

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_dbe16d63517310a82a988f9f13df4867.png)

<br>

### Section 4

_Nothing to do here...yet!_

### Footer

Again, we have a dark background and white text. Add the `dark-background` class to the `footer` tag in the HTML. Create a `footer` class and add it as a second class on the `<footer>` tag. Use this class to center all the text inside this element and to set up the font size to `1.9em`.

:+1: Spoiler: To add a second class, you have to do the following:

```html
<!-- ... -->

<footer class="dark-background footer">
  <!-- ... -->
</footer>
```

Now, create a new class - `address`, and assign it to the `address` HTML tag. In this class, define:

- font style: `normal`.
- font size: `0.8em`.

We are almost done. The same as we targeted all the links inside the nav bar (using multiple selector approach), here let's target all the links inside footer and their styles:

- color: blue (check out the table at the beginning of this iteration).
- text-decoration: none.

Assign this class to each element inside the list you have in the footer.

:+1: Spoiler: The way to go about this is the next:

```css
.footer a {
  /* styles to be added here */
}
```

And one, the last thing for this iteration is to remove the dots from the list that is displaying social media links. You can target the `ul` tag inside the footer and set the `list-style` property to _none_. So here it is!

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_791457cbe452066c3123de22f4182eb8.png)

<br><br>

:heart: **Happy coding!**
