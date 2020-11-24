# Gatsby Chakra UI Recipe

[Chakra UI](https://chakra-ui.com/) provides a set of accessible, reusable, and composable React components that make it super easy to create websites and apps.

This recipes sets up and configures [@chakra-ui/gatsby-plugin](https://www.gatsbyjs.com/plugins/@chakra-ui/gatsby-plugin/) by installing it's dependencies and shadowing `theme.js` file to create a custom theme.

### Env dependencies

- node
- npm
- gatsby
- gatsby-cli

### Usage

`gatsby recipes https://raw.githubusercontent.com/shoxton/gatsby-recipe-chakra-ui/master/chakra-ui.mdx`

---

# This recipe:

## Installs necessary NPM packages


- @emotion/react
- @emotion/styled
- framer-motion
- @chakra-ui/react
- @chakra-ui/gatsby-plugin

This step implements the [`<NPMPackage>`](https://github.com/gatsbyjs/gatsby/blob/master/packages/gatsby-recipes/README.md#npmpackage) API.

---

## Installs @chakra-ui/gatsby-plugin plugin

This step is responsable for installing [`@chakra-ui/gatsby-plugin`](https://www.gatsbyjs.com/plugins/@chakra-ui/gatsby-plugin/) in the `gatsby-config.js` file.

This step implements the [`<GatsbyPlugin>`](https://github.com/gatsbyjs/gatsby/blob/master/packages/gatsby-recipes/README.md#gatsbyplugin) API.

---

## Shadows @chakra-ui/gatsby-plugin `theme.js`

By shadowing the `theme.js` file, you can create a custom theme.

This step implements the [`<GatsbyShadowFile>`](https://github.com/gatsbyjs/gatsby/blob/master/packages/gatsby-recipes/README.md#gatsbyshadowfile)

---

## Once you've installed this recipe, you're ready to get started!

- Learn more about [@chakra-ui/gatsby-plugin options](https://chakra-ui.com/guides/integrations/with-gatsby)
- Read more about Chakra UI on the official [Chakra docs site](https://chakra-ui.com/getting-started)
- Check the [Gatsby recipes docs](https://github.com/gatsbyjs/gatsby/blob/master/packages/gatsby-recipes/README.md) and learn how to create your own

---

`Implemented with 💖 by` [`shoxton`](https://github.com/shoxton)
