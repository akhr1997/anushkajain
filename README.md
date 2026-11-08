# Anushka Jain — Legal Dossier Portfolio

React implementation of the desktop and mobile Nush Website design exports supplied in this chat. The prior blue landing page has been replaced with the white, slate, and muted-blue dossier design.

## Run locally

```sh
npm install
npm run dev
```

Use the local URL printed by Vite.

## Production build

```sh
npm run build
npm run preview
```

Desktop uses the bordered two-column editorial layout, full chronology, credential matrix, and contact/archive section. Mobile uses a portrait-first profile, serif headings, stacked panels, experience tabs, and fixed bottom navigation. Responsive breakpoint: 700px.

Navigation and experience tabs work locally. The enquiry form validates the inputs and opens a prefilled email draft for the visitor to review and send; there is no server submission or enquiry storage. Resume buttons download the supplied LinkedIn profile PDF. The supplied portrait is used directly.

Content follows the provided design exports, including bar-admission labels and competency percentages. Verify these professional details before public release. Employment dates retain the overlap present in the supplied LinkedIn profile.

## Deploy on Netlify

Set the base directory to this project folder, the build command to `npm run build`, and the publish directory to `dist`. No environment variables or hosting-specific runtime are required. For a manual deployment, run `npm run build` and upload the generated `dist` folder.

Stack: React, Vite, Lucide icons, CSS. Fonts: Plus Jakarta Sans and Cormorant Garamond via Google Fonts with local fallbacks.
