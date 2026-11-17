# KATC website

Responsive React, TypeScript and Vite website for Kerala Ayurvedic Treatment
Center. The original KATC logo, clinic photographs, doctor photograph, treatment
images and introduction video are reused.

## Run locally

```sh
npm install
npm run dev
```

## Build and preview

```sh
npm run build
npm run preview
```

The application uses React Router routes at `/`, `/about`, `/treatments`,
`/doctor`, `/ayurveda`, `/gallery` and `/contact`. Configure the deployment host
to serve `index.html` for these paths so direct links and refreshes work.

The production build includes `public/robots.txt` and `public/sitemap.xml`.
Treatment information is educational and does not promise outcomes; KATC
operates on a walk-in basis. No appointment booking is implemented.
