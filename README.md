# gluestack-ui v2 Experimental Initiative with Expo

This repository is an experimental project for building and testing applications with **gluestack-ui v2**, a universal and accessible UI component library for React, React Native, and Next.js.

## About gluestack-ui v2

gluestack-ui v2 is a significant evolution from its predecessors, built with a modern, modular, and developer-friendly approach. It's designed to be unbundled, allowing you to copy and paste only the components you need directly into your project. This results in smaller bundle sizes and gives you full control over your codebase.

The library is built on top of [NativeWind](https://www.nativewind.dev/), enabling you to use the power of [Tailwind CSS](https://tailwindcss.com/) for styling your universal components.

### Key Features

- **Universal & Accessible**: Write once, run anywhere. Components are designed to work seamlessly across web and mobile, with accessibility built-in.
- **Modular by Design**: Instead of a bundled package, you can pick and choose components, copying them directly into your project.
- **Styled with NativeWind**: Leverage the full power of Tailwind CSS for styling, providing a familiar and powerful styling experience.
- **React Server Components (RSC) Support**: Optimized for performance with support for RSC.
- **Figma UI Kit**: A comprehensive Figma kit for designers to ensure design and development are in sync.
- **VS Code Extension**: Snippets and tools to speed up your development workflow.
- **Highly Customizable**: A non-opinionated design approach gives you the freedom to create your own design system.

## Getting Started with this Project

This project is an [Expo](https://expo.dev) application, providing a perfect environment to experiment with `gluestack-ui` v2 on both web and mobile platforms.

### Getting Started

1.  **Install dependencies**

    ```bash
    bun install
    ```

2.  **Start the development server**

    ```bash
    bunx expo start
    ```

This will open the Expo developer tools, where you can choose to run the app on an Android emulator, iOS simulator, or in the browser (for React Native Web).

### Generating Native Projects (`prebuild`)

If you want to run the project with native code or add custom native modifications, you'll need to generate the native `android` and `ios` directories. You can do this with the `prebuild` command:

```bash
bunx expo prebuild --clean
```

The `--clean` flag ensures that you start with a fresh set of native directories based on your current configuration. After running `prebuild`, you can launch the app on a specific platform:

```bash
bunx expo run:ios
bunx expo run:android
```

### Adding gluestack-ui v2 Components

Adding components from `gluestack-ui` v2 is straightforward:

1.  Browse the components in the [official documentation](https://gluestack.io/ui/docs/home/overview/introduction).
2.  Find a component you want to use.
3.  Copy the code for the component and paste it into your project.
4.  Install any necessary dependencies that the component might have.

## Learn More

- **[gluestack-ui Documentation](https://gluestack.io/ui/docs/home/overview/introduction)**: The official documentation for gluestack-ui v2.
- **[gluestack-ui Blog](https://gluestack.io/blogs)**: Stay up-to-date with the latest news and articles.

## Join the Community

- **[Discord](https://discord.com/invite/gluestack)**: Chat with other community members and the team.
- **[Twitter](https://twitter.com/gluestack_io)**: Follow for announcements and updates.
- **[GitHub](https://github.com/gluestack/gluestack-ui)**: Contribute to the project.
