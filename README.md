# Farm Website - Egg Sales & E-Commerce

Farm e-commerce platform for farm.markbarney.net featuring:
- Product browsing and shopping cart
- Stripe payment processing
- Google OAuth authentication
- Order management and tracking
- Email notifications

## Project Status

**Phase:** Design & Planning (Complete)  
**Implementation:** Ready for Development

See `IMPLEMENTATION_PLAN.md` for detailed setup and build instructions.

## Quick Links

- [Implementation Plan](./IMPLEMENTATION_PLAN.md)
- [Live Site](https://farm.markbarney.net)

## Architecture

- **Backend:** Node.js + Express + TypeScript
- **Frontend:** React + TypeScript + Vite
- **Database:** PostgreSQL with Drizzle ORM
- **Authentication:** Google OAuth via Passport.js
- **Payments:** Stripe API with webhook handling

## Getting Started

See `IMPLEMENTATION_PLAN.md` for complete setup instructions.

## Development

```bash
# Install dependencies
npm install

# Set up environment variables
cp .env.example .env

# Run development server
npm run dev

# Run tests
npm run test
```

## Deployment

Deploy to farm.markbarney.net via your preferred hosting platform (Railway, Vercel, etc.).

See deployment section in `IMPLEMENTATION_PLAN.md` for details.
