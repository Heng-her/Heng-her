# MASTER PROMPT — PREMIUM GITHUB PROFILE

Create a premium, professional GitHub Profile README system for **any developer, engineer, designer, researcher, creator, or technical professional**.

Generate:

1. `dark.svg`
2. `light.svg`
3. `README.md`

The SVGs must be self-contained, GitHub-compatible, responsive, animated, accessible, and usable directly inside a GitHub README.

This prompt is intentionally **generic**. Never hard-code a specific person's name, company, role, location, technology stack, project names, URLs, dates, metrics, or personal claims.

All personal information must come from the user's supplied profile data, uploaded files, reference images, or explicit instructions.

---

# 1. CORE OBJECTIVE

Design a high-end GitHub profile hero banner inspired by a modern:

- developer terminal
- code editor
- AI engineering interface
- premium portfolio
- system dashboard
- glassmorphism UI

The visual language should combine:

- professional engineering aesthetics
- terminal/editor chrome
- ASCII or dot-matrix portrait
- subtle futuristic details
- clean information hierarchy
- restrained neon accents
- premium glass surfaces
- excellent readability

The result should feel like a **real product interface**, not a generic AI-generated banner.

Do not make the profile look unnecessarily frontend-only, AI-only, backend-only, or design-only. Adapt the identity to the person's actual profile.

The banner should communicate the person's strongest professional identity quickly without duplicating the entire README.

---

# 2. INPUT / PERSONALIZATION SYSTEM

Before generating the SVG and README, extract or use the available user-provided information.

Possible fields include:

```text
Name:
Professional headline:
Primary roles:
Current company:
Current role:
Location:
Years of experience:
Specialization:
Primary technologies:
Secondary technologies:
AI / ML technologies:
Backend technologies:
Cloud / DevOps:
Architecture / systems:
Featured projects:
Experience:
Education:
Certifications:
Writing:
Portfolio:
GitHub:
LinkedIn:
Other social links:
Email:
Personal tagline:
Profile image:
Reference image:
```

Do not assume that every field exists.

If information is missing:

- omit the field
- reduce the visual content
- use a neutral generic label where appropriate
- never invent facts

Never invent:

- companies
- employment history
- education
- certifications
- awards
- metrics
- project achievements
- URLs
- technologies
- clients
- job titles
- years of experience

---

# 3. USER PROFILE HIERARCHY

Determine the person's strongest identity from the supplied information.

Examples:

```text
AI Engineer
Full-Stack Engineer
Backend Engineer
Frontend Engineer
Software Engineer
DevOps Engineer
Cloud Engineer
Data Engineer
Security Engineer
Open Source Developer
Designer / Developer
Research Engineer
Technical Writer
```

If the person has multiple specialties, combine them naturally.

Example:

```text
AI Engineer · Full-Stack Engineer · SaaS Builder
```

Do not force an AI identity if the supplied profile does not support it.

---

# 4. HERO CANVAS

Use:

```xml
width="1180"
height="610"
viewBox="0 0 1180 610"
```

Use a rounded outer frame with approximately:

```text
16–28px radius
```

The entire composition must remain inside a safe area.

Use an 8px-style spacing system wherever practical.

Avoid:

- overlapping text
- clipped text
- excessive empty space
- cramped panels
- random decorative shapes
- inconsistent alignment

---

# 5. HIGH-LEVEL LAYOUT

Use a two-column composition.

### LEFT — VISUAL / IDENTITY

Approximately:

```text
38–40% width
```

Can contain:

- terminal/editor header
- `VISUAL.MAP`
- ASCII portrait
- visual identity
- subtle scanlines
- command prompt
- compact tagline

### RIGHT — SYSTEM.INFO

Approximately:

```text
60–62% width
```

Can contain:

1. Name
2. Professional headline
3. Current role/company if available
4. Location if useful
5. Experience if available
6. Core focus
7. Selected technology stack
8. Selected projects
9. Links

