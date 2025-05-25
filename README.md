# Maraya (مرايا)

**Status**: 🚧 Under Development

**Maraya** — Arabic for *mirrors* — is a modular cybersecurity platform designed to continuously reflect the digital risk surface of an organization. It provides real-time threat intelligence through scanning, detection, and contextual analysis of the public, deep, and dark web.

---

## 🧠 Project Overview

**Maraya** is built as a Dynamic Risk Profiling (DRP) system with a layered architecture aimed at helping organizations detect, understand, and respond to external threats.

### 🔍 Key Goals:
- Detect impersonating domains, leaked credentials, and infrastructure exposure
- Monitor for Indicators of Compromise (IoCs) across web layers
- Enable contextual analysis and correlation of threat data

---

## 🧱 Architecture

The system is structured into **three core layers**:

### 1. **Services Layer** (🛠 In Development)
- Built with **Python**
- Scans client assets and web sources for threats
- Extracts and classifies Indicators of Compromise (IoCs)
- Supports dark web and deep web intelligence

### 2. **Correlation Layer** *(Planned)*
- Powered by **MISP (Malware Information Sharing Platform)**
- Will correlate data, enrich context, and facilitate trusted sharing

### 3. **Presentation Layer** *(Planned)*
- **Web Dashboard**: Built with **React**, integrating OpenCTI for visualization
- **Mobile App**: Built with **React Native** for on-the-go threat visibility
- **Documentation Site**: Powered by **Docusaurus** for user and developer guides

---

## 🧰 Technology Stack

| Component            | Tech Stack                  |
|---------------------|-----------------------------|
| Scanning Services    | Python                      |
| Backend APIs         | Java (Spring Boot)          |
| Web Dashboard        | React                       |
| Mobile App           | React Native                |
| Documentation        | Docusaurus                  |
| Threat Intelligence  | MISP (Planned)              |

---

## 📁 Repository Structure (Planned)

```bash
maraya/
├── services/           # Python modules for scanning and IoC extraction
├── backend/            # Spring Boot backend APIs
├── frontend-web/       # React dashboard
├── frontend-mobile/    # React Native mobile app
├── docs/               # Docusaurus documentation site
├── README.md
└── LICENSE
```


---

## 🛠 Status

- [x] Architecture defined
- [x] Core services design started
- [ ] Service layer development in progress
- [ ] Frontend and MISP integration planned

---

## 📖 Documentation

Coming soon at: [https://maraya.io/docs](https://maraya.io/docs) *(placeholder)*

---

## 🤝 Contributing

Maraya is currently under active development. Contributions are welcome soon — stay tuned for contribution guidelines, open issues, and community discussions.

---

## 🛡 License

This project will be licensed under the [MIT License](LICENSE).

---

## 🌐 About the Name

**Maraya (مرايا)** means *mirrors* in Arabic — reflecting threats that lie beyond the surface.

