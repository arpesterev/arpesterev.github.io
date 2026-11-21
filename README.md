# Personal website

Source for a bilingual personal website built with Next.js 14, React, TypeScript and Tailwind CSS. It includes work, education, skills and contact sections.

## Development

Use the checked-in npm lockfile:

```sh
npm ci
npm run dev
```

Open http://localhost:3000. For a production build, run `npm run build`. These commands are defined in `package.json`; they were not executed during this documentation update.

## Editing content

- [`src/data/resume.tsx`](src/data/resume.tsx): skills, work history, education and contact links.
- [`messages/ru-ru.json`](messages/ru-ru.json): Russian copy.
- [`messages/en-us.json`](messages/en-us.json): English copy.
- [`src/app/[locale]/page.tsx`](src/app/): localized page.
- [`src/components/`](src/components/): UI components.
- [`src/i18n/`](src/i18n/): locale routing.

A release-build workflow is checked into `.github/workflows/`; review it before changing deployment settings.

When updating the portfolio, check facts, links and dates in both languages. Do not add confidential employment details or material subject to an NDA.
