# Go Web Template	

A small Go web-app template I started in 2021 to learn the standard
library's web stack idioms — `net/http` + `html/template` + handler-based
routing without a framework.

## Includes
- `handlers/` — sign-in, logout, home, index handlers
- `middlewares/auth.go` — auth middleware
- `services/cache.go` — caching service
- `templates/` — Go HTML templates with a base layout + page views

## Status
A learning template from when I first picked up Go. Sat dormant until
I returned to Go in 2025 for a drone-operations side project.
