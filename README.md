# 🐟 FishTrace

<p align="center">
  <img src="https://img.shields.io/badge/FishTrace-Smart%20Fish%20Supply%20Chain-0A7C86?style=for-the-badge" alt="FishTrace">
  <img src="https://img.shields.io/badge/Platform-Laravel%20%7C%20Flutter%20%7C%20Python-111827?style=for-the-badge" alt="Platform">
  <img src="https://img.shields.io/badge/IoT-ESP32-111827?style=for-the-badge" alt="IoT">
  <img src="https://img.shields.io/badge/AI-Quality%20Detection-111827?style=for-the-badge" alt="AI">
</p>

<p align="center">
  <strong>Trusted traceability for a smarter, safer, and more sustainable fish supply chain.</strong>
</p>

<p align="center">
  From the fishing boat to the consumer, <strong>FishTrace</strong> connects people, data, devices, intelligence, and verification into one transparent digital ecosystem.
</p>

<p align="center">
  <a href="#-project-ecosystem">Ecosystem</a> •
  <a href="#-how-fishtrace-works">How It Works</a> •
  <a href="#-core-capabilities">Capabilities</a> •
  <a href="#-technology-stack">Technology</a> •
  <a href="#-getting-started">Getting Started</a> •
  <a href="#-documentation">Documentation</a>
</p>

---

## 🌊 About FishTrace

**FishTrace** is a modular digital traceability platform designed to improve **transparency, quality, accountability, and consumer trust** across Sri Lanka's fish supply chain.

The platform creates a connected journey from **catch to consumer**, allowing supply-chain stakeholders to capture, verify, monitor, and access meaningful product information at every stage.

FishTrace combines:

* 🎣 Fisher, boat, trip, catch, and batch management
* 📱 Mobile-first field operations
* 🔗 Secure QR-based product traceability
* 🚚 Transport and cold-chain monitoring
* 🏭 Processing and retail workflows
* 🌡️ Real-time and historical IoT telemetry
* 🤖 AI-assisted fish quality and spoilage analysis
* ⛓️ Blockchain-backed verification
* 🛡️ Role-based access and privacy-aware consumer views
* 📊 Centralized dashboards and operational insights

> **One supply chain. One connected ecosystem. Complete traceability.**

---

# 🧩 Project Ecosystem

FishTrace is designed as a **multi-repository ecosystem**, allowing each technical component to evolve independently while remaining connected through defined interfaces and workflows.

