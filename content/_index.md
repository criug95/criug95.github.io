---
title: Home
type: landing
sections:
  - block: hero
    content:
      title: ""
      text: ""
    design:
      background:
        image:
          filename: headers/hero.jpg
        image_darken: 0
        image_parallax: true
        image_size: cover
        image_position: center

  - block: resume-biography
    content:
      title: "About me"
      username: admin        # usa il profilo in content/authors/admin/_index.md
      text: |
        Welcome! I am an astrophysicist exploring the evolution of massive stars and compact binaries.
        Currently, my research focuses on supernovae, black hole formation, and gravitational-wave populations.

        In this website, you can find:
        - **Research** — A summary of my research activities
        - **Papers** — Publications and related metrics
        - **Software** — Repositories of codes I’ve developed
        - **Talks** — Invited and contributed talks

  - block: markdown
    content:
      title: ""
      text: |
        <div style="display:flex;flex-wrap:wrap;gap:12px;margin-top:12px;">
          <a href="/research/"     style="padding:10px 16px;border-radius:10px;background:#0ea5e9;color:white;text-decoration:none;">Research</a>
          <a href="/publication/"  style="padding:10px 16px;border-radius:10px;background:#10b981;color:white;text-decoration:none;">Papers</a>
          <a href="/software/"     style="padding:10px 16px;border-radius:10px;background:#6366f1;color:white;text-decoration:none;">Software</a>
          <a href="/talk/"         style="padding:10px 16px;border-radius:10px;background:#f59e0b;color:white;text-decoration:none;">Talks</a>
          <!-- opzionale -->
          <!-- <a href="/teaching/"    style="padding:10px 16px;border-radius:10px;background:#ef4444;color:white;text-decoration:none;">Teaching</a> -->
        </div>

---
