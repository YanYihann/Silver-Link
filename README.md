<div align="center">

# Silver Link

Accessible single-page service concept for helping older adults use everyday digital services with confidence.

[![HTML](https://img.shields.io/badge/HTML5-single%20file-E34F26?logo=html5&logoColor=white)](index.html)
[![Status](https://img.shields.io/badge/status-frontend%20prototype-orange)](#project-status)

</div>

## Overview

Silver Link is a responsive landing-page prototype for a family-oriented digital assistance service. The page presents support options, a simple needs matcher, service steps, testimonials, pricing, and a booking form in a calm, senior-friendly visual system.

## Experience highlights

- Large, readable typography and high-contrast controls
- Service categories covering medical access, daily convenience, and family connection
- Interactive “How can we help today?” matcher
- Three-step service explanation: book online, home visit, peace of mind
- Pricing cards and a booking call to action
- Responsive navigation and layout

## Run locally

Because the prototype is self-contained, you can open `index.html` directly or serve it locally:

```bash
git clone https://github.com/YanYihann/Silver-Link.git
cd Silver-Link
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Repository structure

```text
.
├── index.html                  # Primary interactive landing page
├── silver_link_one_page.html   # Alternate one-page version
└── README.md
```

## Project status

This repository is a frontend concept. Booking actions, identity verification, payments, scheduling, and service delivery are not connected to a backend. Testimonials and service claims should be treated as prototype copy until validated for a real organization.

## Accessibility notes

The design aims for readable type and clear controls. Before production use, complete keyboard-only, screen-reader, zoom, color-contrast, reduced-motion, and form-validation testing with representative older users.

## License

No license file is currently included.


