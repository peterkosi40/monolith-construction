# Deployment checklist

1. Create a new public GitHub repository, for example `monolith-construction-demo`.
2. Upload every file in this folder directly to the repository root (do not upload this folder as a nested directory).
3. In Cloudflare Pages, create a project and connect the repository.
4. Choose framework preset `None`.
5. Set build command to `exit 0` and build output directory to `.`.
6. Select the branch that exists in GitHub (typically `main`) and deploy.
7. Test on a phone and desktop: navigation, project filters, project detail overlays, images, contact email link, and horizontal overflow.
