# Next.js OpenAI Chat UI

A **Next.js 14** frontend application for interacting with a NestJS OpenAI backend.  
Implements a simple chat interface that sends messages to the backend and displays AI-generated responses.

---

## Features

- Responsive chat UI built with **Tailwind CSS** and **DaisyUI**
- Integration with **NestJS OpenAI API**
- Environment-based configuration via `.env.local`
- Real-time message rendering

---

## Getting Started

### Prerequisites

- Node.js v20+
- [pnpm](https://pnpm.io/) installed globally
- Running instance of the [NestJS OpenAI Service](../nestjs-openai)

---

### Setup

1. Clone the repository:

   ```bash
   git clone <your-frontend-repo-url>
   cd nextjs-openai-chat
   ```

````

2.  Install dependencies:

    ```bash
    pnpm install

    ```

3.  Create a `.env.local` file (see `.env.local.example`):

    ```env
    # API URL for the backend
    NEXT_PUBLIC_API_URL=http://localhost:3001

    ```

4.  Run the development server:

    ```bash
    pnpm dev

    ```

5.  Open the app in your browser:

    ```
    http://localhost:3000

    ```


----------

## Project Status

-   ✅ Chat UI implemented

-   ✅ API integration with backend

-   ✅ Tailwind CSS + DaisyUI styling applied

-   🚀 Further improvements planned (loading states, error handling, message persistence)


----------

## Notes

-   Environment variables prefixed with `NEXT_PUBLIC_` are **required** for use in client-side code.

-   The `.env.local` file is ignored by git. Use `.env.local.example` as a template for configuration.

-   For a complete experience, ensure the backend server is running and accessible.

-   DaisyUI provides prebuilt components and themes for styling.
````
