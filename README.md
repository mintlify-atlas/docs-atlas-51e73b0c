# nodriver Documentation

This is the official documentation for [nodriver](https://github.com/ultrafunkamsterdam/nodriver), the next-generation async web scraping and browser automation library for Python.

## About nodriver

nodriver is the official successor of Undetected-Chromedriver, providing a fully asynchronous Python library for browser automation and web scraping. It communicates directly with browsers using the Chrome DevTools Protocol (CDP), eliminating the need for Selenium or ChromeDriver binaries.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview documentation changes locally:

```bash
npm i -g mint
```

Run the following command at the root of your documentation:

```bash
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing changes

Changes are deployed to production automatically after pushing to the main branch.

## Resources

- [nodriver GitHub](https://github.com/ultrafunkamsterdam/nodriver)
- [Mintlify documentation](https://mintlify.com/docs)
