[![Validate](https://github.com/wappalyzer/wappalyzer/actions/workflows/validate.yml/badge.svg)](https://github.com/wappalyzer/wappalyzer/actions/workflows/validate.yml)
[![wappalyzer NPM](https://img.shields.io/badge/npm-wappalyzer-blue)](https://www.npmjs.com/package/wappalyzer)
[![wappalyzer-core NPM](https://img.shields.io/badge/npm-wappalyzer--core-blue)](https://www.npmjs.com/package/wappalyzer-core)
[![Github Sponsor](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&link=https://github.com/sponsors/AliasIO)](https://github.com/sponsors/AliasIO)

<a href="https://www.wappalyzer.com/?utm_source=readme&utm_medium=github&utm_campaign=wappalyzer"><img src="https://www.wappalyzer.com/images/logo/icon_192.png" height="72" alt="Wappalyzer" align="left" /></a>

# Brimble

<br>

[Brimble](https://www.brimble.io) is your go to cloud platform for deploying your frontend web applications.

Streamline your frontend deployment. Effortlessly package and deliver web code. Optimize loading times for seamless user experiences. Simplify your workflow with Brimble.

## Prerequisites

-   [Git](https://git-scm.com)

## Quick start


### Getting started

* Fork the repo [here](https://github.com/brimblehq/templates/fork) ✅
* Clone the repository ✅
* Make changes to templates.json ✅
* Branch name of <code>brimble/template-name</code> ✅
* Upload your banner image [here](https://forms.gle/FwUpnyjp46oiDT6w8) ✅
* Mark your repository as template, in the settings page ✅
* Create a Pull Request ✅
* Wait for your template to go live 🚀


#### Example

```json
[
  {
    "githubUrl": "https://github.com/pipethedev/templates",
    "imageUrl": "https://image.com",
    "categories": [
      "Ecommerce",
      "Health"
    ],
    "deploymentUrl": "https://templates.brimble.app"
  }
]
```

## JSON fields

This is the JSON schema for templates.json.

### Required properties

<table>

  <tbody>
    <tr>
      <td><code>githubUrl</code></td>
      <td>String</td>
      <td>
        Your template url, you want live on brimble
      </td>
      <td><code>https://github.com/pipethedev/templates</code></td>
    </tr>
    <tr>
      <td><code>imageUrl</code></td>
      <td>String</td>
      <td>Banner image or screenshot image url of your template</td>
      <td>
        <code>https://image.com</code>
      </td>
    </tr>
    <tr>
      <td><code>categories</code></td>
      <td>Array</td>
      <td>Array of supported categories, for your template</td>
      <td>
        <code>[
      "Ecommerce",
      "Health"
    ]</code>
      </td>
    </tr>
    <tr>
      <td><code>deploymentUrl</code></td>
      <td>Array</td>
      <td>Deployment url of your template on brimble</td>
      <td>
        <code>"https://templates.brimble.app"</code>
      </td>
    </tr>
  </tbody>
</table>


## Quick note

-   Providing an invalid json format would not get your pull request approved & merged.
-   Only provide supported categories as they are case sensitive.
-   Deployment url should only have the brimble.app subdomain.
-   Uploading a banner image is mandatory.