Keep the information concise.

The banner is not a replacement for the README.

---

# 6. REFERENCE IMAGE HANDLING

If the user supplies a reference image:

Use it to understand:

- composition
- spacing
- visual hierarchy
- typography
- terminal styling
- panel structure
- color relationships
- animation direction
- portrait treatment

Do not blindly copy unrelated text or branding from the reference.

Treat the reference as **visual art direction**, not as profile data.

If the user supplies a personal photograph:

- use it as the portrait source
- crop it appropriately
- preserve recognizable characteristics
- remove irrelevant background elements
- use the portrait only as instructed

---

# 7. ASCII / DOT-MATRIX PORTRAIT

When a profile image is supplied and the user requests an ASCII portrait:

Do NOT display the original raster photograph in the final SVG.

Convert the portrait into a dense SVG text / character representation.

Use:

```xml
<text class="ascii">...</text>
```

or SVG `<tspan>` structures.

The portrait should be rendered from characters rather than an embedded bitmap.

### Preferred crop

Unless the user requests otherwise:

```text
head + shoulders + upper chest
```

Remove:

- legs
- shoes
- unrelated background
- distracting objects
- excessive body area

Preserve important visual features when visible:

- hairstyle
- glasses
- beard
- face shape
- clothing silhouette
- distinctive facial contours

Do not alter the person's identity or invent facial features.

---

# 8. ASCII CHARACTER RENDERING

Use a dense character ramp such as:

```text
 .·:+*#%@
```

or another visually appropriate monochrome/gradient character set.

Use brightness and edge information to preserve:

- face contours
- hair
- glasses
- clothing
- silhouette

Use a monospace font:

```css
ui-monospace,
SFMono-Regular,
Menlo,
Monaco,
Consolas,
monospace
```

Keep character spacing tight enough to resemble the supplied reference.

The portrait should look like a terminal-rendered image composed from many tiny characters or dots.

---

# 9. ASCII PORTRAIT ANIMATION

Use SMIL only.

No JavaScript.

Animate the portrait with subtle effects such as:

1. line-by-line reveal
2. slight opacity transition
3. subtle vertical float
4. slow gradient movement
5. horizontal scanline
6. restrained glow pulse
7. occasional low-intensity signal flicker

Example:

```xml
<animate
  attributeName="opacity"
  values="0;1"
  dur=".25s"
  fill="freeze"
/>
```

Stagger rows slightly.

Avoid making the portrait flash, jump, or constantly glitch.

---

# 10. TERMINAL HEADER

Create a realistic editor/terminal header.

Possible structure:

```text
● ● ●    user@developer:~    [ ONLINE ]
```

Use three terminal controls:

```text
red
yellow
green
```

The actual username/host should be generated from supplied profile information when appropriate.

If no username is provided, use a neutral placeholder such as:

```text
developer@profile
```

Do not invent a company hostname.

---

# 11. LEFT IDENTITY CONTENT

Keep this section concise.

Possible structure:

```text
[PROFILE / ENGINEERING]

Professional Headline

Short supporting phrase

~/profile $ build --ship
```

The exact wording must come from the user's profile or be generic enough not to make unsupported claims.

Do not repeat the entire README here.

---

# 12. RIGHT SYSTEM.INFO PANEL

Create a premium glass terminal panel.

Heading:

```text
SYSTEM.INFO
```

Possible terminal prompt:

```text
user@developer:~$ ./profile.sh
```

Then show only information that exists.

Recommended fields:

```text
Name
Role
Company
Location
Experience
Focus
Stack
Building
```

Example structure:

```text
> NAME        ...
> ROLE        ...
> COMPANY     ...
> LOCATION    ...
> EXPERIENCE  ...
> FOCUS       ...
> STACK       ...
```

If a field is unavailable, remove it rather than inventing it.

Use concise values.

---

