# create-miden

A CLI tool to quickly spin up Miden projects with Next.js, Miden WebClient and Miden Wallet Adapter

## Highlight

- No need for manual setup from scratch
- Prepared with common functionalities

## Prerequisites

Before using `create-miden`, make sure you have the following installed:

- Node.js ≥ 16.0.0
- pnpm (recommended package manager)

Install pnpm globally if you don’t have it:

```bash
npm install -g pnpm
```

Verify your setup:

```bash
node --version   # should be 16.x or newer
pnpm --version
```

## 🚀 Quick Start

```bash
npx create-miden
```

You’ll be prompted to:

- Enter a project name
- Choose template version (Stable by default)

## Next Steps

After the project is created:

```bash
cd <your-project-name>

# install deps (recommended)
pnpm install

# start dev server
pnpm run dev
```

## Project Structure

After creating a project, you'll get:

```
my-app/
├── src/
│   ├── app/                 # Next.js app directory
│   ├── components/          # React components
│   └── ...
├── public/                  # Static assets
├── package.json             # Dependencies and scripts
├── tailwind.config.js       # Tailwind configuration
├── tsconfig.json            # TypeScript configuration
└── README.md                # Project documentation
```

## Publishing

```bash
pnpm run build

pnpm publish
```

## License

MIT License - see [LICENSE](LICENSE) for details.
