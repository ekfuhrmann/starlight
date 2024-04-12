---
title: ⚠️ Details styles demo page ⚠️
---

:::danger
// TODO(HiDeoo) Remove this page
:::

## Basics

The following is a basic `<details>` element with no block content:

<details>
<summary>This is the summary</summary>
This is the details content
</details>

The following is a basic `<details>` element with block content:

<details>
<summary>This is the summary</summary>

This is the details content

</details>

## Opened by default

The following is a `<details>` element opened by default:

<details open>
<summary>This is the summary</summary>
This is the details content
</details>

## Long summary

The following is a `<details>` element with a very long summary:

<details>
<summary>This is the very very very very very very very very very very very very very very very very very very very very very very very very very very very very very very very very very long summary</summary>
This is the details content
</details>

## Long content

The following is a `<details>` element with a very long content:

<details>
<summary>This is the summary</summary>

This is the details content

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas euismod ante lorem, quis posuere massa sodales id. Donec a dapibus nisi, id volutpat lorem. Aenean eleifend nisl at ex feugiat, at vulputate lorem luctus. Aliquam eget accumsan ipsum. Maecenas ut elit hendrerit, sodales leo at, tincidunt elit. Nullam ut venenatis libero. In vel molestie tellus. Suspendisse vitae nibh in felis faucibus aliquet. Nunc tortor enim, pellentesque sit amet justo eget, auctor elementum enim. Nam posuere et ipsum lobortis porttitor. Proin consectetur ullamcorper augue, a fermentum neque dapibus eget. Praesent feugiat orci vulputate turpis mattis, eget placerat mi volutpat.

Maecenas vehicula orci metus, quis dapibus turpis suscipit vitae. Nullam velit ante, convallis fermentum massa a, condimentum mattis lorem. Nunc interdum consequat mollis. Suspendisse semper diam tellus. Maecenas mollis congue mi, eu hendrerit dui hendrerit sed. Aliquam quis ornare dolor. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.

Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Sed posuere arcu ut leo ultrices, in volutpat leo eleifend. Proin facilisis tempus maximus. Sed eu nulla ultricies, accumsan libero sed, commodo nunc. Curabitur sit amet metus vitae erat laoreet cursus et ut magna. Nam euismod justo a orci sagittis molestie. Phasellus et interdum ipsum, sed egestas ligula. Vestibulum congue eros ac neque posuere molestie. Nunc id enim aliquet, vestibulum diam at, fermentum justo.

Duis ac mauris purus. Etiam viverra nisi vel facilisis eleifend. Ut dapibus, eros ac cursus faucibus, augue mi facilisis lacus, ut ullamcorper arcu diam eu nulla. Praesent tincidunt placerat augue eget cursus. Integer magna felis, malesuada in interdum eu, efficitur vel dolor. In feugiat nisl sit amet pharetra ullamcorper. Quisque odio ante, convallis a lectus id, consectetur finibus enim. Curabitur pretium quam ut lectus tristique, ac ornare lorem varius. Ut maximus aliquet est vitae hendrerit. In vitae massa mattis, volutpat dui sagittis, semper arcu. In a ligula tincidunt, elementum nisi ut, tincidunt odio. Etiam accumsan massa a justo convallis blandit. Integer in felis arcu. Nullam id felis et velit blandit convallis vitae a turpis. Nunc vitae erat ac ipsum mattis rutrum nec ut justo. Mauris ullamcorper id metus nec pretium.

Donec purus nibh, ornare ac sagittis porta, porta ac neque. Donec efficitur dictum nibh et hendrerit. Mauris gravida mollis leo posuere posuere. In hac habitasse platea dictumst. Interdum et malesuada fames ac ante ipsum primis in faucibus. Aenean sit amet massa felis. Fusce lectus neque, auctor quis est et, interdum lobortis ante. Nulla aliquet euismod libero, sit amet maximus orci mattis eu. Nullam sed cursus felis. Sed dapibus faucibus dolor, id volutpat eros varius a.

</details>

## Interleaved content

The following are two `<details>` elements with a code block in between:

<details>
<summary>This is the summary</summary>
This is the details content
</details>

```js
console.log('some content in between');
```

<details>
<summary>This is the summary</summary>
This is the details content
</details>

## Markdown content

The following is a `<details>` element with markdown content:

<details>
<summary>This is the summary</summary>

