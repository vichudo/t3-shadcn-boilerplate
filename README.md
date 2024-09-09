# T3 Stack Boilerplate with shadcn UI

![GitHub license](https://img.shields.io/github/license/vichudo/t3-shadcn-boilerplate)
![GitHub stars](https://img.shields.io/github/stars/vichudo/t3-shadcn-boilerplate)
![GitHub forks](https://img.shields.io/github/forks/vichudo/t3-shadcn-boilerplate)
![GitHub issues](https://img.shields.io/github/issues/vichudo/t3-shadcn-boilerplate)
![GitHub last commit](https://img.shields.io/github/last-commit/vichudo/t3-shadcn-boilerplate)

A modern, fully-featured boilerplate built with the T3 Stack and enhanced with shadcn UI components. Perfect for kickstarting your next web application with a powerful, type-safe foundation.

## 🚀 Features

- [Next.js](https://nextjs.org) for server-side rendering and routing
- [TypeScript](https://www.typescriptlang.org/) for type safety
- [tRPC](https://trpc.io) for end-to-end type-safe APIs
- [Prisma](https://www.prisma.io/) for database ORM
- [NextAuth.js](https://next-auth.js.org) for authentication
- [Tailwind CSS](https://tailwindcss.com) for styling
- [shadcn UI](https://ui.shadcn.com/) for beautiful, accessible UI components
- [ESLint](https://eslint.org) and [Prettier](https://prettier.io) for code linting and formatting
- [GitHub Actions](https://github.com/features/actions) for CI/CD
- [Dependabot](https://github.com/dependabot) for automated dependency updates

## 📚 Table of Contents

- [Quick Start](#-quick-start)
- [Project Structure](#-project-structure)
- [Scripts](#-scripts)
- [Environment Variables](#-environment-variables)
- [Database](#-database)
- [Authentication](#-authentication)
- [Styling](#-styling)
- [Adding shadcn UI Components](#-adding-shadcn-ui-components)
- [Deployment](#-deployment)
- [Contributing](#-contributing)
- [License](#-license)

## 🚀 Quick Start

Get up and running with these simple steps:

```bash
# Clone the repository
git clone https://github.com/vichudo/t3-shadcn-boilerplate.git
cd t3-shadcn-boilerplate

# Install dependencies
yarn install

# Set up your environment variables
cp .env.example .env
# Edit .env with your database credentials and other configuration

# Push the Prisma schema to your database
yarn db:push

# Start the development server
yarn dev
```

After running these commands, open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### 📝 Notes:

- Make sure you have Node.js (version 18.x or later) and Yarn installed on your machine.
- You need to have a PostgreSQL database set up and running. Update the `DATABASE_URL` in your `.env` file with your database connection string.
- If you're new to Prisma, check out their [quickstart guide](https://www.prisma.io/docs/getting-started/quickstart) for more information on database setup and management.

## 📂 Project Structure

```
t3-shadcn-boilerplate/
├── src/
│   ├── components/
│   │   └── ui/
│   ├── pages/
│   │   ├── api/
│   │   └── auth/
│   ├── server/
│   │   └── api/
│   ├── styles/
│   └── utils/
├── prisma/
├── public/
├── .github/
├── .env.example
├── next.config.js
├── package.json
├── README.md
└── tsconfig.json
```

## 📜 Scripts

- `yarn dev`: Start the development server
- `yarn build`: Build the production application
- `yarn start`: Start the production server
- `yarn lint`: Run ESLint
- `yarn db:push`: Push the Prisma schema to your database
- `yarn db:studio`: Open Prisma Studio

## 🔐 Environment Variables

Copy the `.env.example` file to `.env` and fill in the required variables:

```
DATABASE_URL="postgresql://user:password@localhost:5432/mydb"
NEXTAUTH_SECRET="your-nextauth-secret"
NEXTAUTH_URL="http://localhost:3000"
```

## 💾 Database

This boilerplate uses Prisma with PostgreSQL. To set up your database:

1. Make sure you have PostgreSQL installed and running
2. Update the `DATABASE_URL` in your `.env` file
3. Run `yarn db:push` to sync your Prisma schema with your database

## 🔒 Authentication

Authentication is handled by NextAuth.js. To configure providers or customize authentication behavior, check the `pages/api/auth/[...nextauth].ts` file.

## 🎨 Styling

This project uses Tailwind CSS for styling. The configuration file is located at `tailwind.config.js`. Global styles are in `src/styles/globals.css`.

## 🧩 Adding shadcn UI Components

To add a new shadcn UI component, run:

```bash
npx shadcn-ui@latest add <component-name>
```

For example, to add the `Button` component:

```bash
npx shadcn-ui@latest add button
```

## 🚢 Deployment

This project is ready to be deployed to platforms like Vercel, Netlify, or any other hosting service that supports Next.js applications.

For Vercel:

1. Push your code to a GitHub repository
2. Import your project to Vercel
3. Vercel will automatically detect that you're using Next.js and set up the build configuration for you
4. Set up your environment variables in the Vercel dashboard
5. Deploy!

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. Check out our [Contribution Guidelines](CONTRIBUTING.md) for more details.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Built with ❤️ using the [T3 Stack](https://create.t3.gg/) and [shadcn UI](https://ui.shadcn.com/). If you find this boilerplate helpful, please consider giving it a star ⭐️!

For any questions or feedback, please [open an issue](https://github.com/vichudo/t3-shadcn-boilerplate/issues) on GitHub.

Happy coding! 🎉
