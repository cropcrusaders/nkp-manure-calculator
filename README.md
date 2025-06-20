# NKP Manure Calculator

## Overview
The **NKP Manure Calculator** is a simple web-based tool for estimating the nutrient
content provided by different types of manure. It now includes options for selecting
your region, crop type and application method to deliver more realistic nutrient
estimates and recommendations. The tool helps farmers and gardeners determine how
much nitrogen (N), phosphorus (P₂O₅), potassium (K₂O) and other essential elements
are contributed by a given quantity of manure.
The calculator is implemented with HTML, CSS and JavaScript and can be run as a
static site or served through Jekyll for GitHub Pages.

## Basic Usage
1. Open `index.html` directly in your browser, or serve the site locally with
   Jekyll:
   ```bash
   bundle install
   bundle exec jekyll serve
   ```
2. Choose the manure type and your region.
3. Select the crop you are fertilizing and how the manure will be applied.
4. Enter the manure quantity and unit (kilograms or pounds).
5. Click **Calculate** to see both the nutrient contribution and a recommended rate to meet your crop's nitrogen needs.

## Deployment
This repository includes a GitHub Actions workflow that automatically builds and
deploys the site to GitHub Pages whenever changes are pushed to `main`.
Simply commit your updates and push them to the repository; the workflow will
handle the deployment.

## Contributing
Contributions are welcome! To propose a change:
1. Fork this repository.
2. Create a feature branch and make your changes.
3. Open a pull request describing your updates.

