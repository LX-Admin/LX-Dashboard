CODEX 2.0: Training Performance Dashboard

A sleek, high-performance analytical portal designed to aggregate, display, and compare embedded Looker Studio datasets. Built with a unified "Athena" aesthetic (Deep Emerald and Gold), this dashboard provides an executive-level viewing experience for training and performance metrics.

🌟 Key Features

Zero-Build Architecture: Runs entirely on the client side using a single HTML file with standalone React and Tailwind CSS via CDN. No complex Node.js build pipelines required—just open and deploy.

Split-View Comparison: A custom dual-pane viewing mode that dynamically hides the sidebar and allows analysts to compare two different Looker Studio datasets side-by-side in real-time.

Bespoke UI/UX: Features a collapsible sidebar for maximum screen real-estate, smooth transitions, glassmorphism effects, and custom scrollbars tailored to the brand aesthetic.

Dynamic Routing: Seamlessly switches between embedded iframes without reloading the page, maintaining a fast, app-like feel.

📊 Integrated Modules

The dashboard is currently configured to track the lifecycle of Executive Assistants (EAs):

EA Journey (High-level overview)

LX Performance (Learning Experience metrics)

Pre-Training (Initial assessments and onboarding)

Training (Core curriculum performance)

Pre-Matching (Graduation and staging)

Post-Match (Client pairing success)

Churn Data (Retention and attrition analytics)

🚀 How to Use / Fork

Because this project uses a standalone Babel compiler in the browser, deployment is instantaneous.

Fork or Clone this repository.

Host the HTML: Serve the training_dashboard.html file on GitHub Pages, standard web hosting, or even open it locally in your browser.

Configure Your Data: To point the dashboard to your own Looker Studio reports, open training_dashboard.html and update the LOOKER_STUDIO_URLS dictionary at the top of the React script:

co
