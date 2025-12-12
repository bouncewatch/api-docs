# BounceWatch API Documentation

Access company data instantly with BounceWatch API - a comprehensive intelligence platform for startup and company data.

<p align="center">
  <a href="https://bouncewatch.com">Website</a> •
  <a href="https://docs.bouncewatch.com">Documentation</a> •
  <a href="https://bouncewatch.com/api-panel/api-keys">Get API Key</a>
</p>

## What is BounceWatch API?

BounceWatch API provides detailed information about companies with a single API call. Get access to:

- **Base Data** - Company identity, contact info, location, employee count, founding date, social media links
- **Business Intelligence** - Industry, business model, target market, services offered, market positioning
- **Technology Stack** - Tools, frameworks, and infrastructure across 100+ technology categories
- **Funding & Investment** - Funding rounds, investors, valuation, total funding
- **Team & Hiring** - Team members, leadership, hiring status, open positions
- **Signals/Highlights** - 40 signal types including partnerships, product launches, funding, team changes, rumors, and metric-based highlights
- **Competitors** - Similar companies, competitor analysis, market positioning

## Key Features

- **Modular Architecture** - Only fetch the data you need with 7 different enrichment modules
- **Two Modes** - Instant response with Cached mode, fresh data with Realtime mode
- **Credit-Based** - Pay for what you use with a transparent credit system
- **Webhook Support** - Get notified instantly when realtime enrichment completes

## Quick Start

```bash
curl -X GET "https://api.bouncewatch.com/api/v1/company/stripe.com" \
  -H "X-API-Key: YOUR_API_KEY"
```

Add enrichment modules based on your needs:

```bash
curl -X GET "https://api.bouncewatch.com/api/v1/company/stripe.com?enrich=funding,team" \
  -H "X-API-Key: YOUR_API_KEY"
```

## Documentation

Visit our full documentation at [docs.bouncewatch.com](https://docs.bouncewatch.com) for:

- [Introduction](https://docs.bouncewatch.com/introduction) - Overview of BounceWatch API
- [Quickstart Guide](https://docs.bouncewatch.com/quickstart) - Get started in 2 minutes
- [Authentication](https://docs.bouncewatch.com/authentication) - API key management
- [API Reference](https://docs.bouncewatch.com/api-reference/overview) - Complete endpoint documentation
- [Credits & Modules](https://docs.bouncewatch.com/credits-and-modules) - Pricing and module details

## Use Cases

- **Investors** - Due diligence, deal flow analysis, funding history
- **Sales Teams** - Lead qualification, prospecting, tech stack discovery
- **Recruitment** - Talent intelligence, hiring status tracking
- **Market Research** - Competitive intelligence, industry trends

## Getting Your API Key

Create your API key from the [BounceWatch Dashboard](https://bouncewatch.com/api-panel/api-keys).

## Development (Documentation Site)

To run the documentation site locally:

```bash
npm i -g mintlify
mintlify dev
```

## License

See [LICENSE](LICENSE) for details.
