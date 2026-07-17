# 1. Initialize Next.js (App Router, TypeScript, Tailwind, ESLint)
npx create-next-app@latest ai-intelligence-hub --typescript --tailwind --eslint --app --src-dir --import-alias "@/*"

cd ai-intelligence-hub

# 2. Install Shadcn UI (Premium component library)
npx shadcn-ui@latest init

# 3. Install Supabase SSR for secure Next.js integration
npm install @supabase/ssr @supabase/supabase-js

# 4. Install animations and utilities
npm install framer-motion lucide-react date-framer
