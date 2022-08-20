Practice project for the purpose of testing: AWS, Docker, Docker compose and Github actions
A staic website and database for testing purposes.

What it does: ( When the deploy action is manually run )

1. Connects to a EC2 instance via SSH ( connstring info in secrets )
2. Copies the static website and database config files from the repo to the server
3. Writes the neccesary env vars
4. Builds and runs docker compose for a nginx static website and a mongodb database ( Website link: boardgaming.store )

The template for the website is from: https://www.free-css.com/free-css-templates