This is the details content

```ts
console.log('Hello world');
```

This is `a` paragraph.

:::note
This is a note
:::

</details>

## Uncontrolled accordion

The following are `<details>` elements forming an uncontrolled accordion, where each `<details>` element can be opened or closed independently:

<details>
<summary>This is the summary (1)</summary>
This is the details content (1)
</details>

<details>
<summary>This is the summary (2)</summary>
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas euismod ante lorem, quis posuere massa sodales id. Donec a dapibus nisi, id volutpat lorem. Aenean eleifend nisl at ex feugiat, at vulputate lorem luctus. Aliquam eget accumsan ipsum. Maecenas ut elit hendrerit, sodales leo at, tincidunt elit. Nullam ut venenatis libero. In vel molestie tellus. Suspendisse vitae nibh in felis faucibus aliquet. Nunc tortor enim, pellentesque sit amet justo eget, auctor elementum enim. Nam posuere et ipsum lobortis porttitor. Proin consectetur ullamcorper augue, a fermentum neque dapibus eget. Praesent feugiat orci vulputate turpis mattis, eget placerat mi volutpat.
</details>

<details>
<summary>This is the summary (3)</summary>
Maecenas vehicula orci metus, quis dapibus turpis suscipit vitae. Nullam velit ante, convallis fermentum massa a, condimentum mattis lorem. Nunc interdum consequat mollis. Suspendisse semper diam tellus. Maecenas mollis congue mi, eu hendrerit dui hendrerit sed. Aliquam quis ornare dolor. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
</details>

## Controlled accordion

The following are `<details>` elements forming an controlled accordion, where only one `<details>` element can be opened at a time:

:::caution
Note that this feature is not supported in Firefox.
:::

<details name="controlled-details">
<summary>This is the summary (1)</summary>
This is the details content (1)
</details>

<details name="controlled-details">
<summary>This is the summary (2)</summary>
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas euismod ante lorem, quis posuere massa sodales id. Donec a dapibus nisi, id volutpat lorem. Aenean eleifend nisl at ex feugiat, at vulputate lorem luctus. Aliquam eget accumsan ipsum. Maecenas ut elit hendrerit, sodales leo at, tincidunt elit. Nullam ut venenatis libero. In vel molestie tellus. Suspendisse vitae nibh in felis faucibus aliquet. Nunc tortor enim, pellentesque sit amet justo eget, auctor elementum enim. Nam posuere et ipsum lobortis porttitor. Proin consectetur ullamcorper augue, a fermentum neque dapibus eget. Praesent feugiat orci vulputate turpis mattis, eget placerat mi volutpat.
</details>

<details name="controlled-details">
<summary>This is the summary (3)</summary>
Maecenas vehicula orci metus, quis dapibus turpis suscipit vitae. Nullam velit ante, convallis fermentum massa a, condimentum mattis lorem. Nunc interdum consequat mollis. Suspendisse semper diam tellus. Maecenas mollis congue mi, eu hendrerit dui hendrerit sed. Aliquam quis ornare dolor. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
</details>

## Nested details

The following is a `<details>` element with a nested `<details>` element:

<details>
<summary>This is the summary</summary>

This is the details content

<details>
<summary>This is the nested summary</summary>
This is the nested details content
</details>

And some content after the nested details

</details>

## `not-content` class

<div class="not-content">

<p>The following is a <code>&lt;details&gt;</code> element wrapped with the <code>not-content</code> CSS class:</p>

<br>

<details>
<summary>This is the summary</summary>
This is the details content
</details>

</div>

## RTL

The following is a `<details>` element nested in a block in RTL:

<div dir="rtl">

<details>
<summary>This is the summary</summary>
This is the details content
</details>

</div>

The following is a `<details>` element in RTL:

<details dir="rtl">
<summary>This is the summary</summary>
With a summary and some details not in a paragraph
</details>

## Asides

The following are `<details>` elements nested in asides:

:::note
This is the note aside content

<details>
<summary>This is the summary</summary>
This is the details content
</details>

:::

:::tip
This is the tip aside content

<details>
<summary>This is the summary</summary>
This is the details content
</details>

:::

:::caution
This is the caution aside content

<details>
<summary>This is the summary</summary>
This is the details content
</details>

:::

:::danger
This is the danger aside content

<details>
<summary>This is the summary</summary>
This is the details content
</details>

:::