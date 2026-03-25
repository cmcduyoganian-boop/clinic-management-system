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