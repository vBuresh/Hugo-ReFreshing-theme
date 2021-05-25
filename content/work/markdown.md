---
title: Markdown
# subtitle: continuer of the title in a two words
date: 2021-05-25T12:19:37+03:00
Lastmod: 2021-05-25T12:19:37+03:00
draft: false
# description: "- дополнение к заголовку (подзаголовок)"
# summary: краткое изложение - зачем читать сие
# summaryImage: images/
author:
  given_name: Vladimir
  family_name: Buresh
  display_name: wBuresh
categories:
  - "webDev"
tags:
  - Markdown
---

Markdown (маркда́ун) — это одним из самых распрострненных языков разметки в мире. Его отличает необычайная логичность, постота и легкость. Элементы форматирования помещаюся непостредственно в текст документа в соответствии с синтаксисом (от греч. 'строй, порядок') Markdown. При этом полностью сохраняется читаемость документа человеком. Кроме того достигается высокая готовность текста к машинной обработке с целью преобразования в многочисленные языки и форматы, в том числе: HTML, Rich Text, .odt, .txt PDF и пр.

Markdown создан Джоном Грубером [John Gruber](https://daringfireball.net/projects/markdown/) и Аароном Шварцем [Aaron Swartz](https://en.wikipedia.org/wiki/Aaron_Swartz) в 2004 году. [Подробнее см. материал в Википедии...](https://ru.wikipedia.org/wiki/Markdown).

О высокой популярности Markdown свидетельствует обалие информации о нем в интернете. Вот, пожалуй, самые востребованные пособия по Markdown:  

- [Markdown By John Gruber](https://daringfireball.net/projects/markdown/)
- [GitHub: markdown-guide](https://github.com/mattcone/markdown-guide)
- [site: Markdown Guide](https://www.markdownguide.org/)

Using Markdown is different than using a WYSIWYG editor. In an application like Microsoft Word, you click buttons to format words and phrases, and the changes are visible immediately. Markdown isn’t like that. When you create a Markdown-formatted file, you add Markdown syntax to the text to indicate which words and phrases should look different.
Применение Markdown отличается от использования редактора WYSIWYG. Например, в текстовых процесорах, таких, как libreJffise, Microsoft Word и др. для форматирования слов и фраз пользователь нажимает соответствующие кнопки, и изменения сразу видны, а в Markdown пользователь добавляет к тексту опредекленные синтаксисом Markdown символы, чтобы указать, как должны выглядеть указаные ими элементы текста и документа.

For instance, to denote a heading, you add a number sign before it (e.g., # Heading One). Or to make a phrase bold, you add two asterisks before and after it (e.g., **this text is bold**). It may take a while to get used to seeing Markdown syntax in your text, especially if you’re accustomed to WYSIWYG applications. The screenshot below shows a Markdown file displayed in the Atom text editor.

Например, чтобы обозначить заголовок, вы добавляете перед ним знак числа (например, # Заголовок один). Или, чтобы выделить фразу жирным шрифтом, добавьте две звездочки до и после нее (например, ** этот текст выделен жирным шрифтом **). Чтобы привыкнуть к синтаксису Markdown в тексте, может потребоваться некоторое время, особенно если вы привыкли к приложениям WYSIWYG. На снимке экрана ниже показан файл Markdown, отображаемый в текстовом редакторе Atom.




[What is Markdown?](https://www.markdownguide.org/getting-started/#what-is-markdown)






Несмотря на

Markdown Guide - это бесплатное справочное руководство с открытым исходным кодом, в котором объясняется, как использовать Markdown, простой и легкий в использовании язык разметки, который можно использовать для форматирования практически любого документа.

The Markdown Guide is a free and open-source reference guide that explains how to use Markdown, the simple and easy-to-use markup language you can use to format virtually any document.
    Markdown Guide - это бесплатное справочное руководство с открытым исходным кодом, в котором объясняется, как использовать Markdown, простой и легкий в использовании язык разметки, который можно использовать для форматирования практически любого документа., Руководство Markdown является свободным и открытым исходным кодом справочное руководство, которое объясняет, как использовать Markdown, простой и легкий в использовании язык разметки вы можете использовать для форматирования практически любой документ.



The Markdown Guide is a free and open-source reference guide that explains how to use Markdown, the simple and easy-to-use markup language you can use to format virtually any document.

Many Markdown applications allow you to use HTML tags in Markdown-formatted text. This is helpful if you prefer certain HTML tags to Markdown syntax. For example, some people find it easier to use HTML tags for images. Using HTML is also helpful when you need to change the attributes of an element, like specifying the color of text or changing the width of an image.

To use HTML, place the tags in the text of your Markdown-formatted file.

```html
This **word** is bold. This <em>word</em> is italic.
```

The rendered output looks like this:

This word is bold. This word is italic.

### HTML в документах Markdown

Источник: [HTML Best Practices](https://www.markdownguide.org/basic-syntax/#html-best-practices)

По соображениям безопасности не все приложения Markdown поддерживают HTML в документах Markdown. В случае сомнений проверьте документацию к вашему приложению Markdown. Некоторые приложения поддерживают только подмножество HTML-тегов.

Используйте пустые строки для отделения HTML-элементов уровня блока, таких как `<div>, <table>, <pre>` и `<p>`, от окружающего содержимого. Старайтесь не делать отступы в тегах табуляцией или пробелами - это может помешать форматированию.

Синтаксис Markdown нельзя использовать внутри блочных HTML-тегов. Например, `<p>italic and **bold**</p>` работать не будут.
