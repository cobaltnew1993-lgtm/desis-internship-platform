# DESIS Internship Platform

A comprehensive web-based internship management system for the DESIS Summer Internship Program.

## Features

- **Multi-Role Dashboards**: Tailored experiences for Interns, Mentors, HR Admins, and Jury members
- **Smart Onboarding**: 4-step onboarding flow with skills assessment and project matching
- **Real-Time Analytics**: Program health monitoring and performance tracking
- **Structured Feedback**: Weekly feedback loops between mentors and interns
- **Standardized Evaluation**: Consistent jury evaluation with objective scoring

## Tech Stack

- **Frontend**: HTML5, CSS3 (Vanilla), JavaScript (ES6+)
- **Fonts**: Inter (Google Fonts)
- **Design System**: Custom CSS variables and component library
- **Hosting**: Vercel

## Project Structure

```
prototype/
├── index.html              # Landing page
├── styles/
│   └── design-system.css   # Complete design system
├── pages/
│   ├── login.html          # Role-based login
│   ├── onboarding-*.html   # 4-step onboarding flow
│   ├── intern-dashboard.html
│   ├── mentor-dashboard.html
│   ├── hr-dashboard.html
│   └── evaluation-form.html
├── components/             # Reusable UI components
└── assets/                 # Images and media
```

## Getting Started

### Local Development

1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/desis-internship-platform.git
cd desis-internship-platform
```

2. Start a local server
```bash
python3 -m http.server 8000
```

3. Open your browser to `http://localhost:8000`

### Deployment

This project is deployed on Vercel and automatically rebuilds on every push to the main branch.

## Design System

The platform uses a comprehensive design system with:

- **Color Palette**: Professional slate grays with indigo accent
- **Typography**: Inter font family with 9-point type scale
- **Components**: Buttons, cards, forms, badges, progress indicators
- **Spacing**: 8-point grid system
- **Animations**: Subtle transitions and hover effects

See `styles/design-system.css` for full specifications.

## User Flows

### Intern Journey
1. Login → Onboarding (Profile → Skills → Preferences → Schedule)
2. Project Assignment → Weekly Work
3. Feedback Review → Learning Resources
4. Final Presentation → Evaluation

### Mentor Journey
1. Login → Dashboard
2. View Mentees → Submit Feedback
3. Monitor Progress → Provide Resources
4. Final Evaluation Support

### HR Admin Journey
1. Login → Program Overview
2. Match Interns to Projects
3. Monitor Program Health
4. Intervene on At-Risk Interns
5. Generate Reports

### Jury Journey
1. Login → Evaluation Form
2. Review Intern Portfolio
3. Score Performance
4. Submit Feedback

## Contributing

This is a prototype for the DESIS Summer Internship Program. For suggestions or improvements, please contact the development team.

## License

© 2026 DESIS Summer Internship Program. All rights reserved.

## Contact

For questions or support, contact: devis@example.com
