# fill-mask-web-component

A HTML web component for filling missing words in sentences.

This component is ideal for making interactive quizzes where the reader needs to fill in a word (i.e. fill in the missing song lyric, fill in the missing word from a quote).

[Try the component](https://capjamesg.github.io/fill-mask-web-component/).

## Demo

Here is an example of the component in use:

https://github.com/capjamesg/fill-mask-web-component/assets/37276661/216ec4ec-2701-4311-a039-72497f3d12dd

## Setup

To use this component, first clone this repository:

```
git clone https://github.com/capjamesg/fill-mask-web-component
cd fill-mask-web-component/
```

Copy the `fillmask.js` file onto your own website.

Add the following code to theweb page where you want to use the component, before you want to use the component:

```html
<script src="./path/to/fillmask.js"></script>
```

You can then add the component. To do so, add the following code:

```html
<fill-mask text="The question pounds my head, what's a lifetime of [word]." answer="achievement"></fill-mask>
```

Replace the `text` attribute with the text you want to add to the page. Use `[word]` to indicate what word you want to mask. You can only specify one word to mask. Then, set the `answer` attribute to be equal to the missing word.

## License

This project is licensed under an [MIT license](LICENSE).
