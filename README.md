# Hey, I'm Ivin

Second-year Computer Science student focused on backend engineering, networking, and infrastructure. Most of my work revolves around self-hosted systems.

## Featured Projects

### [El-Mencho](https://github.com/D-Abigor/El-Mencho)
Event banking and transaction system built for an in-person, casino-style simulation with live concurrent chip transfers.
- Enforced non-negative balances and deadlock-free transfers using deterministic lock ordering and row-level pessimistic locks in PostgreSQL.
- Built with FastAPI, raw `asyncpg` connection pooling, and background session sweeps.
- Containerised with Docker Compose and deployed behind an NGINX reverse proxy on a DigitalOcean droplet for 30+ participants.

### [Beakon](https://github.com/D-Abigor/Beakon)
Lightweight UDP broadcast and discovery tool written in Go to solve a real-world homelab problem on a campus DHCP network.
- Computes local subnet broadcast addresses on headless servers to broadcast network location on boot.
- Paired with a client-side listener featuring dynamic buffer reallocation.

### [Sudoku Solver](https://github.com/D-Abigor/sudoku-solver)
Sudoku solver built using constraint propagation rather than brute-force recursion.
- Tracks candidate elimination across rows, columns, and 3x3 grids to mirror deductive human solving techniques.

## Technologies

- **Languages:** Go, Python, Rust
- **Backend:** FastAPI, PostgreSQL, Redis
- **Infrastructure:** Linux, Docker, NGINX

## Currently Exploring

- CI/CD
- Kubernetes
