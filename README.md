# issues-scrumboard

Display issues from a private GitHub repo in a custom way.

## Requirements

- A web server
- PHP>=5

## Setup

- Expose the `public` folder with the web server
- Run the PHP script every X minutes `php issues.php OUTPUT_PATH GITHUB_TOKEN` (example: `php issues.php ./public s3cr3t`)
- Pull the repo everyday to get access to new features

## Security

You might want to setup a .htaccess to prevent the entire world from accessing your issues
