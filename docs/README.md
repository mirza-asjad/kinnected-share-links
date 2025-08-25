# Kinnected Family Invitation System

This directory contains the GitHub Pages setup for handling family invitation links.

## Structure

- `index.html` - Main landing page for invitation links
- `invite/index.html` - Direct invitation handler that attempts app deep linking

## Setup Instructions

1. Enable GitHub Pages for this repository
2. Set the source to `/docs` folder 
3. Update the SQL function `create_family_invitation` to use your GitHub Pages URL
4. Update the download links in `index.html` to point to your actual app stores

## URL Structure

- Main invitation page: `https://duseca.github.io/Kinnected_Mobile_Nish/index.html?token=ABC12345`
- Direct invitation: `https://duseca.github.io/Kinnected_Mobile_Nish/invite/ABC12345`

## Deep Link Handling

The pages automatically attempt to open the app using the custom scheme:
`kinnected://invite/ABC12345`

If the app is not installed, users are shown download options.
