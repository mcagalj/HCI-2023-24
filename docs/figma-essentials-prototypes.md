# Figma essentials and prototypes <!-- omit in toc -->

We will cover the basics of creating low-fidelity and high-fidelity prototypes in Figma. Throughout the process, we will demonstrate key Figma essentials and features, including **components, auto layout, prototypes, scaling and constraints**. Please note that this is a quick crash course and not a comprehensive course on Figma. Its goal is to provide students with a nudge in the right direction.

- [Information architecture (IA)](#information-architecture-ia)
- [Sitemap](#sitemap)
- [Wireframes](#wireframes)
  - [Desktop: Home Page](#desktop-home-page)
- [Low Fidelity Prototype](#low-fidelity-prototype)
  - [Desktop: Homepage](#desktop-homepage)
- [High Fidelity Prototype](#high-fidelity-prototype)
  - [Desktop: Homepage](#desktop-homepage-1)
- [Figma essentials](#figma-essentials)
  - [Color palette and local color styles](#color-palette-and-local-color-styles)
  - [Layout Grid](#layout-grid)
  - [Figma components and component variants](#figma-components-and-component-variants)
  - [Figma auto layout](#figma-auto-layout)



## Information architecture (IA)

Based on previously discovered typical users and typical tasks to be supported by your digital product, and before creating wireframes and prototypes, you should determine the best way to structure, label and organize information in your digital product/application. This will represent a blueprint of your application/website and is known as Information Architecture (IA). How you organize the information in your digital product will directly affect how users interact with it.

> Information architecture (IA) helps users answer the question *“Where am I and where can I find information/service I’m looking for?”*.
> 

Information architecture plays a crucial role in shaping sitemaps, wireframes, hierarchies, navigation, and metadata.

Some techniques used to design and evaluate information architecture of a digital product:

- User interviews
- [User Personas](https://youtu.be/XnG4c4gXaQY?si=Y9kI7TxMG6iU7uHb)
- [Card Sorting](https://careerfoundry.com/en/blog/ux-design/what-is-card-sorting/)

## Sitemap

A sitemap is a visual representation of the structure and organization of a website or digital product. It outlines the hierarchy of pages and how they are interconnected.

> Sitemaps are informed by information architecture and are related to URL structure decisions.

![Sitemap](/docs/figma-essentials-prototypes/sitemap.png)

## Wireframes

### Desktop: Home Page

![Wireframe](/docs/figma-essentials-prototypes/wireframe-desktop-homepage.png)

## Low Fidelity Prototype

### Desktop: Homepage

![Low Fidelity Prototype](/docs/figma-essentials-prototypes/lofi-desktop-homepage.png)

## High Fidelity Prototype

### Desktop: Homepage

![High Fidelity Prototype](/docs/figma-essentials-prototypes/hifi-desktop-homepage.png)

## Figma essentials

### Color palette and local color styles

We will create our color palette based on brand colors (found in the company logo).

- [ ]  Create a frame titled Color palette and put the logo inside.
- [ ]  Open Foundation: Color Generator plugin and create your palette.
- [ ]  Add colors from the palette to Local styles by using Create Styles button.

### Layout Grid

- [ ]  Create a new frame, set the size and give it a meaningful name.
- [ ]  Add 12-columns equally spaced columns using Layout grid.
- [ ]  Insert the logo, and resized it using Scale tool.

### Figma components and component variants

- [ ]  Create a set of text boxes representing the main menu (select font, color, align and distribute evenly, etc.).
- [ ]  To save the font, you can create Text styles as in the case of colors.

> Notice how repetitive and time-consuming it can be to align menu elements manually each time. We will show later how Auto Layout feature makes this much easier and less time consuming.
> 
- [ ]  Let us highlight one menu item as being active (e.g., using a background rectangle). What if you decide to change the text of the active item? Does it fit the rectangle? What if you decide to highlight another item or update the font weight of all items? This process quickly escalates and becomes tedious. [Figma components and component variants](https://help.figma.com/hc/en-us/articles/360038662654-Guide-to-components-in-Figma) come to rescue here.

- [ ]  Create a master component representing a single menu item. Delete the existing menu and replace create the new by creating instances of the master component.
- [ ]  Try to update some aspect of the master component. What do you observe? (Note: the component instances do not resize yet with the text - we will solve this later with Auto Layout).
- [ ]  Let us finally create a component variant that represents an active state of the item. Try to apply it to your menu.

### Figma auto layout

- [ ]  Add headline and subheadline; if lacking inspiration, consult ChatGPT.
- [ ]  Try to group and align elements using Auto layout which behaves similar to the CSS Flexbox one-dimensional layout model.
