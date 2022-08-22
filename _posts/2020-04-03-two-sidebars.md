---
layout: 'two-sidebar'
title: Options
permalink: /two-sidebar/
---
Basic light and dark mode support is included. Colors are also provided for your own customization.

- toc
{: toc }

## Dark mode

**Dark mode is enabled automatically** via CSS media query—you'll find the source code for this in the `_sass/_variables.scss` stylesheet. If you're familiar with CSS custom properties, you can also use this method to build your own color schemes.

[Read more about using CSS dark mode](https://markdotto.com/2018/11/05/css-dark-mode/) via media queries like this:

```scss
// Example media query to detect dark mode
@media (prefers-color-scheme: dark) {
  // ...
}
```

## Creating themes

If you want to make your own color schemes, modify the CSS variables in the `_sass/_variables.scss` stylesheet with a scoped data attribute or class name.

For example, below we've created the beginnings of a blue theme:

```scss
// Example blue theme
[data-theme="blue"] {
  --body-bg: var(--blue);
  --body-color: #fff;
}
```

Then, apply the theme by adding `data-theme="blue"` to the `<html>` element.

## Colors

Change your site styles by modifying the source code with these CSS custom properties. Poole's colors come from the [Open Color project](https://yeun.github.io/open-color/).

<dl class="colors">
  <dt style="background-color: #fa5252;"></dt>
  <dd>
    <strong>var(--red)</strong><br>
    #fa5252
  </dd>
  <dt style="background-color: #e64980;"></dt>
  <dd>
    <strong>var(--pink)</strong><br>
    #e64980
  </dd>
  <dt style="background-color: #be4bdb;"></dt>
  <dd>
    <strong>var(--grape)</strong><br>
    #be4bdb
  </dd>
  <dt style="background-color: #7950f2;"></dt>
  <dd>
    <strong>var(--purple)</strong><br>
    #7950f2
  </dd>
  <dt style="background-color: #4c6ef5;"></dt>
  <dd>
    <strong>var(--indigo)</strong><br>
    #4c6ef5
  </dd>
  <dt style="background-color: #228be6;"></dt>
  <dd>
    <strong>var(--blue)</strong><br>
    #228be6
  </dd>
  <dt style="background-color: #15aabf;"></dt>
  <dd>
    <strong>var(--cyan)</strong><br>
    #15aabf
  </dd>
  <dt style="background-color: #12b886;"></dt>
  <dd>
    <strong>var(--teal)</strong><br>
    #12b886
  </dd>
  <dt style="background-color: #40c057;"></dt>
  <dd>
    <strong>var(--green)</strong><br>
    #40c057
  </dd>
  <dt style="background-color: #fab005;"></dt>
  <dd>
    <strong>var(--yellow)</strong><br>
    #fab005
  </dd>
  <dt style="background-color: #fd7e14;"></dt>
  <dd>
    <strong>var(--orange)</strong><br>
    #fd7e14
  </dd>
</dl>

## Gray colors

There are also ten grayscale colors to choose from.

<dl class="colors">
  <dt style="background-color: #f8f9fa;"></dt>
  <dd>
    <strong>var(--gray-000)</strong><br>
    #f8f9fa
  </dd>
  <dt style="background-color: #f1f3f5;"></dt>
  <dd>
    <strong>var(--gray-100)</strong><br>
    #f1f3f5
  </dd>
  <dt style="background-color: #e9ecef;"></dt>
  <dd>
    <strong>var(--gray-200)</strong><br>
    #e9ecef
  </dd>
  <dt style="background-color: #dee2e6;"></dt>
  <dd>
    <strong>var(--gray-300)</strong><br>
    #dee2e6
  </dd>
  <dt style="background-color: #ced4da;"></dt>
  <dd>
    <strong>var(--gray-400)</strong><br>
    #ced4da
  </dd>
  <dt style="background-color: #adb5bd;"></dt>
  <dd>
    <strong>var(--gray-500)</strong><br>
    #adb5bd
  </dd>
  <dt style="background-color: #868e96;"></dt>
  <dd>
    <strong>var(--gray-600)</strong><br>
    #868e96
  </dd>
  <dt style="background-color: #495057;"></dt>
  <dd>
    <strong>var(--gray-700)</strong><br>
    #495057
  </dd>
  <dt style="background-color: #343a40;"></dt>
  <dd>
    <strong>var(--gray-800)</strong><br>
    #343a40
  </dd>
  <dt style="background-color: #212529;"></dt>
  <dd>
    <strong>var(--gray-900)</strong><br>
    #212529
  </dd>
</dl>

<p>Phasellus quam turpis, feugiat sit amet ornare in, hendrerit in lectus.
Praesent semper mod quis eget mi. Etiam eu ante risus. Aliquam erat volutpat.
Aliquam luctus et mattis lectus sit amet pulvinar. Nam turpis nisi
consequat etiam lorem ipsum dolor sit amet nullam.</p>

<h3>And Yet Another Subheading</h3>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas ac quam risus, at tempus
justo. Sed dictum rutrum massa eu volutpat. Quisque vitae hendrerit sem. Pellentesque lorem felis,
ultricies a bibendum id, bibendum sit amet nisl. Mauris et lorem quam. Maecenas rutrum imperdiet
rhoncus dui quis euismod. Maecenas lorem tellus, congue et condimentum ac, ullamcorper non sapien.
Donec sagittis massa et leo semper a scelerisque metus faucibus. Morbi congue mattis mi.
Phasellus sed nisl vitae risus tristique volutpat. Cras rutrum commodo luctus.</p>

<p>Phasellus odio risus, faucibus et viverra vitae, eleifend ac purus. Praesent mattis, enim
quis hendrerit porttitor, sapien tortor viverra magna, sit amet rhoncus nisl lacus nec arcu.
Maecenas tortor mauris, consectetur pellentesque dapibus eget, tincidunt vitae arcu.
Vestibulum purus augue, tincidunt sit amet iaculis id, porta eu purus.</p>