# 13. ROLE ROTATION

If the person has multiple documented roles/specialties, optionally rotate them.

Example:

```text
Software Engineer
AI Engineer
Full-Stack Engineer
Backend Engineer
SaaS Builder
```

Rules:

- derive roles from supplied information
- do not exaggerate
- reveal character-by-character where practical
- show a blinking cursor
- fade smoothly
- loop continuously
- use SMIL only

If only one role is available, use a static role instead of forcing unnecessary animation.

---

# 14. PROFESSIONAL FOCUS

Highlight the person's actual strongest technical areas.

Examples:

```text
AI / ML
LLMs
Frontend
Backend
Cloud
DevOps
Distributed Systems
System Design
Data
Security
Mobile
SaaS
Developer Tooling
Automation
```

Never assume a technology that the profile does not mention.

---

# 15. TECH STACK

Create a compact grid of technology pills.

Derive the technologies from the user's actual profile.

Possible categories:

```text
Languages
AI / ML
Frontend
Backend
Databases
Cloud
DevOps
Architecture
Testing
Tools
```

Do not show every technology.

Prefer the strongest and most relevant technologies.

Each pill may contain:

- small status dot
- subtle border
- gradient highlight
- soft glow
- tiny floating animation

Animation must remain restrained.

---

# 16. PROJECTS

Show only selected projects.

For each project use:

```text
Project Name    Short factual description
```

Descriptions should be one short phrase.

Use actual projects supplied by the user.

Never invent:

- project metrics
- users
- revenue
- performance numbers
- clients
- achievements

The purpose is to provide proof of engineering breadth without creating a crowded project catalog.

---

# 17. LINKS

Use only links supplied by the user.

Possible links:

```text
GitHub
LinkedIn
Portfolio
Website
Medium
X
YouTube
Email
```

Do not invent URLs.

Keep links compact and visually secondary to the main identity.

---

# 18. OPTIONAL TOP NAVIGATION

A subtle editor-style navigation bar may contain:

```text
Code    Projects    Experience    Contact
```

or other appropriate sections.

It is decorative and should not dominate the banner.

Do not imply that these are clickable inside the SVG unless the SVG actually contains valid links.

---

# 19. DARK THEME

Create a premium dark theme.

Suggested palette:

```text
Background:
#030712
#07111F
#0B1220

Panel:
#0F172A

Primary text:
#F8FAFC

Muted:
#94A3B8

Accent:
#7C3AED
#22D3EE
#10B981
```

Use a restrained animated gradient such as:

```text
violet → cyan → emerald
```

The colors can be adapted to the user's preferred visual identity.

Use:

- radial gradients
- subtle grid
- fine noise
- floating particles
- glass reflections
- border shimmer

Keep the background understated.

---

# 20. LIGHT THEME

Create a genuinely designed light theme.

Do NOT simply invert the dark SVG.

Suggested palette:

```text
Background:
#FFFFFF
#F8FAFC
#EEF6FF

Text:
#0F172A
#334155
#475569

Accent:
#2563EB
#06B6D4
#10B981
```

Use:

- translucent white glass
- subtle shadows
- soft borders
- blue/cyan/violet accents
- lower glow intensity

Maintain the same layout and information hierarchy as dark mode.

---

# 21. GLASSMORPHISM

Use transparent glass panels.

Suggested opacity:

```xml
fill-opacity=".20"
fill-opacity=".25"
fill-opacity=".35"
```

Combine with:

- translucent surfaces
- thin borders
- subtle gradients
- soft shadows
- restrained glow

Do not use heavy opaque cards unless necessary for readability.

---

# 22. BACKGROUND DEPTH

Use subtle layers:

```text
radial gradients
grid
fine noise
particles
scanlines
glass reflections
border shimmer
```

Optional animated elements:

- drifting particles
- slowly moving radial gradients
- border highlight
- subtle reflection sweep

