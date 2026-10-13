# SaaS POS System — Project Tracker

## 1. Project Overview

- Project: SaaS POS System
- GitHub repository: `saas-pos-system`
- Backend: Java 21, Spring Boot, Maven
- Database: MySQL
- Frontend: React, Redux Toolkit, shadcn/ui
- Architecture: Full-stack application with a monolithic backend
- Learning approach: Follow the instructor's course step by step
- Deployment goal: Docker, Kubernetes, AWS, and a public HTTPS URL

## 2. Development Workflow

For every meaningful task:

1. Follow the instructor's lesson.
2. Implement the task in this project.
3. Test the change.
4. Review files for secrets before committing.
5. Update this tracker and the relevant detailed tracker.
6. Commit and push to GitHub using the agreed commit convention.
7. Proceed to the next task.

Never commit real passwords, API keys, JWT secrets, cloud credentials, or other sensitive values.

## 3. Project Foundation

- [x] Create Spring Boot project
- [x] Configure Java 21
- [x] Start the initial Spring Boot application successfully
- [x] Commit and push the initial project
- [x] Add project dependencies to `pom.xml`
- [ ] Verify the latest dependency changes with a Maven build
- [ ] Configure and verify application properties
- [ ] Establish backend implementation tracker

## 4. Backend Roadmap

Follow the instructor's listed order.

- [ ] Login/Register API
- [ ] User API
- [ ] Store API
- [ ] Product API
- [ ] Category API
- [ ] Branch API
- [ ] Inventory API
- [ ] Employee API
- [ ] Customer API
- [ ] Order API
- [ ] Refund API
- [ ] Shift Report API
- [ ] Admin Dashboard API
- [ ] Branch Analytics API
- [ ] Store Analytics API

Detailed progress: `gaurav-pos-system/BACKEND_TRACKER.md`

## 5. Frontend Roadmap

### Cashier UI
- [ ] Create React project
- [ ] Set up shadcn/ui
- [ ] Header and product section
- [ ] Cart section
- [ ] Payment section
- [ ] Customer management UI
- [ ] Shift report UI
- [ ] Order history
- [ ] Refund UI
- [ ] Cashier routes
- [ ] Cashier sidebar

### Branch UI
- [ ] Branch sidebar
- [ ] Branch routes
- [ ] Branch dashboard
- [ ] Branch orders
- [ ] Branch inventory
- [ ] Branch settings
- [ ] Branch employee UI
- [ ] Branch reports

### Store UI
- [ ] Store layouts
- [ ] Store routes
- [ ] Store dashboard
- [ ] Branch management
- [ ] Product management
- [ ] Category management
- [ ] Employee management
- [ ] Branch settings
- [ ] Upgrade plan UI

### Super Admin UI
- [ ] Admin dashboard layout
- [ ] Admin routes
- [ ] Admin dashboard
- [ ] Pending requests
- [ ] Subscription UI

### Authentication UI
- [ ] Complete authentication UI lesson

Detailed progress: `gaurav-pos-system/FRONTEND_TRACKER.md` (create when frontend work begins).

## 6. Frontend State Management

- [ ] Global state
- [ ] Auth slice
- [ ] User slice
- [ ] Customer slice
- [ ] Order slice
- [ ] Refund slice
- [ ] Shift Report slice
- [ ] Branch slice
- [ ] Category slice
- [ ] Employee slice
- [ ] Store slice
- [ ] Product slice
- [ ] Inventory slice
- [ ] Branch Analytics slice
- [ ] Store Analytics slice
- [ ] Subscription Plan slice

## 7. API Integration

### Cashier
- [ ] Login API
- [ ] Product API
- [ ] Customer API
- [ ] Cart slice
- [ ] Order API
- [ ] Refund API
- [ ] Shift Report API

### Branch
- [ ] First integration lesson (confirm title from course)
- [ ] Branch Dashboard API
- [ ] Branch Inventory API
- [ ] Branch Employee API

### Store
- [ ] Store Overview API
- [ ] Second integration lesson (confirm title from course)
- [ ] Store Product API
- [ ] Store Employee API
- [ ] Store Sales API
- [ ] Report API
- [ ] Branch Management API
- [ ] Store Settings API

### Super Admin
- [ ] Admin Login API
- [ ] Store Management API
- [ ] Admin Dashboard API

Detailed progress: create `INTEGRATION_TRACKER.md` when integration begins.

## 8. Post-Course Testing and Deployment

These are additional project goals, not confirmed instructor lessons.

- [ ] Review application configuration and architecture
- [ ] Test backend and frontend
- [ ] Review authentication and authorization
- [ ] Remove hardcoded secrets
- [ ] Configure environment variables
- [ ] Create Docker configuration
- [ ] Build and test Docker images
- [ ] Add Kubernetes manifests
- [ ] Deploy to AWS
- [ ] Configure public HTTPS access
- [ ] Document setup and deployment
- [ ] Update README with features, architecture, and screenshots

Detailed progress: create `DEPLOYMENT_TRACKER.md` when deployment work begins.

## 9. Commit Message Convention

Format: `type(scope): concise description`

Examples:

- `chore(backend): initialize Spring Boot application`
- `chore(backend): configure project dependencies`
- `docs(project): add SaaS POS development tracker`
- `config(backend): configure application properties`
- `feat(backend-auth): implement login and registration`
- `feat(frontend-pos): build cashier terminal layout`
- `feat(integration): connect product UI with product API`
- `chore(docker): add backend Dockerfile`
- `chore(kubernetes): add backend deployment`

Use a message that accurately describes the changes in that commit.

## 10. Progress Log

| Date | Task | Verification | Status |
|---|---|---|---|
| 2026-10-13 | Initialize Spring Boot project | User confirmed successful startup | Completed |
| 2026-10-13 | Add project dependencies | User reported adding dependencies; latest Maven build not verified | Pending verification |
| 2026-10-13 | Create project tracker | To be committed and pushed | Pending |

## 11. Current Next Action

1. Create and push this tracker.
2. Create the detailed backend tracker.
3. Continue from the instructor's current lesson.
4. Verify configuration and Maven build before marking the next task complete.
