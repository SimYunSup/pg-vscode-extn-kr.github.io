---
layout: default
title: Overview
nav_order: 1
description: ""
permalink: /
---


# Extension API

Visual Studio Code is built with extensibility in mind. From the UI to the editing experience, almost every part of VS Code can be customized and enhanced through the Extension API. In fact, many core features of VS Code are built as [extensions](https://github.com/Microsoft/vscode/tree/master/extensions) and use the same Extension API.

This documentation describes:

- How to build, run, debug, test and publish an extension
- How to take advantage of VS Code's rich Extension API
- Where to find guides and code samples to help get you started

If you are looking for published extensions, head to the [VS Code Extension Marketplace](https://marketplace.visualstudio.com/vscode).

## What's new?

VS Code updates on a monthly cadence, and that applies to the Extension API as well. New features and APIs become available every month to increase the power and scope of VS Code extensions.

To stay current with the Extension API, you can review the monthly release notes, which have dedicated sections covering:

* [Extension authoring](https://code.visualstudio.com/updates#_extension-authoring) - Learn what new extension APIs are available in the latest release.
* [Proposed extension APIs](https://code.visualstudio.com/updates#_proposed-extension-apis) - Review and give feedback on upcoming proposed APIs.

## What can extensions do?

Here are some examples of what you can achieve with the Extension API:

- Change the look of VS Code with a color or icon theme - [Theming](/api/extension-capabilities/theming)
- Add custom components & views in the UI - [Extending the Workbench](/api/extension-capabilities/extending-workbench)
- Create a Webview to display a custom webpage built with HTML/CSS/JS - [Webview Guide](/api/extension-guides/webview)
- Support a new programming language - [Language Extensions Overview](/api/language-extensions/overview)
- Support debugging a specific runtime - [Debugger Extension Guide](/api/extension-guides/debugger-extension)

If you'd like to have a more comprehensive overview of the Extension API, refer to the [Extension Capabilities Overview](/api/extension-capabilities/overview) page. [Extension Guides Overview](/api/extension-guides/overview) also includes a list of code samples and guides that illustrate various Extension API usage.

## How to build extensions?

Building a good extension can take a lot of effort. Here is what each section of the API doc can help you with:

- **Get Started** teaches fundamental concepts for building extensions with the [Hello World](https://github.com/Microsoft/vscode-extension-samples/tree/master/helloworld-sample) sample.
- **Working with Extensions** includes in-depth guides on various extension development topics, such as [publishing](/api/working-with-extensions/publishing-extension) and [testing](/api/working-with-extensions/testing-extension) extensions.
- **Extension Capabilities** dissects VS Code's vast API into smaller categories and points you to more detailed topics.
- **Extension Guides** includes guides and code samples that explain specific usages of VS Code Extension API.
- **Language Extensions** illustrates how to add support for a programming language with guides and code samples.
- **Advanced Topics** explains advanced concepts such as [Extension Host](/api/advanced-topics/extension-host), [Supporting Remote Development and VS Online](/api/advanced-topics/remote-extensions), and [Proposed API](/api/advanced-topics/using-proposed-api).
- **References** contains exhaustive references for the [VS Code API](/api/references/vscode-api), [Contribution Points](/api/references/contribution-points), and many other topics.

## Looking for help

If you have questions for extension development, try asking on:

- [Stack Overflow](https://stackoverflow.com/questions/tagged/visual-studio-code): There are [thousands of questions](https://stackoverflow.com/questions/tagged/visual-studio-code) tagged `visual-studio-code`, and over half of them already have answers. Search for your issue, ask questions, or help your fellow developers by answering VS Code extension development questions!
- [Gitter Channel](https://gitter.im/Microsoft/vscode) and [VS Code Dev Slack](https://aka.ms/vscode-dev-community): Public chatroom for extension developers. Some VS Code team members chime in conversations.

To provide feedback on the documentation, create new issues at [Microsoft/vscode-docs](https://github.com/Microsoft/vscode-docs/issues).
If you have extension questions that you cannot find an answer for, or issues with the VS Code Extension API, please open new issues at [Microsoft/vscode](https://github.com/Microsoft/vscode/issues).

