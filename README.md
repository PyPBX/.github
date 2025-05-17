# PyPBX

**PyPBX** is a modern, modular, open-source VoIP and telephony management platform built in Python.  
It is designed to be a clean, extensible, and developer-friendly alternative to legacy PBX GUIs such as FreePBX and Issabel — powered by a modern tech stack and deeply integrated with Asterisk.

---

## 🚀 Mission

PyPBX aims to:
- Modernize PBX management interfaces using Python, FastAPI, and a reactive frontend.
- Provide a modular architecture for extensions and custom call logic.
- Improve maintainability, security, and performance compared to legacy PHP-based PBX systems.
- Empower organizations and developers to build, extend, and scale voice communication infrastructure effortlessly.

---

## 🔧 Core Features (Planned)

- 🧩 **Modular Web UI** (React/Vue)
- ⚙️ **RESTful API** using FastAPI
- 📞 **Asterisk Integration** (via AMI/ARI/AGI)
- 🧠 **Dialplan & Extension Management**
- 🎛️ **IVR / Queues / Trunks Configuration**
- 🔁 **Conf File Generator & Live Reload**
- 🔒 **User & Role-Based Access Control**
- 📊 **Call Monitoring (WebSocket / Live Events)**
- 🎙️ **Call Recording Interface**
- 🌐 **Multi-language & Multi-tenant Ready**
- 📦 **Plugin System for Extensions (e.g., CRM, Billing)**

---

## 🗺️ Roadmap

### ✅ Phase 1: Bootstrap & Infrastructure (Q2 2025)
- [x] Create GitHub organization
- [x] Define system architecture
- [x] Launch core repository: `pypbx-core`
- [ ] Set up Docker-based dev environment
- [ ] Initial database schema (users, extensions, trunks)
- [ ] Define plugin architecture (entry point-based)

### 🚧 Phase 2: Core PBX Features (Q3 2025)
- [ ] Build admin API (FastAPI + Pydantic)
- [ ] Asterisk AMI/ARI connector layer
- [ ] Conf file generator (Jinja2)
- [ ] Extension & dialplan management
- [ ] UI prototype (React or Vue)
- [ ] Role-based auth (JWT / OAuth2)

### 🔄 Phase 3: Advanced Capabilities (Q4 2025)
- [ ] Queue & IVR management
- [ ] Trunk & route configuration
- [ ] Call recording dashboard
- [ ] Real-time dashboard via WebSockets
- [ ] User provisioning & tenant isolation

### 🧪 Phase 4: Community Modules & Beta Release (Q1 2026)
- [ ] Plugin: Simple CRM integration
- [ ] Plugin: Call center metrics
- [ ] Plugin: Voicemail manager
- [ ] Release stable Beta v0.9
- [ ] Documentation site & CLI tool

---

## 📂 Repositories Structure

| Repo | Description |
|------|-------------|
| [`pypbx-core`](https://github.com/PyPBX/pypbx-core) | Backend API (FastAPI), database models, service logic |
| `pypbx-ui` | Frontend UI (React or Vue) |
| `pypbx-ami` | Python-based interface to Asterisk AMI |
| `pypbx-ari` | ARI wrapper and async control interface |
| `pypbx-plugins` | Official and community plugins |
| `pypbx-docker` | Docker-compose environment for dev & testing |

---

## 🙌 Contributing

We welcome all contributors — developers, sysadmins, VoIP experts, and documentation writers!

### To get involved:
- Clone the [core repo](https://github.com/PyPBX/pypbx-core) (coming soon)
- Check the [issues](https://github.com/PyPBX/pypbx-core/issues) and pick one
- Join the discussions under the [Discussions tab](https://github.com/PyPBX)

### Communication Channels
- Discord / Matrix (coming soon)
- GitHub Discussions

---

## 🛡 License

PyPBX is released under the **MIT License** (pending confirmation).

---

## 🤝 Acknowledgements

- Inspired by FreePBX, VitalPBX, and FusionPBX
- Built with love by the Python and Asterisk communities

---

