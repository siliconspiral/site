# Silicon Spiral Web Site

## Github Pages Setup

- Set up DNS Alias record for siliconspiral.com -> siliconspiral.github.io:
  - See https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site#configuring-an-apex-domain
- Set up DNS CNAME record for www.siliconspiral.com -> siliconspiral.github.io:
- Navigate to Settings > Pages:
  - Set build and deployment source = deploy from a branch, branch = main, folder = /docs.
  - Set custom domain as siliconspiral.com and perform DNS check.
  - Once TLS certificate has been created, check Enforce HTTPS.

Now the site should be available at https://siliconspiral.com and a redirect to this from https://www.siliconspiral.com.

## Hugo

The [Hugo](https://gohugo.io/) static site generator is used to create this web site. Please install the `hugo` binary for development. You will also need to install [Go](https://go.dev/) to treat the theme as a module (see below).

### Initial Setup

The following steps were followed to set this site up:

    $ hugo new site site
    $ cd ten-things-site

### Theme

The [Blowfish](https://blowfish.page/) theme is a git submodule in this site.

Myriad configuration options under the `config` directory are documented on the [Blowfish](https://blowfish.page/) site.

### Development Server

To start the development server:

    $ hugo server

The `/content/*.md` files can be edited and the server will auto refresh the page.

### Deployment

**It is important to build the site before pushing to github**

To build the site, run:

    $ hugo build
    $ git push origin main

This will place the static site into the `/docs` directory. A `git push` to github will the set off the automatic deployment.

Main web site

## Notes

Site is held in the docs directory and served locally with:

    $ hugo server

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
