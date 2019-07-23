# WordPress & Rails

Before I learned Rails, I used to work with WordPress to build sites for clients. I started a blog so I'm using the framework again but Php is pretty bad, so I'm sticking with Rails.

## My plan

The idea is to use WordPress as a cms & use Rails to display posts in different parts of the app.

1. User connects their WordPress account using oAuth
1. User selects which sites to sync
1. System fetches data from api and saves locally
1. Any actions on the site are sent back upstream to appear on their site
   1. Comments
   1. Likes
   
## Plugins

- `invisible-toolkit` contains code to work with services and tools provided by Invisible Hat Ventures
