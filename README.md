# Next.js 15 App Router Link Issue

This repository demonstrates a bug encountered in Next.js 15's App Router where links defined using the `next/link` component fail to navigate to the intended pages.  Despite using correct `href` values, the application always redirects to the root path.  The solution involves ensuring proper file structure and route configuration within the `app` directory.