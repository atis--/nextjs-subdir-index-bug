
# How to reproduce

```bash
npm install
npm run dev
```

This is the "getting started" tutorial from Next.js website with a subdirectory page added to it.

Navigate to `http://localhost:3000/subdir/` (with a **trailing slash**) and observe the page hang. Other routes (root and `/subdir` without trailing slash) work OK.

