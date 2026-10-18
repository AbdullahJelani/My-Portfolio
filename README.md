# Abdullah Jelani — Portfolio

My personal portfolio website, hosted on GitHub Pages:
https://abdullahjelani.github.io/My-Portfolio/

## About

I'm a digital marketer, sales leader and aspiring web developer from Swat,
Pakistan. This site showcases:

- My professional background (12+ years in pharma sales & brand growth)
- Digital marketing portfolio (live FB/IG/web work for a health brand)
- Education and certifications
- A few small web projects (Movie Ranking, Birthday Invite)

## Tech

- Plain HTML5 & CSS3 (no build step)
- Font Awesome for icons
- One shared stylesheet: `Assets/css/style.css`

## Structure

```
.
├── index.html                       # Home / portfolio landing page
├── README.md
├── Assets/
│   ├── css/style.css                # Shared stylesheet
│   ├── images/                      # Profile & project images
│   └── resume/abdullah-resume.pdf   # Downloadable CV
└── Public/
    ├── about.html                   # About page
    ├── contact.html                 # Contact page
    ├── Movie-ranking.html           # Small project
    └── Birthday-invite.html         # Small project
```

All `Public/*.html` pages link back to `../index.html` for consistent
navigation.