[![brimble NPM](https://img.shields.io/badge/npm-brimble-blue)](https://www.npmjs.com/package/@brimble/cli)


<a href="https://res.cloudinary.com/dgqfojhx4/image/upload/v1683036273/brimble-assets/paystack-logo_imtgax.png"><img src="https://res.cloudinary.com/dgqfojhx4/image/upload/v1683036273/brimble-assets/paystack-logo_imtgax.png" height="72" alt="Brimble" align="left" /></a>

# Brimble

<br>

[Brimble](https://www.brimble.io) is your go-to cloud platform for deploying front-end web applications.

Streamline your frontend deployment. Effortlessly package and deliver web code. Optimize loading times for seamless user experiences. Simplify your workflow with Brimble.

## Prerequisites

-   [Git](https://git-scm.com)

## Quick start


### Getting started

* Fork the repo [here](https://github.com/brimblehq/templates/fork) ✅
* Clone the repository ✅
* Make changes to templates.json ✅
* Create a branch with the name: <code>brimble/template-name</code> ✅
* Upload your banner image [here](https://forms.gle/FwUpnyjp46oiDT6w8) ✅
* Mark your repository as a template, on the settings page ✅
* Add brimble badge to readMe ✅
* Create a Pull Request ✅
* Wait for your template to go live 🚀


#### Example

```json
[
  {
    "githubUrl": "https://github.com/pipethedev/templates",
    "categories": [
      "e-commerce",
      "health-fitness"
    ],
    "deploymentUrl": "https://templates.brimble.app"
  }
]
```

<details><summary><b>Supported Categories</b></summary>

### Template Categories

- **Portfolio**: Templates for showcasing personal or professional portfolios, including artists, designers, photographers, and developers. <code>portfolio</code>

- **E-Commerce**: Templates tailored for online stores, enabling users to easily sell products and services. <code>e-commerce</code>

- **Blog**: Templates for bloggers to share articles, stories, and insights on various topics. <code>blog</code>

- **Corporate**: Professional templates suitable for corporate websites, highlighting company information, services, and contact details. <code>corporate</code>

- **Startup**: Templates aimed at startup companies, focusing on product features, team profiles, and value propositions. <code>startup</code>

- **Event**: Templates for promoting and managing events, conferences, workshops, and other gatherings. <code>event</code>

- **Restaurant**: Templates for restaurants and cafes, showcasing menus, location details, and reservation options. <code>restaurant</code>

- **Personal Blogging**: Templates tailored for personal bloggers to express thoughts, ideas, and experiences. <code>personal-blogging</code>

- **Nonprofit**: Templates for nonprofit organizations to raise awareness, share mission details, and collect donations. <code>nonprofit</code>

- **Education**: Templates for educational institutions, providing information about courses, faculty, and admissions. <code>education</code>

- **Travel**: Templates designed for travel agencies or travel bloggers to showcase destinations, itineraries, and travel tips. <code>travel</code>

- **Music/Band**: Templates for musicians and bands to showcase their music, tour dates, and merchandise. <code>music-band</code>

- **Health/Fitness**: Templates related to health and fitness, suitable for gyms, fitness coaches, and wellness blogs. <code>health-fitness</code>

- **Real Estate**: Templates for real estate agents or agencies to display property listings and contact information. <code>real-estate</code>

- **Technology**: Templates for tech-related companies or blogs, focusing on products, innovations, and industry insights. <code>technology</code>

- **Fashion**: Templates for fashion designers, brands, or boutiques to showcase clothing lines and accessories. <code>fashion</code>

- **Art/Creative**: Templates for artists and creatives to display their artwork, designs, and creative projects.<code>art-creative</code>

- **Freelancer/Consultant**: Templates for freelancers and consultants to present their services, expertise, and client testimonials. <code>freelancer-consultant</code>

- **Community/Forum**: Templates for creating online communities or discussion forums around specific topics. <code>forum</code>

- **News/Magazine**: Templates designed for news websites or online magazines, featuring articles, headlines, and multimedia content. <code>news/magazine</code>



</details>

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
      <td><code>categories</code></td>
      <td>Array</td>
      <td>Array of supported categories, for your template</td>
      <td>
        <code>[
      "e-commerce",
      "health-fitness"
    ]</code>
      </td>
    </tr>
    <tr>
      <td><code>deploymentUrl</code></td>
      <td>Array</td>
      <td>Deployment URL of your template on brimble</td>
      <td>
        <code>"https://templates.brimble.app"</code>
      </td>
    </tr>
  </tbody>
</table>

## Brimble Badge
The URL of the badge is the repository URL

<br/>
<a href="https://beta.brimble.io">
<img src="https://res.cloudinary.com/dgqfojhx4/image/upload/v1692011166/brimble-assets/badge_fuuq5i.png" alt="Brimble badge"/>
</a>

## Quick note

-   Providing an invalid json format would not get your pull request approved & merged.
-   Only provide supported categories as they are case-sensitive.
-   Deployment URL should only have the brimble.app subdomain.
-   Uploading a banner image is mandatory.
-   Absence of the brimble badge in your readMe file could prevent pull request approval
