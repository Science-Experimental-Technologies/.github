# Publish the SCIX site on Cloudflare Pages

The static site is in `site/`. It uses plain HTML and CSS, needs no package install, and has no build step.

## Connect the repository

1. In Cloudflare, open **Workers & Pages** and choose **Create application → Pages → Connect to Git**.
2. Authorize Cloudflare Pages to access the GitHub organization, then select `Science-Experimental-Technologies/.github`.
3. Configure the deployment:

   | Setting | Value |
   | --- | --- |
   | Production branch | `main` |
   | Framework preset | `None` |
| Root directory | Leave blank (repository root) |
   | Build command | Leave blank |
   | Build output directory | `site` |

4. Choose an available Pages project name, then save and deploy. Cloudflare assigns the deployed project a `*.pages.dev` hostname.

After the first deployment, commits to `main` will update the live site automatically. Preview deployments are available for other branches and pull requests.

Cloudflare requires the repository to be authorized in the account that owns the Pages project. This repository does not contain account credentials or deployment tokens.
