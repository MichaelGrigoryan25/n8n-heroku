# n8n.io Heroku Docker Container Instance

This repository is ready to go for deployment of n8n.io on Heroku Cloud.

# Steps to reproduce

- Install Heroku CLI -> `npm i -g heroku`
- Login to Heroku -> `heroku login` and after `heroku container:login`
- Create a new app -> `heroku create`
- Push the container to Heroku Registry -> `heroku container:push web`
- Release the container to Heroku -> `heroku container:release web`
- Done!

Now check out the website ( typically SOME-SILLY-NAME.herokuapp.com ) that the CLI has returned and your n8n instance should be good to go!