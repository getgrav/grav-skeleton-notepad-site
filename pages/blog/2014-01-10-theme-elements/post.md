---
layout: post
title: "Theme Elements"
description: Theme Elements will save you tons of time working on the site content. Now you'll be able to create complex layouts within minutes.
taxonomy:
  tag: [Grav, Author]
image: picture-38.jpg
---
I've put together a little post to introduce you to the Notpead theme and get you started with Markdown. Go ahead and edit this post to get going and learn how it all works!

# ELEMENTS

Writing in markdown is really easy. In any editor like notepad, you simply write as you normally would. Where appropriate, you can use formatting shortcuts to style your content. 

## LISTS

For example, a list:

- Item number one
- Item number two
	- A nested item
- A final item

or with numbers!

1. Remember to buy some milk
1. Drink the milk
1. Tweet that I remembered to buy the milk, and drank it

## LINKS

Want to link to a source? No problem. If you put the url in this format, like `[http://getgrav.org/](http://getgrav.org/)` - it'll automatically be linked up like [http://getgrav.org/](http://getgrav.org/). But if you want to customize your anchor text, you can do that too! Here's a link to the [my website](http://getgrav.org/ "Grav Website"). Neat.

## WHAT ABOUT IMAGES? ##

Images work too! And they are responsive! Already know the URL of the image you want to include in your article? Images are responsive and uses lightbox. 

![Photo16](photo16.jpg)
![Photo13](photo13.jpg)
![Photo19](photo19.jpg)

Check out [this post]({{ site.url }}/articles/sample-post-images/) to learn about including images in your post.

## AND VIDEOS? ##

Video embeds are responsive and scale with the width of the main content block with the help of [FitVids](http://fitvidsjs.com/).

## EQUATIONS

Are you an engineer? Or a mathematician? Want to post some equations in your Grav blog for the world to see? No problem. Wrapping your equation between `$$...$$` will produce something like this:

<math display="block">
  <mstyle>
    <mi>f</mi>
    <mrow>
      <mo>(</mo>
      <mi>a</mi>
      <mo>)</mo>
    </mrow>
    <mo>=</mo>
 <mfrac>
        <mn>1</mn>
        <mrow>
          <mn>2</mn>
          <mi>π<!-- π --></mi>
          <mi>i</mi>
        </mrow>
      </mfrac>
    <msub>
      <mo>∮</mo>
      <mrow>
        <mi>γ</mi>
      </mrow>
    </msub>
    <mfrac>
      <mrow>
        <mi>f</mi>
        <mo>(</mo>
        <mi>z</mi>
        <mo>)</mo>
      </mrow>
      <mrow>
        <mi>z</mi>
        <mo>−</mo>
        <mi>a</mi>
      </mrow>
    </mfrac>
    <mi>d</mi>
    <mi>z</mi>
  </mstyle>
</math>

## THE LOGO ##

Not sure which image you want to use yet? That's ok too. Leave yourself a descriptive placeholder and keep writing. Come back later and change the image in the user/config/site.yml.

## ICONS

This theme includes over 360 fontawesome icons. To use an icon go to [Fontawesome](http://fontawesome.io/3.2.1/icons/) website and click on the desired icon to find the appropriate tag.

<div class="text-center">
<i class="icon-cogs"></i> <i class="icon-youtube-sign"></i> <i class="icon-thumbs-up"></i> <i class="icon-coffee"></i> <i class="icon-cloud-upload"></i> <i class="icon-camera"></i> <i class="icon-comments-alt"></i> <i class="icon-eye-open"></i> <i class="icon-heart"></i> <i class="icon-globe"></i>
</div>

## QUOTING ##

Sometimes a link isn't enough, you want to quote someone on what they've said. It was probably very wisdomous. Is wisdomous a word? Find out in a future release when I introduce spellcheck! For now - it's definitely a word.

> Wisdomous - it's definitely a word.
><small><cite title="Hossain Mohd Faysal">Hossain Mohd Faysal</cite></small>

## READY FOR A BREAK? ##

Throw 4 or more dashes down on any new line and you've got yourself a fancy new divider. Aw yeah.

----

That should be enough to get you started. Have fun - and let us know what you think [@getgrav](https://twitter.com/getgrav).