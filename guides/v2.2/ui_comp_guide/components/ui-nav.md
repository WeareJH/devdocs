---
layout: default
group: UI_Components_guide
subgroup: components
title: Nav component
menu_title: Nav component
version: 2.2
github_link: ui_comp_guide/components/ui-nav.md
---

## Overview

The Nav component implements tabs navigation.

See the [Admin Design Pattern Library (Tabs)]({{page.baseurl}}/pattern-library/containers/tabs/tabs.html) topic for information about the UI design patterns that can be implemented using the Nav component.

## Configuration options

Extends all `uiComponent` and `collapsible` configuration.

Nav-specific options:

<table>
  <tr>
    <th>Option </th>
    <th>Description</th>
    <th>Type</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><code>collapsible</code></td>
    <td>Enables/disables the collapsible functionality.</td>
    <td>Boolean</td>
    <td><code>false</code></td>
  </tr>
  <tr>
    <td><code>component</code></td>
    <td>The path to the component’s JS constructor, in terms of RequireJS.</td>
    <td>String</td>
    <td><code>Magento_Ui/js/form/components/tab_group</code></td>
  </tr>
  <tr>
    <td><code>opened</code></td>
    <td>Initial collapsible state, if the collapsible functionality is enabled.</td>
    <td>Boolean</td>
    <td><code>true</code></td>
  </tr>
  <tr>
    <td><code>template</code></td>
    <td>The path to the component’s <code>.html</code> template.</td>
    <td>String</td>
    <td><code>ui/tab</code></td>
  </tr>
</table>
