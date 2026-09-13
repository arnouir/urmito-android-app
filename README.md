# URMITO Seller App — Portfolio Showcase

URMITO Seller App is an Android marketplace project started in **2024** and currently under active development. It is designed for sellers who list clothing and related fashion accessories through the URMITO marketplace.

This repository is a **portfolio showcase**. It presents selected seller-side interfaces and workflows; the application source code is private and is not included here.

## Overview

The screenshots currently focus on part of the seller experience, including product management and the multi-step product listing flow. Some platform-specific features are still under development and are intentionally not presented yet.

The screenshots in this repository **do not represent every screen, feature, or module in the application**.

## Main Features Shown

- Seller product dashboard
- Multi-step product listing workflow
- Product name, brand, gender, category, and subcategory selection
- Product image and media submission
- Main image and zoomed-image fields
- Product size-chart submission
- Optional product video submission
- Light and dark interface themes
- Offline/local data storage with SQLite
- PHP backend with MySQL persistence

## Tech Stack

| Layer | Technology |
| --- | --- |
| Android application | Kotlin |
| Offline/local storage | SQLite |
| Backend | PHP |
| Server database | MySQL |

## Screenshots

### Dark Theme

<p align="center">
  <a href="screenshots/01-products-dashboard-dark.png">
    <img src="screenshots/01-products-dashboard-dark.png" width="300" alt="URMITO seller products dashboard in dark theme" />
  </a>
  <a href="screenshots/02-product-details-dark.png">
    <img src="screenshots/02-product-details-dark.png" width="300" alt="URMITO product details form in dark theme" />
  </a>
  <a href="screenshots/03-product-media-dark.png">
    <img src="screenshots/03-product-media-dark.png" width="300" alt="URMITO product media upload screen in dark theme" />
  </a>
</p>

### Light Theme

<p align="center">
  <a href="screenshots/04-products-dashboard-light.png">
    <img src="screenshots/04-products-dashboard-light.png" width="300" alt="URMITO seller products dashboard in light theme" />
  </a>
  <a href="screenshots/05-product-details-light.png">
    <img src="screenshots/05-product-details-light.png" width="300" alt="URMITO product details form in light theme" />
  </a>
  <a href="screenshots/06-product-media-light.png">
    <img src="screenshots/06-product-media-light.png" width="300" alt="URMITO product media upload screen in light theme" />
  </a>
</p>

> The screenshots above are selected portfolio views only and do not cover the full application.

## Portfolio Overview

<p align="center">
  <a href="portfolio-overview.png">
    <img src="portfolio-overview.png" width="900" alt="URMITO Seller App portfolio overview" />
  </a>
</p>

## Architecture

```mermaid
flowchart LR
    A[Android Seller App<br/>Kotlin] --> B[SQLite<br/>Offline / Local Data]
    A --> C[PHP Backend]
    C --> D[MySQL Database]
```

The Android client uses **SQLite** for local/offline data handling and communicates with a **PHP backend**, with server-side data stored in **MySQL**.

## Project Status

**Active Development — started in 2024**

The project is still evolving. Additional marketplace capabilities and platform-specific features are under development and are not included in this public showcase.

## Repository Status

This repository is intended solely as a **portfolio presentation**. The production source code, backend implementation, business logic, and unreleased features remain private.
