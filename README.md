[![wappalyzer NPM](https://img.shields.io/badge/npm-brimble-blue)](https://www.npmjs.com/package/@brimble/cli)


<a href="https://res.cloudinary.com/dgqfojhx4/image/upload/v1683036273/brimble-assets/paystack-logo_imtgax.png"><img src="https://res.cloudinary.com/dgqfojhx4/image/upload/v1683036273/brimble-assets/paystack-logo_imtgax.png" height="72" alt="Brimble" align="left" /></a>

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
