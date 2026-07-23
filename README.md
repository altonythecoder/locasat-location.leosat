# 🛰️ locaSAT: Global LEO Satellite Tracker & Ground Control Station

Real-time 3D Space Domain Awareness (SDA) platform tracking Low Earth Orbit (LEO) constellations (Starlink, OneWeb, Iridium NEXT, Planet Labs, ISS) with 60 FPS smooth interpolation using SGP4 orbital mechanics and CesiumJS.

---

## 🚀 Quick Start with Docker

```bash
# Clone the repository
git clone [https://github.com/altonythecoder/locasat-location.leosat](https://github.com/altonythecoder/locasat-location.leosat)
cd locasat-location.leosat

# Run with Docker Compose
docker compose up --build

Access the Ground Control Station UI at http://localhost:8000.
```

## 🛠️ Tech Stack & Architecture
```bash
Backend: Python 3.11, FastAPI, WebSockets, Skyfield (SGP4 Orbital Propagator), Pydantic (schemas.py)

Frontend: CesiumJS 3D WebGL Globe, HTML5/CSS3 Glassmorphism UI

DevOps: Docker, Docker Compose
```

