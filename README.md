# DoubleZero Documentation

This repository contains the official documentation for DoubleZero, a decentralized framework for creating and managing high-performance decentralized networks, optimized for distributed systems like blockchains.

## About DoubleZero

DoubleZero provides an integrated service for highly-optimized transmission and pre-processing for distributed systems data. Users of DoubleZero enjoy improved network performance through edge filtering and optimized routing compared to traditional internet connections.

## Documentation Structure

- **Getting Started**: Introduction and setup guides
- **Connection Modes**: IBRL and Multicast connection options
- **Network**: Contribution and architecture information
- **Support**: FAQs and important notices
- **API Reference**: Technical API documentation

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally. To install, use the following command:

```
npm i -g mint
```

Run the following command at the root of your documentation, where your `docs.json` is located:

```
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing changes

Install our GitHub app from your [dashboard](https://dashboard.mintlify.com/settings/organization/github-app) to propagate changes from your repo to your deployment. Changes are deployed to production automatically after pushing to the default branch.

## Need help?

### Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

### Resources
- [Mintlify documentation](https://mintlify.com/docs)
- [Mintlify community](https://mintlify.com/community)
- [DoubleZero Protocol](https://docs.malbeclabs.com/)
