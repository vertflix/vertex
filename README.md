# Vertex

> RIP P-Stream

## Quick Deploy

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fvertflix%2Fvertex)

[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/vertflix/vertex)

## Running Locally

Type the following commands into your terminal / command line to run Vertex locally

```bash
git clone https://github.com/vertflix/vertex.git
cd vertex
git pull
pnpm install
pnpm run dev
```

Then you can visit the local instance [here](http://localhost:5173) or, at local host on port 5173.

## Updating a Vertex Instance

To update a Vertex instance you can type the below commands into a terminal at the root of your project.

```bash
git remote add upstream https://github.com/vertflix/vertex.git
git fetch upstream # Grab the contents of the new remote source
git checkout <YOUR_MAIN_BRANCH>  # Most likely this would be `origin/main`
git merge upstream/main
# * Fix any conflicts present during merge *
git add .  # Add all changes made during merge and conflict fixing
git commit -m "Update vertex instance (merge upstream/main)"
git push  # Push to YOUR repository
```