Do not overload the composition.

---

# 23. ANIMATION SYSTEM

Use only native SVG animation:

```text
SMIL
<animate>
<animateTransform>
<animateMotion>
```

Allowed SVG features:

```text
linearGradient
radialGradient
filter
mask
clipPath
animate
animateTransform
animateMotion
```

Do NOT use:

- JavaScript
- external JavaScript
- external CSS
- CSS keyframe animation
- canvas
- iframe
- video
- external animation libraries

Animations should:

- loop smoothly
- be subtle
- remain readable
- not distract from the profile

---

# 24. SEQUENTIAL INFORMATION REVEAL

Reveal important information in a deliberate sequence.

Suggested sequence:

```text
1. terminal frame
2. portrait
3. name
4. headline
5. role
6. profile rows
7. skills
8. links
```

Use staggered opacity/transform animations.

The first render should still remain understandable if animation is not supported.

---

# 25. TYPING EFFECT

For animated text, prefer true character-by-character or mask-based reveal.

Avoid simply sliding a rectangle across an already-visible phrase if that makes it look like a block wipe.

Use:

- `<mask>`
- `<clipPath>`
- staggered `<tspan>` opacity
- animated width/reveal regions

where practical.

Always keep the cursor immediately after the visible text.

---

# 26. TYPOGRAPHY

Use monospace typography for terminal UI.

Preferred:

```text
ui-monospace
SFMono-Regular
Menlo
Monaco
Consolas
monospace
```

Hierarchy:

```text
Name:
large / bold

Headline:
medium / accent

Section headings:
small / uppercase / letter-spaced

Labels:
muted or cyan

Values:
high contrast

ASCII:
small dense monospace
```

Keep typography consistent between dark and light themes.

---

# 27. ALIGNMENT — CRITICAL

The composition must feel symmetrical and intentional.

### LEFT PANEL

- center the ASCII portrait inside its card
- maintain equal visual whitespace
- center or consistently align the supporting identity content
- do not allow the portrait to hug the left edge

### RIGHT PANEL

Use a balanced information grid.

Recommended:

```text
label column → right aligned
value column → left aligned
```

or another clearly balanced layout.

Avoid:

- excessive left anchoring
- inconsistent x positions
- drifting values
- uneven card padding
- awkward empty regions

Major headings can be centered when appropriate.

The entire banner should feel visually balanced rather than like a dashboard pushed toward one side.

---

# 28. INFORMATION DENSITY

Follow this principle:

```text
Banner = identity + strongest technical signals + selected proof
README = complete information
```

Do not duplicate long README sections.

Avoid:

- long biographies
- huge skill walls
- detailed employment descriptions
- every project
- every technology
- repeated links
- repeated role descriptions
- unnecessary statistics

---

# 29. PROFESSIONAL VISUAL STYLE

The result should feel like:

```text
Professional Engineer
+
Technical Identity
+
Terminal UI
+
Premium Portfolio
```

Avoid:

```text
gaming UI
childish neon
generic hacker aesthetic
excessive glitch
too many colors
cluttered dashboards
random badges
```

Use neon accents as highlights, not as the entire design.

---

# 30. ACCESSIBILITY

Add:

```xml
role="img"
aria-label="..."
```

The accessible label should be generated from the supplied profile information.

Use sufficient contrast.

Do not rely entirely on color to communicate meaning.

Keep important text as real SVG text.

---

# 31. GITHUB COMPATIBILITY

The SVG must work when committed directly into a GitHub repository.

The SVG must be self-contained.

Do not use:

- JavaScript
- external fonts
- external images
- remote CSS
- remote assets
- external animation libraries

When a profile image is converted to ASCII, the final SVG should contain the resulting character data directly.

Do not embed the original raster photo unless the user explicitly requests a raster image.

---

# 32. README THEME SWITCHING

