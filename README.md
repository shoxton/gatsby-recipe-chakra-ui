# Gatsby Chakra UI Recipe

[Chakra UI](https://chakra-ui.com/) provides a set of accessible, reusable, and composable React components that make it super easy to create websites and apps.

This recipes sets up and configures [gatsby-plugin-chakra-ui](https://www.gatsbyjs.com/plugins/gatsby-plugin-chakra-ui/) by installing it's dependencies and shadowing `theme.js` file to create a custom theme.

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

- @chakra-ui/core
- gatsby-plugin-chakra-ui

This step implements the [`<NPMPackage>`](https://github.com/gatsbyjs/gatsby/blob/master/packages/gatsby-recipes/README.md#npmpackage) API.

---

## Installs gatsby-plugin-chakra-ui plugin

This step is responsable for installing [`gatsby-plugin-chakra-ui`]((https://www.gatsbyjs.com/plugins/gatsby-plugin-chakra-ui/)) in the `gatsby-config.js` file.

This step implements the [`<GatsbyPlugin>`](https://github.com/gatsbyjs/gatsby/blob/master/packages/gatsby-recipes/README.md#gatsbyplugin) API.

---

## Creates gatsby-plugin-chakra-ui `theme.js`

By creating the `theme.js` file, you can create your own global styles.

This step implements the [`<GatsbyShadowFile>`](https://github.com/gatsbyjs/gatsby/blob/master/packages/gatsby-recipes/README.md#gatsbyshadowfile)

---

## Once you've installed this recipe, you're ready to get started!

- Learn more about [gatsby-plugin-chakra-ui options](https://github.com/chakra-ui/chakra-ui/tree/develop/tooling/gatsby-plugin-chakra-ui#plugin-options)
- Read more about Chakra UI on the official [Chakra docs site](https://chakra-ui.com/getting-started)
- Check the [Gatsby recipes docs](https://github.com/gatsbyjs/gatsby/blob/master/packages/gatsby-recipes/README.md) and learn how to create your own

---

`Implemented with 💖 by` [`shoxton`](https://github.com/shoxton)
