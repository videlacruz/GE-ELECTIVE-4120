# Activity 3 — Social Media Infographics and Mini Project Documentation

## Output: Infographic and Mini Project — "NO JOB. NOT ENOUGH JOB?" + JOBLINK PH

Below is the project documentation, explanation of the concept, design choices, creative process, and a ready-to-use responsive HTML/CSS template you can use to present the infographic as a social-media-ready web card.

---

## I. Introduction

Unemployment and underemployment are social and economic issues that still persist in the
Philippines. Unemployment means being ready and able to work but not having a job, while
underemployment entails having a job but not being fully satisfied with its conditions, i.e.
wanting extra hours, a different job, etc. Both problems can lead to poverty, stress, lack of
professional growth and difficulties in meeting basic needs.

The infographic "NO JOB. NOT ENOUGH JOB?" sheds light on the reasons for the issue,
people who are affected, possible outcomes and solutions for unemployment and
underemployment. The infographic stresses the point that having a job does not necessarily
mean having enough working hours, enough income or opportunities for professional
development.

## II. Proposed IT/Technology-Enabled Solution

**JOBLINK PH: A Smart Employment and Skills-Matching Platform**

The proposed solution for unemployment and underemployment is the JOBLINK PH platform.
This mobile and web-based platform aims at connecting people with jobs and training
possibilities.

The platform would have a matching algorithm that compares the user's education, skills,
previous work experience, preferred place of residence and working hours against existing job
offers. Thus, it can be helpful for finding proper employment and getting additional jobs or
opportunities for better positions.

## III. Key Features

1. **Smart Job Matching**
   - The system suggests job offers according to the user's skills, education, preferences, working
     hours and preferred location.
2. **Skills and Training Recommendations**
   - The system offers online courses and trainings according to the skills most requested by
     employers.
3. **Underemployment Assistance**
   - Employed users can look for part-time jobs, extra working hours, freelance options, and jobs
     with better career prospects.
4. **Verification of Job Openings**
   - Employers can post vacant positions while the website will verify openings to decrease risk of
     encountering fake or misleading job ads.
5. **Digital CV Maker**
   - Users will be able to make digital CVs and apply to suitable employers with ease.
6. **Employment Monitoring Dashboard**
   - Users will be able to track applications, interviews, job offers, training received, and other
     recommendations.

## IV. Explanation of How the Proposed Solution Will Address the Problem

JobLink PH can help to solve unemployment issues by facilitating the process of looking for jobs
and connecting people who need to find employment with employers. This solution can also
assist in solving the problem of underemployment through access to extra hours of work,
part-time jobs, and better job matches for employed individuals.

Furthermore, this solution will allow for addressing skills mismatch issues since it will be able to
identify skills gap between user’s current skills and requirements for the jobs available.
Personalized training recommendations can allow users to enhance their skills.

## V. Anticipated Benefits

The proposed system would be able to:

- Increase access to employment opportunities
- Enable workers to get a job according to their capabilities
- Provide additional employment opportunities to underemployed workers
- Support ongoing skills development
- Simplify the process of looking for job opportunities
- Facilitate the process of finding qualified candidates by employers

## VI. Conclusion

Unemployment and underemployment are not only a lack of jobs but also availability of
appropriate and adequate employment. Technology-based solutions like JobLink PH will be able
to provide a means by which Filipino workers will be connected to employers, training services,
and better employment opportunities. With the use of technology in job matching and skills
development, the proposed solution can help in generating more and better job

---

## Design concept, choices, and creative process

Concept summary:
- The infographic and mini project center on clarity and empathy — presenting data and
  solution options with a visual hierarchy that helps users (job seekers, underemployed
  workers, and employers) quickly understand the problem and the proposed solution.

Design choices:
- Color: Use a limited palette with high contrast — e.g., a strong accent color (warm orange or
  teal) to call out problems and CTAs, neutral background (light gray or off-white), and a
  supportive secondary color for positive outcomes (green hues) for success stories or
  benefits.
- Typography: Clean, legible sans-serif for headers (bold, large) and a neutral sans-serif for
  body text. Maintain readable sizes for social media cards (header ~28–36px, body ~14–18px
  when exported at 1200×630px). Use generous line-height and spacing.
- Layout: Vertical card composition suited for social platforms (Instagram, Facebook, LinkedIn)
  or adapted horizontally for Twitter/X and LinkedIn sharing. Break content into digestible
  blocks: Problem, Who's Affected, Causes, Consequences, Solutions, and Call-to-Action.
- Imagery & icons: Use simple icons (people, gears, briefcase, graduation cap) and minimal
  illustrations to keep focus on the message. Maintain consistent icon stroke weight.
- Data visualization: Use simple charts (bar or donut) to show key stats; show percentages
  and short labels rather than dense tables.
- Accessibility: Ensure color contrast ratios meet WCAG AA for text, provide alt text for
  images, and avoid relying on color alone to convey meaning.

