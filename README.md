# MediFlow - Clinic Management System

## Project Overview
A responsive clinic management system with role-based dashboards (Admin, Nurse) and medicine inventory tracking.

## Laboratory Requirements
- ✅ CSS Grid Layout
- ✅ Accessibility Audit
- ✅ Keyboard Navigation
- ✅ Device Simulation

## How to Run
1. Make sure WAMP server is running
2. Open browser and go to: `http://localhost/clinic-management-system/`
3. Login with:
   - **Admin:** username: `admin`
   - **Nurse:** username: `nurse`

| Member | Contribution | File | Status |
|--------|--------------|------|--------|
| Member 1 | Global Styles & Reset | `css/member1-base.css` | ✅ Completed |
| Member 2 | Layout & Responsive Grid | `css/member2-layout.css` | ✅ Completed |
| Member 3 | UI Components | `css/juniesaludes-components.css` | ✅ Completed |
---

**Created by:** Ian Duyogan - Member 1
**Date:** March 25, 2026

## Member 2: Layout & Responsive Grid System
**Author:** Sheina Abegail Lala
**File:** `css/member2-layout.css`
**Date:** March 25, 2026

### Contributions:
1. **CSS Grid Layout** - Mobile-first grid system (1-2-3 columns)
2. **Responsive Breakpoints** - Tablet (768px), Desktop (1024px)
3. **Navigation Layout** - Flexbox navigation with backdrop blur
4. **Card Hover Effects** - Smooth transform and shadow transitions
5. **Device Optimizations** - iPhone SE, iPad Pro specific styles

## Member 3: UI Components
**Author:** Junie Saludes
**File:** `css/juniesaludes-components.css`
**Date:** March 26, 2026

### Contributions:
1. **Card Components** - Styled cards with hover effects
2. **Button Variants** - Primary, outline, secondary, danger buttons
3. **Form Inputs** - Styled inputs with focus states
4. **Badge Components** - Primary, warning, success badges
5. **Alert Messages** - Success, error, warning alerts
6. **Progress Bar** - Custom styled progress indicator
7. **Tooltip** - Hover tooltip effect
8. **Loading Shimmer** - Animated loading effect

### Code Snippet:
```css
button {
    background: var(--primary-color);
    border-radius: 60px;
    transition: all 0.2s ease;
}

button:hover {
    transform: translateY(-2px);
    box-shadow: 0 4px 12px rgba(30, 111, 92, 0.3);
}

### Code Snippet:
```css
.dashboard-grid {
    display: grid;
    grid-template-columns: 1fr;
    gap: 1.5rem;
}

@media (min-width: 768px) {
    .dashboard-grid {
        grid-template-columns: repeat(2, 1fr);
    }
}

@media (min-width: 1024px) {
    .dashboard-grid {
        grid-template-columns: repeat(3, 1fr);
    }
}