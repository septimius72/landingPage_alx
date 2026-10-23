AI-Powered Technical Recruiter Portfolio 🚀

A high-performance, single-file personal branding and portfolio landing page designed for a Senior/Staff Technical Recruiter and Talent Acquisition Leader. Built with modern web design trends in mind, it features an interactive bento-grid layout, kinetic canvas animations, and functional OSINT tooling.

✨ Key Features

Hybrid Interactive Background: A pure CSS topographic elevation map layered underneath a zero-dependency HTML5 <canvas> particle network that reacts to cursor movement.

Integrated OSINT Query Generator: A functional UI widget that generates production-ready Boolean search strings for recruiting specific tech stacks, complete with a "Copy to Clipboard" toast notification.

Interactive CLI Terminal: A built-in terminal emulator that allows visitors to type commands (like skills, boolean-sample, and contact) to explore the profile in a developer-native format.

Modern Bento Grid UI: Clean, glassmorphic layout using Tailwind CSS with mouse-tracking spotlight hover effects (inspired by Vercel/Linear).

Seamless Light/Dark Mode: Dynamic theme toggling that automatically updates colors, typography, and canvas particle behaviors without page reloads.

Floating Dock Navigation: A sticky macOS-inspired bottom dock for quick access to key social links and contact points.

Zero Build Step: 100% self-contained in a single HTML file with CDN-linked dependencies.

🛠 Tech Stack

Markup: HTML5

Styling: Tailwind CSS (via CDN)

Scripting: Vanilla JavaScript (DOM manipulation, Canvas API, Intersection Observers)

Icons: Lucide Icons (via CDN)

Typography: Google Fonts (Plus Jakarta Sans, JetBrains Mono)

🚀 Quick Start / Installation

Because this project is built as a single, self-contained HTML file without a complex build pipeline, running it locally is instantaneous.


Add required assets:
Ensure the following two files are placed in the same directory as index.html:

Sashik_AI_GEN_2.jpg (Profile Photo)

alex.becz.2026.pdf (Downloadable Resume)

Run it:
Simply double-click index.html to open it in any modern web browser. (Alternatively, use a tool like VS Code Live Server for hot reloading).

🎨 Customization

To adapt this template for your own use, open index.html and look for the following sections:

Terminal Logic: Search for const cmdResponses in the <script> tag to change what the terminal outputs when specific commands are typed.

OSINT Strings: Search for const sourcingStrings to update the boolean logic generator.

Marquee Skills: Search for const skills1 and const skills2 to update the infinitely scrolling skill tags.

