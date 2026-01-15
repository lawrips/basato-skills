# Basato Skills

🧪 Personal Claude skill collection - sharing what has worked for me. Use at own risk.

## Installation

```bash
/plugin marketplace add lawrips/basato-skills
/plugin install docker-dev-setup@basato-skills
```

## Available Skills

### docker-dev-setup

Set up isolated Docker dev environment for web projects with optional dynamic port detection. 

**Tested on:** I've had good success with it working on my own macOS + Node.js (patterns should adapt to other stacks)

**Features:**
- Non-root container user
- Basic security hardening (dropped capabilities, no privilege escalation)
- Hot reload via volume mounts
- Secret management support (Doppler, .env, direnv)
- VS Code launch.json integration

**Usage:** Just ask Claude to set up Docker for your dev environment, or run `/docker-dev-setup`.

## License

MIT
