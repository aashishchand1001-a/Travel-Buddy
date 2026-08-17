# Travel-Buddy

Netlify deployment

This project is configured to deploy on Netlify.

- Build command: npm run build
- Publish directory: build

Recommended: connect the GitHub repository https://github.com/aashishchand1001-a/Travel-Buddy to Netlify (Netlify -> New site -> Import from Git) and use the settings above. Netlify will automatically build and publish the site on every push to the selected branch.

If you prefer manual deploys, install the Netlify CLI and run:

  npm install -g netlify-cli
  netlify deploy --prod --dir=build

If the project requires a different build command or publish directory, update netlify.toml accordingly or tell me what to set.
