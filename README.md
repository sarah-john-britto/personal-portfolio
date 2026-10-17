My personal portfolio with a 3D starfield background, scroll animations, and a working contact form.

Features
3D WebGL starfield with mouse parallax (Three.js)
Scroll-triggered animations (GSAP)
Typing animation, custom cursor, and 3D card tilt
Contact form powered by a Vercel serverless function and the Resend API
Responsive design with SEO and social preview tags
Built With
HTML, CSS, JavaScript
Three.js and GSAP
Node.js (Vercel serverless function in api/submit.js)
Resend API for emails
Run Locally
bash
cd your-repo-name
echo "RESEND_API_KEY=your_key" > .env
vercel dev

Open http://localhost:3000
