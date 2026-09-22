# FishTrace

<p align="center">
  <strong>Trusted traceability for a smarter, safer, and more sustainable fish supply chain.</strong>
  <br />
  From the fishing boat to the consumer, FishTrace connects people, data, and technology in one transparent ecosystem.
</p>

<p align="center">
  <a href="#project-ecosystem">Explore the ecosystem</a> Â·
  <a href="#getting-started">Get started</a> Â·
  <a href="#documentation">Read the documentation</a>
</p>

---

## About FishTrace

FishTrace is a modular digital platform designed to improve transparency, quality, and accountability across Sri Lanka's fish supply chain. It brings together traceability workflows, mobile access, IoT telemetry, AI-assisted spoilage detection, and blockchain-backed verification.

The platform helps stakeholders record and follow a product's journey through:

- Fisher, boat, trip, catch, and batch management
- Secure QR-based product traceability
- Transport, processing, retail, and compliance workflows
- Real-time and historical IoT sensor data
- AI-assisted fish quality and spoilage analysis
- Privacy-aware consumer trace views

## Project ecosystem

This repository is the central project hub. The implementation is maintained across focused repositories so each team can work independently without changing the others.

| Repository | Purpose | Link |
| --- | --- | --- |
| **FishTrace Platform** | Core web platform, API, administration, traceability workflows, and consumer portal | [Open repository](https://github.com/gayashan939/FishTrace) |
| **FishTrace Mobile** | Mobile application for field teams, fishers, transporters, and inspectors | [Open repository](https://github.com/SLBDEVELOPERS/fishtrace_app) |
| **FishTrace AI** | AI-assisted fish quality assessment and spoilage detection services | [Open repository](https://github.com/Chathura1109/fish-spoilage-ai) |
| **FishTrace IoT** | Sensor integration, telemetry simulation, and device communication | [Open repository](https://github.com/SLBDEVELOPERS/FishTrace_IoT) |
| **FishTrace Blockchain** | Distributed verification and tamper-evident supply-chain records | [Open repository](https://github.com/Chathura1109/FishTrace-Blockchain) |

> **Link setup:** These links point to the official SLBDEVELOPERS repositories. Share this central README with lecturers, reviewers, collaborators, or clients as the single project link.

## How it works

```text
Fishing & Catch Data â†’ Processing & Transport â†’ Retail & Compliance â†’ Consumer QR Trace
         â”‚                       â”‚                       â”‚                    â”‚
         â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€ IoT telemetry + AI quality insights â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
                              Blockchain verification
```

## Core technology

| Layer | Technologies |
| --- | --- |
| Web platform | Laravel, PHP, MySQL/MariaDB, Vite |
| Mobile | Flutter / Dart |
| Intelligence | Python-based AI services and spoilage analysis |
| Connected devices | ESP32-style telemetry and sensor integrations |
| Trust layer | Blockchain-backed verification |
| Delivery | REST API, QR labels, role-based dashboards |

## Getting started

Clone the repository that matches the area you want to explore, then follow its own setup instructions. For the main platform:

```bash
git clone https://github.com/SLBDEVELOPERS/FishTrace.git
cd FishTrace
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate:fresh --seed
npm install
npm run build
php artisan serve
```

Development demo credentials and environment requirements are documented in the [platform README](FishTrace/README.md).

## Documentation

- [English user manual](FishTrace/docs/user-manual-en.md)
- [à·ƒà·’à¶‚à·„à¶½ user manual](FishTrace/docs/user-manual-si.md)
- [API contract](FishTrace/docs/api-contract.md)
- [Implementation checklist](FishTrace/docs/implementation-checklist.md)
- [Shared-hosting deployment guide](FishTrace/docs/shared-hosting-deployment.md)

## Project status

FishTrace is an actively developed academic and applied technology project. Individual repositories may evolve at different speeds; refer to each repository's README and documentation for the most current implementation status.

## Contributing

Contributions, testing feedback, documentation improvements, and ideas are welcome. Please open an issue in the relevant repository before starting a large change so the team can coordinate the work.

## License

Add the project's approved license here before publishing the repositories publicly.

---

<p align="center">
  <strong>FishTrace</strong><br />
  Building trust from ocean to table.
</p>

