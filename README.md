# Next.js router.push() Not Working After Initial Build

This repository demonstrates a common issue with Next.js where `router.push()` doesn't work as expected after the initial page load.  The problem occurs when navigating from the 'About' page to the 'Contact' page.

## Problem

The navigation to the contact page from the about page does not work after the initial build.  The page does not reroute.

## Solution

The problem is due to missing or incorrect file paths and routes.  Ensure the file paths are correctly mapped within the `pages` directory and that routes match page file names.

## Setup

1. Clone this repository.
2. Run `npm install` to install the dependencies.
3. Run `npm run dev` to start the development server.

Navigate to the '/about' page and click on the button to go to the '/contact' page. You should see this error.
