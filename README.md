# General CSS / HTML exercises

## Installation

Run `npm install`

## Usage

To run the live server, run `npm run serve`

## Notice

I've already added some styles and margin to give the `<div>`, `<h1>` and `<p>` tags better visibility. This is by design.

## Task

## Task 1

#### Aligning block elements

1. Create a `<div>` element
2. Give it a width of `50%`
3. Give it a height of `200px`
4. Centre it on the page

## Task 2

#### Aligning text

1. Create a `<div>` element

2. Inside the `<div>` element, create a `<p>` element, with dummy text

3. Write some CSS which **only** affects the `<p>` element and causes it to align to the centre of the page.

## Task 3

#### Using inline-block

1. Paste the following HTML code:

```
<div>
	<div></div>
	<div></div>
</div>
```

2. Give the 2 nested `<div>` elements a height of `100px`

3. Make it so that the nested `<div>` elements appear side by side, rather than on top of each other

4. Give the nested `<div>` elements a background color of your choice, and a margin which will prevent them from appearing too close to each other

5. Adjust the height of the first nested `<div>` element, so that it is `200px`.

> Have a look at the page. Notice anything strange? You should see the second `<div>` element aligned to the bottom of the parent container (if you don't, go back to the previous steps to see where you went wrong).

Research: [https://developer.mozilla.org/en-US/docs/Web/CSS/vertical-align](https://developer.mozilla.org/en-US/docs/Web/CSS/vertical-align)

6. To fix this, apply the CSS `vertical-align: top` to the child container.

## Task 4 ##

1. Paste the following HTML code:

```
<div>
	<div>
		<div></div>
	</div>
</div>
```

2. Using the child combinator selector (I prefer the name **first child selector**), write some CSS to target the first nested `<div>` but not the second.

Research: [https://developer.mozilla.org/en-US/docs/Web/CSS/Child_combinator](https://developer.mozilla.org/en-US/docs/Web/CSS/Child_combinator)

## Task 5 ##

1. Paste the following HTML code:

```
<div>
	<div>
		<div></div>
	</div>
</div>
```

2. Using the descendant combinator selector (I normally call this just the **descendant selector**), write some CSS to target the **all** the `<div>`

Research: [https://developer.mozilla.org/en-US/docs/Web/CSS/Descendant_combinator](https://developer.mozilla.org/en-US/docs/Web/CSS/Descendant_combinator)

## Task 6 ##

1. Taking the above as an example, use a type selector (I call these element selectors) to apply a border of `1px` width and a colour of your choice to all `<div>` and `<p>` and `<h1>` elements.

Research: [https://developer.mozilla.org/en-US/docs/Web/CSS/Type_selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/Type_selectors)