| Component                   | Purpose                                                                                              | Repository                                                              |
| --------------------------- | ---------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| 🖥️ **FishTrace Platform**  | Core web platform, REST API, administration, traceability workflows, dashboards, and consumer portal | [Open Repository](https://github.com/gayashan939/FishTrace)             |
| 📱 **FishTrace Mobile**     | Mobile application for field teams, fishers, transporters, and inspectors                            | [Open Repository](https://github.com/SLBDEVELOPERS/fishtrace_app)       |
| 🤖 **FishTrace AI**         | AI-assisted fish quality assessment and spoilage detection                                           | [Open Repository](https://github.com/Chathura1109/fish-spoilage-ai)     |
| 🌡️ **FishTrace IoT**       | Sensor integration, telemetry simulation, and connected-device communication                         | [Open Repository](https://github.com/SLBDEVELOPERS/FishTrace_IoT)       |
| ⛓️ **FishTrace Blockchain** | Distributed verification and tamper-evident supply-chain records                                     | [Open Repository](https://github.com/Chathura1109/FishTrace-Blockchain) |

### 🔗 One Project. Multiple Components.

Each repository focuses on a specific responsibility while contributing to the same FishTrace ecosystem.

This structure allows:

* Independent development
* Clear separation of responsibilities
* Easier testing and deployment
* Technology-specific development workflows
* Scalable future expansion

> **Recommended:** Use this repository as the **central project hub** when sharing FishTrace with lecturers, reviewers, collaborators, stakeholders, or clients.

---

# 🔄 How FishTrace Works

```text
┌──────────────────────┐
│   🎣 FISHING STAGE   │
│                      │
│ Fisher • Boat • Trip │
│ Catch • Batch        │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│  🧊 PROCESSING &     │
│     TRANSPORT        │
│                      │
│ Processing • Storage │
│ Cold Chain • IoT     │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│  🏪 RETAIL &         │
│     COMPLIANCE       │
│                      │
│ Quality • Inspection │
│ Verification        │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│    📱 CONSUMER       │
│                      │
│ Scan QR → Trace Fish │
│ Verify → Understand  │
└──────────────────────┘

        ▲          ▲
        │          │
   🌡️ IoT       🤖 AI
   Telemetry     Quality
        │          │
        └────┬─────┘
             │
             ▼
      ⛓️ Blockchain
       Verification
```

### The Traceability Journey

**1. Catch**

Fishers record information about the fishing trip, vessel, catch, species, quantity, and batch.

**2. Process**

Products move through processing and storage while important operational information is captured.

**3. Transport**

IoT-enabled telemetry can provide environmental information such as temperature and other sensor readings.

**4. Verify**

AI services can assist with fish-quality assessment while blockchain-backed records provide an additional verification layer.

**5. Retail**

Retail and compliance stakeholders can access relevant product and quality information.

**6. Consumer**

Consumers scan a **QR code** to access a privacy-aware traceability view and understand the journey of the product.

---

# ✨ Core Capabilities

## 🎣 Catch & Vessel Management

Manage the foundational data behind every fishing operation.

* Fisher profiles
* Boat registration
* Fishing trips
* Catch records
* Species information
* Catch quantities
* Batch creation
* Supply-chain ownership

---

## 📦 End-to-End Traceability

Follow a fish product through its complete supply-chain journey.

```text
Catch
  ↓
Batch
  ↓
Processing
  ↓
Storage
  ↓
Transport
  ↓
Retail
  ↓
Consumer
```

Every stage can contribute relevant information to the product's digital history.

---

## 🔎 QR-Based Consumer Traceability

Each traceable product or batch can be associated with a QR identifier.

Consumers can:

* Scan a QR code
* View product information
* Understand the supply-chain journey
* Access relevant quality information
* Verify available records

The consumer experience is designed to expose **useful information without unnecessarily exposing sensitive operational data**.

---

## 🌡️ IoT & Cold-Chain Monitoring

FishTrace connects physical-world conditions with digital supply-chain records.

Potential telemetry includes:

* Temperature
* Humidity
* Device status
* Timestamped sensor readings
* Transport conditions
* Historical telemetry

This creates a digital connection between **what happens to the product** and **what the system records**.

---

## 🤖 AI-Assisted Quality Analysis

FishTrace AI provides machine-learning capabilities for fish-quality and spoilage assessment.

The AI layer can support:

* Image-based fish assessment
* Quality classification
* Spoilage detection
* Confidence information
* Automated analysis workflows

> AI acts as an **assistive intelligence layer**, supporting human decision-making rather than replacing domain expertise.

---

## ⛓️ Blockchain Verification

Blockchain technology provides an additional trust layer for selected supply-chain records.

The goal is to create records that are:

* Tamper-evident
* Verifiable
* Traceable
* Distributed

Blockchain is used as a **verification layer**, while operational data remains managed by the appropriate platform components.

---

# 🏗️ System Architecture

```text
                         ┌─────────────────────┐
                         │      CONSUMER       │
                         │      QR SCANNER     │
                         └──────────┬──────────┘
                                    │
                                    ▼
┌─────────────────────────────────────────────────────────┐
│                  FISHTRACE PLATFORM                     │
│                                                         │
│  Web Dashboard • REST API • Admin • Traceability       │
│  Users • Batches • Processing • Retail • Compliance    │
└───────────────┬───────────────────┬─────────────────────┘
                │                   │
                ▼                   ▼
       ┌────────────────┐   ┌─────────────────┐
       │  FISHTRACE     │   │   FISHTRACE     │
       │    MOBILE      │   │       AI        │
       │                │   │                 │
       │ Field Teams    │   │ Quality         │
       │ Fishers        │   │ Spoilage        │
       │ Inspectors     │   │ Detection       │
       └────────────────┘   └─────────────────┘
                │                   │
                └─────────┬─────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │  FISHTRACE IoT │
                 │                 │
                 │ ESP32 / Sensors │
                 │ Telemetry       │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │   BLOCKCHAIN    │
                 │                 │
                 │ Verification &  │
                 │ Immutable Proof │
                 └─────────────────┘
```

---

# 🛠️ Technology Stack

| Layer                  | Technology                                             |
| ---------------------- | ------------------------------------------------------ |
| **Web Platform**       | Laravel • PHP • MySQL / MariaDB • Vite                 |
| **Mobile Application** | Flutter • Dart                                         |
| **AI & Intelligence**  | Python • Machine Learning • Computer Vision            |
| **IoT**                | ESP32 • Sensors • Telemetry                            |
| **Trust Layer**        | Blockchain-backed verification                         |
| **Communication**      | REST APIs                                              |
| **Traceability**       | QR Codes                                               |
| **Access Control**     | Role-based authorization                               |
| **Deployment**         | Web Server / Shared Hosting / Cloud-ready architecture |

---

# 🔐 Security & Trust

FishTrace is designed with security and controlled information sharing in mind.

Key principles include:

* Role-based access control
* Protected administrative workflows
* API-based communication
* Controlled consumer data exposure
* Traceability record verification
* Separation of platform responsibilities
* Privacy-aware consumer views

The architecture is intended to ensure that **the right stakeholder sees the right information at the right stage**.

---

# 📱 User Roles

FishTrace supports multiple actors across the supply chain.

```text
                 ┌───────────────┐
                 │     ADMIN     │
                 └───────┬───────┘
                         │
       ┌─────────────────┼──────────────────┐
       ▼                 ▼                  ▼
   🎣 Fisher        🏭 Processor        🚚 Transporter
       │                 │                  │
       └─────────────────┼──────────────────┘
                         ▼
                    🏪 Retailer
                         │
                         ▼
                    🔍 Inspector
                         │
                         ▼
                    👤 Consumer
```

Each role interacts with the system according to its operational responsibilities and permissions.

---

# 🚀 Getting Started

## Prerequisites

Before running the main platform, make sure you have:

* PHP
* Composer
* MySQL / MariaDB
* Node.js & npm
* Laravel-compatible web server
* Git

---

## Clone the Platform

```bash
git clone https://github.com/SLBDEVELOPERS/FishTrace.git

cd FishTrace
```

## Install Dependencies

```bash
composer install
```

## Configure Environment

```bash
cp .env.example .env

php artisan key:generate
```

Configure your database and application settings inside `.env`.

## Prepare the Database

```bash
php artisan migrate:fresh --seed
```

## Install Frontend Dependencies

```bash
npm install
npm run build
```

## Start the Application

```bash
php artisan serve
```

The platform will then be available through the Laravel development server.

> Development credentials, environment requirements, API information, and platform-specific instructions are maintained inside the platform repository.

---

# 📚 Documentation

Detailed documentation is maintained across the project ecosystem.

### 📖 User Guides

* 🇬🇧 [English User Manual](FishTrace/docs/user-manual-en.md)
* 🇱🇰 [සිංහල User Manual](FishTrace/docs/user-manual-si.md)

### 🔧 Technical Documentation

* [API Contract](FishTrace/docs/api-contract.md)
* [Implementation Checklist](FishTrace/docs/implementation-checklist.md)
* [Shared Hosting Deployment Guide](FishTrace/docs/shared-hosting-deployment.md)

For component-specific documentation, refer to the README of each repository.

---

# 📊 Project Status

**FishTrace is an actively developed academic and applied technology project.**

The ecosystem is developed through multiple specialized repositories, and individual components may progress at different rates.

For the most accurate implementation status, technical requirements, and setup instructions, refer to the README and documentation within each component repository.

---

# 🤝 Contributing

Contributions, testing feedback, documentation improvements, ideas, and technical suggestions are welcome.

Before beginning a significant change:

1. Open an issue in the relevant repository.
2. Describe the proposed change.
3. Discuss the implementation approach with the team.
4. Keep changes aligned with the responsibilities of the relevant component.

This helps maintain a clean architecture and prevents unnecessary cross-repository conflicts.

---

# 🗺️ Project Vision

FishTrace aims to demonstrate how modern technologies can work together to address real-world challenges in the fisheries supply chain.

```text
        OCEAN
          │
          ▼
       🎣 CATCH
          │
          ▼
      📦 BATCH
          │
          ▼
     🏭 PROCESS
          │
          ▼
     🌡️ MONITOR
          │
          ▼
       🚚 MOVE
          │
          ▼
      🏪 RETAIL
          │
          ▼
       📱 SCAN
          │
          ▼
      👤 TRUST
```

### From Ocean to Table — With Evidence at Every Step.

---

# 📄 License

The appropriate project license will be added before public production release.

---

<p align="center">
  <strong>🐟 FishTrace</strong>
</p>

<p align="center">
  <em>Building trust from ocean to table.</em>
</p>

<p align="center">
  <sub>Trace • Verify • Monitor • Understand</sub>
</p>
