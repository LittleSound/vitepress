# Vitepress Collapsible Sidebar (alpha) 📝💨

add support for collapsible multi-level sidebar

> This is the function of PR [#1360](https://github.com/vuejs/vitepress/issues/1360)

## Use

> package.json

```ts
  "vitepress": "npm:vitepress-collapsible-sidebar@1.0.0-alpha.17.8",
```

## Demo

collapsed

![collapsed](https://user-images.githubusercontent.com/19204772/190911974-b25d7e93-6b47-4062-98ae-23cfa303229e.png)

expand

![expand](https://user-images.githubusercontent.com/19204772/190912002-bffe8eb3-7f6a-47ae-9289-42cfad958bac.png)

## Description

- When this node is both a page and a parent node, a split line will be added between the collapse button and the link to distinguish the functional area.
- If there are no links to jump to, switch to expand when clicking on the text
