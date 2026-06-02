# SimCoder Pro - Medical Coding Career Simulator

A highly realistic web and mobile application that simulates a real entry-level to advanced medical coding job environment.

## Overview

SimCoder Pro is **NOT** a quiz app, flashcard app, or study guide. It is a comprehensive employment simulator designed to provide hands-on coding experience that mirrors actual outpatient, physician, and professional-fee coding environments.

### Core Objective

Users learn by performing realistic coding work. The application presents medical records, provider documentation, operative reports, progress notes, and other coding-related documents where users must:

- Read documentation
- Identify diagnoses and procedures
- Assign ICD-10-CM codes
- Assign CPT codes
- Assign HCPCS Level II codes when applicable
- Select modifiers
- Determine sequencing
- Correct claim errors
- Pass coding audits

## Features

### Career Progression System
- **10 Career Levels**: From Coding Trainee to Master Coder
- **Specialty Assignments**: 15+ medical specialties
- **Performance-Based Advancement**: Based on accuracy, productivity, and audit performance

### Virtual Work Environment
- Professional coding dashboard
- Daily chart queue
- Productivity metrics and performance tracking
- Realistic workday simulation

### Medical Documentation
- 5,000+ unique fictional patient charts
- Realistic medical documentation formats
- Multiple specialties and complexity levels

### Coding Features
- ICD-10-CM code lookup and assignment
- CPT code assignment
- HCPCS Level II code support
- Modifier application
- Code sequencing
- Educational feedback after each chart

### Code Reference Lookup
- **Complete ICD-10-CM Manual Integration**: Every code with full descriptions, guidelines, includes/excludes notes, and clinical examples
- **CPT Manual Reference**: Every code with descriptor, typical unit value, work value, and usage guidelines
- **HCPCS Level II Manual**: Comprehensive drug, device, supply, and service codes with usage rules
- **Real-time Code Validation**: Cross-reference codes as you assign them
- **Guidelines and Edits**: NCCI edits, bundling rules, and coverage requirements
- **Clinical Decision Support**: Suggested codes based on documentation

### Comprehensive Training Library
- **ICD-10-CM Training Module**: 50+ detailed lessons covering all 21 chapters
- **CPT Training Module**: Comprehensive E/M, surgical, and procedural coding education
- **HCPCS Level II Training**: Drug codes, modifiers, supplies, and services
- **Modifier Training**: Detailed explanations of all critical modifiers with use cases
- **Coding Guidelines**: Official guideline references with examples
- **Specialty-Specific Training**: Orthopedics, cardiology, gastroenterology, etc.
- **Common Error Prevention**: Real audit findings and how to avoid them
- **Compliance Training**: HIPAA, billing compliance, and audit readiness

### Quality Assurance
- Realistic audit system
- Claim denial simulator
- QA review process
- Performance reviews and recommendations

### Learning Resources
- Searchable reference library
- CodeCoach AI mentor system
- Compliance education

## Quick Start

### Prerequisites
- Node.js 18+
- PostgreSQL 15+
- Docker & Docker Compose (optional)

### Development Setup

```bash
# Clone the repository
git clone https://github.com/yourusername/SimCoder-Pro.git
cd SimCoder-Pro

# Using Docker (recommended)
docker-compose up -d

# Or manual setup
cd backend && npm install
cd ../frontend && npm install

# Start development servers
npm run dev
```

Access the application at `http://localhost:3000`

## Project Structure

```
SimCoder-Pro/
├── frontend/               # React web application
├── backend/                # Node.js API server
├── database/               # Schemas and migrations
├── content/                # Medical charts and scenarios
├── training/               # Training library content
├── code-reference/         # ICD-10, CPT, HCPCS manuals
├── docs/                   # Documentation
└── docker-compose.yml      # Container orchestration
```

## Technology Stack

- **Frontend**: React 18, TypeScript, Tailwind CSS, Redux
- **Backend**: Node.js, Express, PostgreSQL, Redis
- **Database**: PostgreSQL 15
- **Cache**: Redis
- **Auth**: JWT
- **Deployment**: Docker, AWS/GCP ready

## Documentation

- [Architecture Guide](docs/ARCHITECTURE.md)
- [API Reference](docs/API.md)
- [Database Schema](docs/DATABASE.md)
- [Feature Specifications](docs/FEATURES.md)
- [Content Guidelines](docs/CONTENT.md)
- [Setup Instructions](docs/SETUP.md)
- [Code Reference System](docs/CODE_REFERENCE.md)
- [Training Library Guide](docs/TRAINING_LIBRARY.md)

## Development Roadmap

### Phase 1: Core Infrastructure
- [x] Project structure
- [x] Database setup
- [x] Code Reference System design
- [x] Training Library architecture
- [ ] Backend API foundation
- [ ] Authentication system

### Phase 2: Core Application
- [ ] Dashboard UI
- [ ] Chart queue system
- [ ] Coding workspace
- [ ] Code lookup integration
- [ ] Training Library UI

### Phase 3: Content Generation
- [ ] Chart generation engine
- [ ] Specialty-specific templates
- [ ] Audit scenarios
- [ ] Denial scenarios
- [ ] Training content population

### Phase 4: Advanced Features
- [ ] CodeCoach AI system
- [ ] QA module
- [ ] Performance tracking
- [ ] Career progression

### Phase 5: Polish & Launch
- [ ] Mobile optimization
- [ ] Testing and QA
- [ ] Documentation
- [ ] Beta launch

## License

MIT License - See LICENSE file for details

## Contributing

Contributions are welcome! Please see CONTRIBUTING.md for guidelines.