Use GitHub's theme-aware `<picture>` pattern:

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./light.svg" />
  <img src="./dark.svg" alt="Professional developer profile" />
</picture>
```

Use the user's actual files and accessibility description.

Do not display both SVGs simultaneously.

---

# 33. README STRUCTURE

Create a README that complements the banner.

Suggested structure:

```text
Hero
Short introduction
About / Focus
Experience
Featured Projects
Engineering Stack
Writing / Content
GitHub Activity
Connect
```

Only include sections supported by the supplied information.

The README can contain more detail than the hero.

The hero should remain concise.

---

# 34. DATA ACCURACY

This is mandatory.

Use only:

- user-provided information
- supplied files
- supplied profile links
- supplied reference images
- explicit user instructions

Never invent factual profile information.

If information conflicts across supplied sources:

- prefer the most recent explicit user-provided information
- if the conflict cannot be resolved, omit the disputed detail
- do not silently manufacture a resolution

Do not invent metrics, achievements, certifications, education, employment dates, clients, revenue, or technical claims.

---

# 35. FINAL QUALITY CHECK

Before delivering the files, verify:

- [ ] `dark.svg` exists
- [ ] `light.svg` exists
- [ ] optional `README.md` exists
- [ ] both SVGs use the same composition
- [ ] dark and light themes are genuinely designed separately
- [ ] supplied portrait is used when requested
- [ ] portrait is appropriately cropped
- [ ] ASCII portrait is represented using SVG characters when requested
- [ ] no unintended raster portrait is embedded
- [ ] no external assets
- [ ] no JavaScript
- [ ] no external CSS
- [ ] SMIL animations are used
- [ ] SVG is valid XML
- [ ] special characters are escaped
- [ ] accessibility attributes exist
- [ ] text is readable
- [ ] portrait is centered
- [ ] right-side information is balanced
- [ ] no text overlaps
- [ ] no content is clipped
- [ ] AI/technical identity is only emphasized when supported by the profile
- [ ] projects are factual
- [ ] links are factual
- [ ] no unsupported achievements or claims
- [ ] animation is subtle
- [ ] GitHub `<picture>` theme switching works
- [ ] banner does not duplicate the entire README

---

# 36. REFERENCE DIRECTION

If the user supplies a visual reference similar to:

```text
VISUAL.MAP
        +
SYSTEM.INFO
```

use that as the primary composition direction:

```text
LEFT
ASCII / visual identity

RIGHT
terminal / system information
```

Preserve the reference's important visual characteristics:

- terminal/editor chrome
- monospace typography
- ASCII portrait
- thin luminous borders
- cyan / violet / blue accents
- glass panels
- scanlines
- restrained futuristic details
- dark/light variants

But redesign the content and proportions for the actual user.

Do not copy unrelated names, labels, projects, companies, URLs, or personal information from the reference.

---

# 37. FINAL DELIVERABLE

Return:

```text
dark.svg
light.svg
README.md
```

and ensure each file is ready to place directly into a GitHub profile repository.

The final result should feel:

```text
premium
minimal
technical
intelligent
polished
aligned
modern
personalized
production-quality
```

The design must adapt to **any user's actual professional identity** while preserving the same premium terminal / ASCII / glassmorphism design system.

Social
Follow @vaibhav.create on Instagram for more such videos, AI workflows, cinematic websites, and creative development content.
🌐 Portfolio Website
https://vaibhav-create.vercel.app
💻 Cinematic Portfolio Repository
https://github.com/VaibhavKhushalani/cinematic-portfolio
🐙 GitHub
https://github.com/VaibhavKhushalani
💼 LinkedIn
https://www.linkedin.com/in/vaibhav-khushalani-760217136
✍️ Medium
https://medium.com/@vaibhavkhushalani
📸 Instagram
https://www.instagram.com/vaibhav.create
▶️ YouTube
https://www.youtube.com/@vaibhav.create
❤️ Thanks again for the support!
