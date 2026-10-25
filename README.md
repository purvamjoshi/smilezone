# Smile Zone Dental Clinic

Website for Smile Zone Dental Clinic, Jodhpur Gam, Satellite, Ahmedabad.

Run by Dr. Aashay Shah (BDS, MDS, Periodontist and Implantologist) and Dr. Disha Shah (BDS, MDS, Endodontist).

## What is in here

| Path | Purpose |
| --- | --- |
| `index.html` | The complete website. One self-contained file, images included. |
| `assets/doctors/` | Portraits of both doctors, full resolution |
| `assets/clinic/` | Photos of the treatment room, chairs, waiting lounge, consultation room, reception desk, and wash and storage area |
| `assets/brand/` | Logo with a transparent background, the tooth mark on its own, and the visiting card |

`index.html` has no build step and no dependencies. Open it in any browser to view it. The images inside it are embedded, so the page works even with no other files beside it. The `assets` folder holds the same media as separate files, at higher resolution, for social posts, the Google Business profile, printing, or handing to anyone who works on the site later.

## Sections of the page

1. Hero with call buttons and clinic details
2. Meet your dentists
3. Twelve dental treatments, grouped into everyday care, saving and replacing teeth, and gums, kids and smile
4. What happens on your first visit
5. Inside the clinic photo gallery
6. Visit us, with address, timings and directions
7. Frequently asked questions

## Built in

- Plain HTML and CSS, no framework
- Custom SVG illustrations for each of the twelve treatments
- Responsive from 320px phones upwards, with a call button pinned to the bottom on mobile
- Light and dark mode
- SEO meta tags and Schema.org structured data for a dental clinic and the FAQ

## Hosting

Any static host works, since the site is one file. To publish free with GitHub Pages, go to Settings, then Pages, and serve the `main` branch from the root folder.

## Editing

The content lives in `index.html`. Clinic details appear in more than one place, so when any of these change, update them everywhere:

- Phone numbers: `+91 97269 84858` and `+91 99091 52456`
- Address and the Google Maps directions links
- Timings: 10:00 am to 1:00 pm and 5:00 pm to 8:00 pm
- The `application/ld+json` block in `<head>`, which feeds Google

## Before going live

- Confirm which phone number belongs to which doctor
- Add the days the clinic is open, since only the timings are on the page
- Add a Google Maps embed or the clinic's exact map pin once the Google Business profile is live
- Add real patient reviews, with consent
