# Entrepreneurship History Timeline

**Course**: ENTR 20263 Entrepreneurship & Innovation (TCU Neeley School of Business)

**Audience**: Required for all TCU business majors

## Overview

This web‑based timeline tool was developed for ENTR 20263: Entrepreneurship & Innovation. The primary learning objective is to introduce students to modern, AI‑assisted software workflows, not to delve into advanced programming techniques. Through guided interaction with the codebase—and by leveraging generative AI—students will:

- **Explore a no‑code/low‑code mindset**: Understand how today’s platforms can accelerate development.
- **Appreciate AI integration**: See how AI agents can modify, refactor, and extend real software.
- **Collaborate on code**: Propose and implement feature requests (e.g., new timeline views, data sources).

Ultimately, the goal is to foster **software fluency** and inspire creative applications of AI in entrepreneurship.

---

## Features

- **Interactive Timeline View**  Displays historical or future events with smooth animations and a scroll‑driven background effect.

- **Supabase Authentication & Authorization**

  - *Magic link* sign‑in for students.
  - Approval workflow: new users request access, admins review pending requests.
  - Role check to display an **Approvals** tab for administrators.

- **Event Contribution**

  - Signed‑in and approved students can add new timeline events.
  - Data is persisted in a Supabase table (`events`).

- **AI‑Friendly Codebase**  Encourages students to use generative AI tools (e.g., ChatGPT) to propose, test, and implement changes.

---

## Usage in ENTR 20263

1. **Sign in** using your university email to receive a magic link.
2. **Wait for admin approval**: Your access request is automatically routed to the course instructor (admin).
3. **Add events**: Once approved, the "Add Event" form appears on the Home tab.
4. **Experiment with AI**: Students are encouraged to use AI tools (e.g., GitHub Copilot, ChatGPT) to:
   - Refactor CSS for theme customization
   - Add new event filters or search capabilities
   - Integrate alternative data sources (CSV upload, external APIs)
   - Implement additional authentication flows

---

## Contributing

- Fork the repository and create feature branches.
- Use AI to draft pull requests—include prompts, AI‑generated code, and your own edits.
- Submit a pull request with a clear description of your changes and the AI prompts you used.

---

## Educational Outcomes

By the end of this project, students will:

- Recognize the power and limitations of AI in code generation.
- Understand how to wire up a database‑backed SPA with minimal boilerplate.
- Appreciate the role of authentication and role‑based access in web apps.
- Develop confidence in proposing software enhancements, even without deep coding expertise.

---

## Rebuild it Yourself

If you want to rebuild this project from scratch, you will need to carefully set up a database schema and configure permissions so that users can only modify their own data, just as we have done here. The only tools required are free:

- **GitHub** (for version control and hosting static web content)
- **Supabase** (for authentication, database storage, and real-time updates)

Beyond those services, no additional paid tools are necessary.

---

*This project is maintained by Eric Arseneau at the Neeley School of Business - Texas Christian University.*
