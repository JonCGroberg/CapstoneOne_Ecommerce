<a name="capstone-1-ecommerce"></a>

# Capstone 1: Ecommerce

A modern and responsive ecommerce frontend built purely with HTML, CSS and Bootstrap.

## Live Site

https://joncgroberg.github.io/EcommerceCapstone/

<a name="table-of-contents"></a>

# Table of contents

- [Capstone 1: Ecommerce](#capstone-1-ecommerce)
- [Table of contents](#table-of-contents)
- [Development Process](#development-process)
- [Key Features](#key-features)
  - [Image Grid](#image-grid)
  - [Hero Image \& Navbar](#hero-image--navbar)
    - [Before](#wide-device)
    - [After](#mobile)
  - [Validation](#validation)
- [Pages](#pages)
  - [Landing](#landing)
  - [Store](#store)
  - [Login](#login)
  - [Register](#register)
  - [Checkout](#checkout)
- [About the project](#about-the-project)
    - [Technologies Used](#technologies-used)
    - [Credits \& Inspiration](#inspiration)

<a name="requirments-planning"></a>

# Development Process

 Diagram designed in [Figma]("https://www.figma.com/file/S2n1eDcWJ2ht2EFfM9nrPH/Ecommerce-Board?type=whiteboard&node-id=0%3A1&t=JVaHlDMqPAjOVueR-1")


![Ecommerce Board](./images/ecommerceBoard.png)

# Key Features

## Image Grid

- Images turn into a **masonry** grid at small sizes
  - Add to cart and bookmark icons on small cards **change** size
- Images **scale** to fit display size
  <p align="center">
  <img src= "images/feature1.gif" width=500>
  </p>
## Hero Image & Navbar

- Add to cart text **shortens** to "Add" on wide screens
- Button text **shortens** in larger views
- Navbar **collapses** and search bar **moves** to the top
- Hero Image **expands** to fill mobile screen


<a name="wide-device"></a>

### Wide Device

- Smaller card and portion of add to cart texts **hides**
- In row 

  <p align="center">
  <img src= "images/feature2Part1.png" width = 600>
  </p>

<a name="mobile"></a>

### Mobile

- Images scale to become larger forcing them to **wrap** 
- **Collapsed** navbar
  - Search bar **moves** to the top only when collapsed

  <p align="center">
  <img src= "images/feature2Part2.png" width=350>
  </p>

## Validation

  <p align="center">
  <img src= "images/validation.png" height = 200>
  </p>

<a name="pages"></a>

# Pages

<a name="landing"></a>

## Landing

Welcomes users with hero image and overview of the watch process
![Large](./images/mainLG.png)

- Stages using **Bootstrap cards**
- **Dynamic** and collapsing navbar

<a name="store"></a>

## Store

Displays products in responsive image grid. Bookmark, add to cart by clicking.

![Large](./images/storeLG.png)

- **Responsive** hero image using **columns** and Bootstrap cards
- Responsive product list using Bootstrap cards
  - **Responsive** buttons using Bootstrap **columns**

<a name="login"></a>

## Login

![Large](./images/loginLG.png)


- **Form** to capture basic user details
- **Validation** of required fields
- Remember me **checkbox**
- **Link** to register page

<a name="register"></a>

## Register


![Large](./images/registerLG.png)

- **Form** to capture basic user details
- **Validation** of required fields
- Remember me **checkbox**
- **Radio** buttons 
- **Link** to login page

<a name="checkout"></a>

## Checkout

![Large](./images/checkoutLG.png)
- **Shows** selected products, totals
- Enter to checkout: Address, payment, confirmation.
- **Validation** before proceeding.
- Cart built with **HTML table**

<a name="about-the-project"></a>

# About the project

<a name="tech"></a>

### Technologies Used

- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [HTML](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)
- [Bootstrap](https://getbootstrap.com/)
- [Figma](https://www.figma.com/) (wireframing and planning)
- [Stable Diffusion](https://stablediffusionweb.com/) (used in image generation)
- [Claude-instant-100k](https://www.anthropic.com/) (used in paragraph generation)

<a name="inspiration"></a>

### Credits & Design Inspiration

- [Amazon](https://www.amazon.com/)
- [Target](https://www.target.com/)
- [Apple Store](https://www.apple.com/store?afid=p238%7CsHI7bHWVr-dc_mtid_1870765e38482_pcrid_675348649381_pgrid_13945964767_pntwk_g_pchan__pexid__&cid=aos-us-kwgo-brand-apple-store--slid---product-)
