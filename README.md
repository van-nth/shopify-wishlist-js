<div id="top"></div>
<div align="center">
<h3 align="center">Shopify Wishlist</h3>
  <p align="center">
    Create a simple Shopify Wishlist by Javascript
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

- Only need Javascript and a bit CSS code to implement the ADD-TO-WISHLIST function to your Shopify Store

- Compatible with all Shopify Themes

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

- Javascript
- CSS

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

### Installation

1. Copy and paste 2 files `wishlist.js` and `wishlist.css` in this repo to `assets` folder in your Theme

2. Place these script in `theme.liquid` before the closing `</head>` tag

```sh
<script id="Wishlist" data-handle={{ product.handle }} src="{{ 'Wishlist.js' | asset_url }}" defer="defer"></script>
```

```sh
{{ 'wishlist.css' | asset_url | stylesheet_tag }}
```

<p align="right">(<a href="#top">back to top</a>)</p>

## Usage

1. Click on the add-to-wishlist icon in a product, the product will be added to the Wishlist toggle Dialog
2. To view the Wishlist Dialog

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Email: kat@alphaxp.com

Project Link: [https://github.com/van-nth/shopify-wishlist-js]

<p align="right">(<a href="#top">back to top</a>)</p>
