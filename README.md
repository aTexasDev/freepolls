# Free Polls

Create free polls instantly with no signup required. The fastest free poll maker online - type your question and share in under 10 seconds. Anonymous voting with real-time results.

**Live:** [freepolls.app](https://freepolls.app)

## Tech Stack

- Vanilla JavaScript
- HTML5 / CSS3
- i18n internationalization support
- AWS Lambda + API Gateway backend

## Features

- Instant poll creation (under 10 seconds)
- No signup required
- Anonymous voting
- Real-time results
- Shareable poll links
- Multi-language support

## Getting Started

1. Clone the repository
```bash
git clone https://github.com/aTexasDev/freepolls-app.git
cd freepolls-app
```

2. Open `index.html` in your browser, or serve with any static file server:
```bash
npx serve .
```

## Architecture

This is the frontend application. It communicates with a serverless backend (AWS Lambda + API Gateway) for authenticated operations and data persistence.

- **Authentication:** Google OAuth 2.0
- **Payments:** Stripe Checkout
- **Hosting:** AWS S3 + CloudFront CDN
- **Backend:** AWS Lambda (not included in this repo)

## License

MIT License - see [LICENSE](LICENSE) for details.

---

Built by [T.K. Flautt](https://snapitsoftware.com) | [SnapIT Software](https://snapitsoftware.com)
