# Go URL Shortener

This is a simple URL shortening service implemented in Go. The service generates a short URL for a given original URL and redirects to the original URL when the short URL is accessed.

## Features

- Generate a shortened URL for any given original URL.
- Redirect to the original URL using the shortened URL.
- Simple in-memory storage for URL mappings.

## Installation

1. **Clone the Repository**

   ```sh
   git clone https://github.com/kundan766/Golang-URL-shorten-project.git
   cd Golang-URL-shorten-project


Project Structure
main.go: The main file containing the server implementation.
URL: Struct to store URL information.
generateShortenURL: Function to generate a short URL.
createURL: Function to create a URL entry.
getURL: Function to retrieve a URL entry.
handler: Basic handler for the root endpoint.
shortURLHandler: Handler to generate short URLs.
redirectURLHandler: Handler to redirect to the original URL.
