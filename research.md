# CL Global Academy Website Redesign Research

## Company

CL Global Academy designs academic and cultural immersion programmes in Cambridge through its OxCam Programmes. The current official site describes academically rigorous courses that combine Cambridge-based teaching, cultural activities, Fellow Advisor support, project-based learning, and global student networking.

Key facts from the official site:

- Founded in 2009 by Allen and Katrina.
- Welcomes over 1,500 students to Cambridge each year.
- Reports 24,000+ graduates and 16 years designing and delivering Cambridge courses.
- Offers AI+, System Design & Engineering Thinking+, and OxCam Research+.
- Serves both university students and younger students aged 13-18.
- Has bases in the UK, Shanghai, and the US.
- States that CL Global Academy is independent and not affiliated with any universities.

## Business Category Benchmarks

The strongest academic summer/immersion programme websites make the first screen concrete: who the programme is for, where it takes place, why it is credible, and how to apply. They also separate course discovery, application, parent/student reassurance, and post-enrollment preparation.

Benchmarks reviewed:

- Immerse Education: Strong route separation by age, location, subject, online/on-campus format, and programme type. It foregrounds academic pathways and has a large knowledge-base structure for parent/student questions.
- Oxford Royale: Uses strong proof metrics, advisor CTAs, location routing, new programme modules, student experience video, and a high-polish editorial system.
- Reach Cambridge: Quickly states age range, Cambridge setting, expert-led subjects, college accommodation, global community, and BAC accreditation. It makes "Apply now" visible early and includes trust/review signals.
- Oxbridge Summer School: Compact, direct homepage with price, small-group teaching, subject examples, accommodation, pastoral support, testimonials, and next-step CTAs.

Reusable benchmark lesson: high-end education pages need both romance and operations. The best pages sell the feeling of Cambridge, but also answer practical questions: course fit, dates, age band, accommodation, supervision, application path, accreditation/proof, and what happens after enrollment.

## Target Company Research

CL Global Academy's official homepage currently emphasizes "Meticulously crafted academic programmes" and Cambridge-based academic/cultural experiences. The courses page names 2026 offerings:

- AI+ Course: Machine Learning+ or Data Science+, delivered in association with Cambridge Enterprise, Monday 10 August to Sunday 23 August 2026.
- System Design & Engineering Thinking+: partner content with the University of Cambridge Department of Engineering, Monday 27 July to Sunday 9 August 2026.
- OxCam Research+: for students aged 13-18, Monday 27 July to Sunday 9 August 2026.

The partnerships page clarifies the collaboration model, college partners, instructor network, and independence disclaimer. It says CL Global Academy collaborates with over 60 Cambridge professors and industry experts and has developed 100+ courses spanning 9 academic disciplines.

## Current Homepage / Linked Page Observations

Strengths:

- Beautiful Cambridge video/photo material in the first screen.
- Clear Cambridge location and academic tone.
- Strong proof metrics: annual students, alumni, years, acceptance statistic.
- Useful content about Authentic Cambridge Experiences, Fellow Advisors, Academic Excellence, and alumni testimonials.
- Real application CTA points to `https://jinshuju.com/f/L0N0o5`.
- Contact CTA uses `mailto:contact@clglobal.org`.
- Course page has detailed course descriptions and useful official links.
- Partnerships page has a Strikingly custom form and gives useful clarification around independence and collaborations.

Gaps:

- The homepage is visually atmospheric but does not expose the course decision paths soon enough.
- The video hero is strong, but the page could do more with nearby proof, course routing, and next-step clarity.
- The application process is a link, not an explained workflow.
- Course dates, audiences, and project outcomes are buried on the course page.
- The independence disclaimer exists, but should be visible near credibility claims so the page feels transparent.
- Contact paths are scattered; homepage could provide a clearer "who should contact whom" routing system.
- No explicit student journey tracker, despite a programme with clear stages: apply, select course, prepare, arrive, project, showcase, alumni network.

## Redesign Goal

Design a polished, contentful homepage for ambitious students, parents, academic partners, and institutions considering OxCam Programmes. The page should feel cinematic and prestigious without becoming vague. It should preserve the Cambridge video background, bring proof and course routes into the first decision area, and make the next action obvious.

The redesigned homepage centers on:

- A video hero with immediate application and course-routing CTAs.
- Proof metrics adjacent to the first decision.
- A programme journey tracker so students and parents understand the path from application to alumni network.
- Course cards with dates, audience, and project themes.
- Transparent partnership and independence language.
- A concise inquiry brief that preserves public mailto routes instead of inventing a private backend.

## Backend/API Reuse

Preserved public surfaces:

- Application URL: `https://jinshuju.com/f/L0N0o5`
- General email: `mailto:contact@clglobal.org`
- Partnership email discovered on courses page: `mailto:partnership@clglobal.org`
- Official course page: `https://www.clglobal.org/courses`
- Official partnerships page: `https://www.clglobal.org/partnerships`
- Official contact page: `https://www.clglobal.org/contact`
- Cambridge Enterprise course/partnership URL: `https://www.enterprise.cam.ac.uk/connecting-cambridge-innovation/global-outreach/cl-global-academy/`
- Department of Engineering training URL: `https://cebc.eng.cam.ac.uk/education/short-training-sessions`
- Social links from site data: LinkedIn, Instagram, YouTube.

Visible frontend details:

- Homepage has no public application form endpoint; application is an external Jinshuju link.
- Partnerships page uses a Strikingly custom form. Visible fields include Name, Email, and Message. The email input name is `$item1606282596776#email`. No stable public form `action` endpoint is exposed in static HTML, and submission appears dependent on Strikingly runtime/recaptcha. The redesign documents and links the live partnerships page rather than inventing a private Strikingly submit API.
- The redesign includes a static mailto-based inquiry brief only, with `action="mailto:contact@clglobal.org"`, `method="post"`, and `enctype="text/plain"`.

Preserved media:

- Hero background video: `https://player.vimeo.com/video/1062106828?background=1&api=1&autopause=0&autoplay=1&mute=1&badge=0&loop=1&portrait=0&title=0`
- Original Strikingly poster/fallback: `https://uploads.strikinglycdn.com/static/videos/1741024304/video/1988968907-e530cbaa3fe8783fac9970b2b3023bbe44139d44794005cdf466984c298733a8-d_1280`
- Official logo image: `https://custom-images.strikinglycdn.com/res/hrscywv4p/image/upload/c_limit,fl_lossy,h_630,w_1200,f_auto,q_auto/243274/119769_798809.png`

## Sources Reviewed

- https://www.clglobal.org/
- https://www.clglobal.org/courses
- https://www.clglobal.org/our-team
- https://www.clglobal.org/partnerships
- https://www.clglobal.org/contact
- https://www.enterprise.cam.ac.uk/connecting-cambridge-innovation/global-outreach/cl-global-academy/
- https://cebc.eng.cam.ac.uk/education/short-training-sessions
- https://www.immerse.education/
- https://www.oxford-royale.com/index
- https://www.reachcambridge.com/
- https://oxbridgesummerschool.com/
