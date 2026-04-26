# Reflection — CYA-02
**Srishanth Surakanti | Personal Portfolio Website**

---

## Activity Description

I built my personal portfolio site from scratch. No templates. The goal was something I'd actually want to hand a recruiter, not something I put together to check a box. It runs on HTML, CSS, and vanilla JavaScript, deployed through GitHub Pages. 25 commits, 69 deployments, and I'm still working on it. Some of the early decisions have already been replaced entirely from iteration.

---

## Technical and Professional Decisions

The popup secondary nav bar was the most interesting problem on this project. As you scroll between sections, a small nav appears and shows different action links based on where you are. Work shows a GitHub link. About drops in a resume download. Contact shows email and socials. It sounds simple but getting it to actually feel right took a while. There's scroll detection, section boundary tracking, and DOM updates that all have to happen without any flash or flicker. I wrote it in vanilla JavaScript because I didn't want to reach for a library until I understood what the library would even be doing for me.

The CSS is split across three files: a shared base, a desktop sheet, and a mobile sheet. More overhead upfront, but it made mobile iteration a lot less risky. I could change something on mobile without worrying about breaking desktop. Worth it.

The custom cursor was another deliberate detail. I wanted it to behave like the iPadOS pointer: not just a dot that follows the mouse, but something that morphs and snaps to interactive elements the way Apple's cursor does. Replicating that feel in a browser without any framework was its own small problem to solve.

Building this at all was a professional decision. A hand-built portfolio tells a different story than a Squarespace page.

---

## Contributions

This is entirely my own work. Every design call, every line of code, every deployment. I'm still the only contributor.

---

## Quality Assessment

I'd call it proficient with work left to do. The core experience is solid and the site is live. The next real milestone is the wallpapers storefront. I make minimalist and abstract wallpapers and the whole reason I built a dedicated section for them is to sell them directly through the site. The section is designed and in the nav, but it's not connected to Gumroad yet. That's the most concrete thing on my list. Beyond that, the Work section is still showing a placeholder and I want to replace it with real case studies. If I started over I'd nail down the content structure before touching any CSS. I kept adjusting layout decisions mid-build because the content kept shifting. Figure out what you're saying first, then figure out how it looks.

---

## Career Alignment

This is the most practical thing I did for my career this semester. It's the first link I send when someone asks for my portfolio. Writing it from scratch in real tools shows something a template can't. I want to work in software or ML engineering where technical depth and product quality both matter. This project is what that looks like in practice.
