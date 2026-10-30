# Diwanshu Singhal — Personal Portfolio

A responsive portfolio website customized for Diwanshu Singhal and aligned with the Internal Assessment Project brief.

## Profile
- Name: Diwanshu Singhal
- GitHub: https://github.com/diwanshu27
- View My Profile:https://generate-portfolio-from-repository.vercel.app/
- Education and specialization: confirm the exact institution and course details with Diwanshu before final submission.

## Technologies
- HTML, CSS, JavaScript
- Python (featured practicals)
- Git and GitHub
- Vercel serverless function for the chatbot
- Groq API through a server-side endpoint

## Assessment Features
- Home, About Me, Skills, Projects, Contact, and AI Chatbot sections
- Five project cards required by the assessment
- Search projects by title, description, or technology
- Light/dark mode toggle
- Responsive layout
- Portfolio chatbot with error handling; API key is read server-side from an environment variable
- Existing city-based weather lookup retained

## Projects

1. **Python Programs Collection** — Python practice programs and fundamentals.
   - https://github.com/diwanshu27/diwanshu-python-25bcon1339
   - https://github.com/diwanshu27/Diwanshu-python-Directory-25bcon1339
2. **Messy Python Code Improvement** — AI-assisted code improvement practical. The repository link below is the Python practice repository and should be confirmed as the exact practical repo.
   - https://github.com/diwanshu27/Diwanshu-python-Directory-25bcon1339
3. **Bug Fixing Using Cursor AI** — Python debugging practical.
   - https://github.com/diwanshu27/Buggy-python-script-25bcon1339
4. **Interactive Quiz Application** — Interactive quiz practical.
   - https://github.com/diwanshu27/Quiz_25bcon1339
5. **Book Reading List Application** — Reading-list practical.
   - https://github.com/diwanshu27/reading-list-25bcon1339
   - Live deployment URL: not confirmed; add it when available.

## Run Locally

The static website can be opened through a local web server. To test the chatbot, use Vercel's development environment so `/api/chat` is available.

1. Install Node.js and the Vercel CLI.
2. Run `vercel dev` from the project directory.
3. Add `GROQ_API_KEY` to your local Vercel environment. Do not put the secret in frontend files or commit it to GitHub.
4. Open the local URL provided by Vercel.

## Deploy to Vercel

1. Push the portfolio files to a GitHub repository owned by Diwanshu.
2. Import that repository into Vercel.
3. In Vercel Project Settings → Environment Variables, add `GROQ_API_KEY` with a valid Groq API key.
4. Optionally set `GROQ_MODEL` if a different supported model is required.
5. Redeploy and test search, theme toggle, chatbot, project links, images, and mobile layout.

## Important Before Submission

- Confirm the exact education/institution details with Diwanshu.
- Confirm whether `Diwanshu-python-Directory-25bcon1339` is the correct repository for the separate “Messy Python Code Improvement” practical.
- Add the live Reading List URL if Diwanshu has deployed it.
- Add the final portfolio's public URL after deployment.
- Set `GROQ_API_KEY` in Vercel; the chatbot will return a configuration error until this is done.
