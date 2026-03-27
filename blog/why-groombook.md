# Why GroomBook: Built for Groomers, Not Corporations

**March 2026**

---

## The Problem

You're a grooming salon owner or solo groomer. You've looked at scheduling software before. Here's what you've probably experienced:

- **MoeGo**: $50-150/month. Works, but you're paying every month forever, and if they change pricing or shut down, your business goes with it.
- **Gingr or PetExec**: Enterprise software, $200+/month, designed for franchise chains. Way more than you need.
- **Square Appointments or Calendly**: Generic scheduling tools that don't understand grooming. No breed-aware timing. No pet history. No waitlist system. You're constantly working around the tool instead of working with it.
- **Paper and spreadsheets**: Reliable, but you lose time to manual double-booking checks, no-show tracking, and coordinating across your team.

**Here's the core problem:** Most grooming software is either too expensive, doesn't understand your workflow, or locks you into paying forever. And if the company gets bought or shuts down, you're out of luck.

---

## What You Actually Need

After talking to dozens of groomers, a few needs keep coming up:

1. **Appointment scheduling that understands grooming**
   - A 15-minute Pomeranian bath-and-brush is different from a 45-minute Doodle shave-down
   - Generic tools don't account for breed, coat type, or complexity
   - You end up double-booking or rushing

2. **Client and pet history in one place**
   - Notes about each pet: "this dog gets matted" or "anxious around water"
   - Service history: what was done last time, how long it took
   - Paper files get lost; no system means context lives in your head

3. **Online booking so clients can help themselves**
   - Stop fielding "what times do you have?" calls
   - Let clients book, confirm, or cancel 24/7 without calling you
   - Reduce no-shows with automated confirmations

4. **Automatic waitlist filling**
   - When someone cancels, automatically fill that slot from your waitlist
   - No more manually checking the list and calling people back

5. **Your data stays yours**
   - This is the big one. You've seen salon software get acquired, change pricing, or shut down.
   - You want to own your client list, appointment history, and business data.

---

## What GroomBook Gives You

GroomBook is **open-source, self-hosted pet grooming software** built specifically to solve these problems.

### What you get out of the box:

- **Smart appointment scheduling** — calendar view, groomer assignment, breed-aware service timing
- **Client search & profiles** — quickly find clients and their complete pet history
- **Pet history with appointment notes** — everything about every client and their pets, including detailed notes from each visit
- **Online booking portal** — clients book 24/7, see real availability
- **Automated waitlist** — automatically fill cancellations from your queue
- **Role-based staff accounts** — front desk sees bookings; only you see financials
- **Calendar feed sync** — push appointments to Google Calendar or Apple Calendar automatically

### And because it's open source:

- **You own your data** — runs on your server (or a $20/month VPS). Your client list never becomes someone's asset.
- **No vendor lock-in** — if you want to customize it, hire any developer. If you want to move hosts, you just clone the repo.
- **No monthly fees** — pay nothing to use the software itself. (Optional: managed hosting if you want someone else to handle backups and updates.)
- **Community-driven** — anyone can contribute, audit the code, or suggest features.

---

## How Much?

**Free.**

MIT license. Download it, run it yourself, no subscription.

You can have it running in 5 minutes:

```bash
git clone https://github.com/groombook/groombook
cd groombook
docker compose up --build
```

That's it. You have a fully functional grooming management system running locally.

---

## Who This Is For

**GroomBook is built for:**

- Solo groomers tired of paper and spreadsheets
- Small salons with 2-5 groomers who can't justify $200+/month for enterprise software
- Grooming business owners who value owning their business data
- Groomers who want a tool built specifically for grooming workflows

**GroomBook is not (yet) for:**

- Enterprise salon chains with 20+ locations (that's not our focus)
- Businesses that want 24/7 managed SaaS support with legal contracts (look at Phorest or Vagaro instead)

---

## Why Open Source Matters

The grooming industry has a real problem: **software companies own the data**.

You pay $100/month for scheduling software. You build your client list, your service history, your business on their platform. Then:

- The company gets acquired. Pricing triples.
- They pivot to focus on salons instead of groomers. Features you depend on get removed.
- The platform shuts down. You have 30 days to export what you can.

This happened to salon software owners. It's happening right now in the dog training world.

**Open source prevents this.** If GroomBook ever stops being useful or disappears, the code is still yours. You can hire any developer to maintain it or move it to a new host. Your data was never anyone else's leverage.

That's why we're building this as open source.

---

## Getting Started

1. **Try the demo** — play with a fully functional test version: [demo.groombook.io](https://demo.groombook.io)
2. **Self-host** — run it yourself with Docker Compose (no credit card required)
3. **Read the docs** — detailed setup and feature guides at [groombook.github.io/getting-started](https://groombook.github.io/getting-started)
4. **Join the community** — questions, feedback, and feature requests on [GitHub](https://github.com/groombook/groombook)

---

## What's Next?

GroomBook v1 covers the essentials. We're actively building:

- Automated SMS/email reminders and confirmations
- Mobile app for iOS/Android
- POS & invoicing integration
- Offline-capable mobile experience for mobile groomers
- Business analytics and reporting
- Multi-language support
- Groomer commission tracking
- QuickBooks and accounting software integrations

You can track the roadmap [on GitHub](https://github.com/orgs/groombook/projects/1).

---

## One More Thing

If you've been making do with a whiteboard, paper calendar, or expensive software you resent paying for, you have a better option now.

You deserve tools built for your work, not tools that force you to adapt to software. You deserve to own your business data. And you shouldn't have to pay $100+/month for it.

That's what GroomBook is here to do.

**[Try the demo →](https://demo.groombook.io)**

---

*Questions? Feedback? Found a bug? [Open an issue on GitHub](https://github.com/groombook/groombook/issues)*

*Want to contribute? [See the contributing guide](https://github.com/groombook/groombook/blob/main/CONTRIBUTING.md)*
