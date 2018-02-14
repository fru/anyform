<div>
    <a href="https://github.com/fru/anyform">
        <img src="/packages/config/readme_resources/header.png" align="right" height="95px"/>
    </a>
    <a href="goto_demo_readme">
        <img src="/packages/config/readme_resources/demo2.gif" align="right" width="476px"/>
    </a>
</div>

# Usage

Install anyform and a [component set](https://www.google.com):

```bash
npm install -s anyform-react
npm install -s anyform-set-default
```

Embed the editor into your app:

```jsx
import Anyform from 'anyform-react';
import set from 'anyform-set-default';

// In the intended render method add:
<Anyform.Editor components={set} />
```

## Content

* [Common usage](#common-usage)
* [Installation](#installation)
    * [Node projects](#node-projects)
    * [Web projects](#web-projects)
* [Parameters](#parameters)
    * [Aliases](#aliases)
    * [Sequence](#sequence)