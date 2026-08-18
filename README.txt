AccessMed California — official website bundle
==============================================

FILES IN THIS FOLDER

  index.html    → Home page (visitors land here first)
  mission.html  → Our mission — why we exist, what healthcare workers see,
                  what we're trying to change
  tools.html    → Renewal Check, Deadline Tracker, FAQ, Glossary, Myths &
                  Facts, and verified contact info for all 58 CA counties
  videos.html   → Official BenefitsCal/DHCS video tutorials, embedded with
                  full attribution — organized in 3 tabs (Renewals /
                  Getting Started / Managing Account)
  blog.html     → 10 fact-checked articles on Medi-Cal renewal, eligibility,
                  lost coverage, family situations, and 2026 policy changes
  impact.html   → Organization statistics + anonymous feedback survey
  help.html     → How to help us spread awareness — share, volunteer,
                  translate, or introduce us to community organizations
  favicon.svg   → The bridge logo (shows in browser tabs)

  NETLIFY-DEPLOY-GUIDE.html  → Open this in a browser for step-by-step
                                deploy instructions
  README.txt   → This file


TO DEPLOY

1. Go to https://app.netlify.com/drop (or sign in to Netlify).
2. Drag this entire folder onto the drop zone.
3. You get a live URL in ~30 seconds.
4. Point your domain (accessmedcalifornia.org) at Netlify.
   Full DNS instructions are in the deploy guide.


FORMS

Three forms are wired to Netlify Forms:
- Renewal reminders (on the home page)
- Feedback survey (on the impact page)
- Get involved (on the how-to-help page)

Once deployed to Netlify, submissions appear automatically in your
Netlify dashboard → Forms. You'll get email notifications for each one.
For local previews (opening the HTML directly), submissions show a
success message but don't send anywhere.

If you're NOT deploying to Netlify, you'll need to swap the form
handlers for another service like Formspree.


VERIFIED INFORMATION

All hotline numbers are pulled from official DHCS sources:
- Medi-Cal Helpline: (800) 541-5555
- Medi-Cal Fraud Hotline: (800) 822-6222
- TTY: 711 (California Relay Service)
- Official portal: BenefitsCal.com

All 58 California county phone numbers on the Tools page are pulled
from the official DHCS County Contact List:
https://www.dhcs.ca.gov/wp-content/uploads/2025/10/County-Contact-List.pdf


UPDATING LATER

Edit the HTML files in any text editor (Notepad, TextEdit, VS Code).
Drag the folder back onto Netlify. Live in 30 seconds.

Nothing here needs a build step, dependencies, or a server. Plain HTML,
CSS, and JavaScript. Any developer (or any AI assistant) can read
and modify it. You own all of it.


LANGUAGES

The site supports 9 languages, selectable from the top-right menu:
English, Spanish, Chinese (Simplified), Hindi, Punjabi, Vietnamese,
Tagalog, Korean, and Arabic. Arabic automatically switches the layout
to right-to-left.

Before public launch, have native speakers review the non-English
translations, especially for the AccessBot chat responses.


CONTACT

accessmedcalifornia@gmail.com