Creative process:
1. Research: Gather data on unemployment and underemployment rates, causes, and
   demographic groups affected.
2. Sketch: Draft several layout options on paper or a wireframing tool, focusing on
   hierarchy and how the user’s eye will travel.
3. Design: Move the preferred sketch into a design tool (Figma, Canva, or Illustrator). Choose
   palette, fonts, and icons. Create components for each block so different versions (vertical
   vs horizontal) can be exported quickly.
4. Iterate: Get feedback from peers — refine language to be concise and empathetic.
5. Produce: Export PNG/JPEG in social sizes (1080×1350 for Instagram portrait; 1200×630 for
   link previews; 1080×1080 square), and prepare the web card template below for embedding.

---

## Mini Project Documentation — Technical notes

Objective: Produce a sharable infographic and a simple web card that presents the same
information and link to the JobLink PH prototype or documentation.

Recommended tech stack for the prototype:
- Frontend: HTML/CSS, optionally small JS for interactivity (filtering jobs, expand/collapse)
- Frameworks: Lightweight — use Tailwind CSS or plain CSS for static demo. If you want
  a production platform later: React or Vue with a backend API.
- Backend (optional for demo): Node/Express or Firebase for quick prototyping.
- Database: Firestore or a relational DB (Postgres) depending on scale. For matching
  algorithm demos, mock data or JSON files are sufficient.

Assets:
- Placeholders for icons and illustrations (SVG).
- Replace placeholder text and data with verified statistics and sources when available.

---

## Social-media-ready responsive HTML/CSS template (use for embedding or preview)

Below is a simple responsive card you can drop into a page and screenshot/export as a
PNG for social posts. Replace text and colors as needed and include your exported images
when sharing on social platforms.

```html
<!-- name=infographic-card.html -->
<div class="card">
  <header class="card-header">
    <h1>NO JOB. NOT ENOUGH JOB?</h1>
    <p class="sub">Unemployment & underemployment in the Philippines</p>
  </header>
  <section class="card-body">
    <p class="lead">Having a job doesn't always mean enough hours, income, or growth.</p>
    <ul class="points">
      <li><strong>Who’s affected:</strong> fresh graduates, part-time workers, mothers returning to work</li>
      <li><strong>Causes:</strong> skills mismatch, lack of open positions, geographic barriers</li>
      <li><strong>Solutions:</strong> JobLink PH — smart matching, training, underemployment assistance</li>
    </ul>
  </section>
  <footer class="card-footer">
    <a class="cta" href="#">Learn about JobLink PH</a>
  </footer>
</div>

<style>
  :root{--bg:#f7f7f7;--card:#ffffff;--accent:#0077b6;--muted:#6b7280;--success:#16a34a}
  .card{width:100%;max-width:900px;margin:0 auto;background:var(--card);border-radius:12px;padding:28px;box-shadow:0 8px 24px rgba(9,30,66,.08);font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,'Helvetica Neue',Arial}
  .card-header h1{font-size:28px;margin:0;color:var(--accent)}
  .card-header .sub{color:var(--muted);margin-top:6px}
  .card-body{margin-top:18px}
  .lead{font-size:18px;margin-bottom:12px}
  .points{list-style:none;padding:0;margin:0;display:grid;gap:8px}
  .points li{background:#f3f4f6;padding:10px;border-radius:8px;color:#111827}
  .card-footer{display:flex;justify-content:flex-end;margin-top:18px}
  .cta{background:var(--accent);color:white;padding:10px 16px;border-radius:8px;text-decoration:none}
  @media (max-width:480px){.card{padding:18px}.card-header h1{font-size:22px}.lead{font-size:16px}}
</style>
```

Notes for using the template:
- To export as a social image: open this HTML in a browser, set the viewport to the
  target dimension (e.g., 1200×630), and take a screenshot or use a headless screenshot
  tool (Puppeteer, Playwright) to generate the PNG.
- Replace the CTA href with the actual JobLink PH prototype or a PDF of the full report.

---

## Accessibility and captioning
- Provide alt text for the exported image when posting: e.g., "Infographic titled 'NO JOB.
  NOT ENOUGH JOB?' summarizing causes and solutions for unemployment and underemployment
  in the Philippines, promoting JobLink PH as a skills-matching and training platform."
- Include a short text paragraph with the post describing key facts so that screen reader
  users and search engines can read the content.

---

## Credits and references
- Design and content by: [Your name]
- Prototype idea: JobLink PH — concept for this activity
- Replace with specific data sources (PSA, DOLE, World Bank) when you publish the
  infographic publicly.

---

If you want, I can also:
- Export a ready PNG/JPEG for a chosen social size from this template.
- Create a Figma file or Canva layout using these texts and the color palette.
- Produce a short caption and hashtags tailored for Facebook, Instagram, LinkedIn, and
  Twitter/X.

