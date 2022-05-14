### List of Views, Sections, and Components:
---
- **MainHeader.vue**
  - logo
  - nav
    - nav links

---
- HomeView.vue [Forside]
  - WelcomeSection.vue
    - NavTo.vue
    - Heading2.vue
    - TextArea.vue
    - AnnouncementBanner.vue
  - ScheduleSection.vue
    - NavTo.vue
    - Heading2.vue
    - BusinessHours.vue
    - ScheduleTable.vue
  - NewsSection.vue
    - NavTo.vue
    - Heading2.vue
    - TextArea.vue
    - NewsArticle.vue (for-loop)
---
- FrolView.vue [Frolerne]
  - ServicesSection.vue
    - NavTo.vue
    - Heading2.vue
    - Disclaimer.vue
    - MenuList.vue
  - FrolSection.vue
    - NavTo.vue
    - Heading2.vue
    - FrolComponent.vue (for-loop)
---
- **MainFooter.vue**
    - ContactSection.vue
      - Heading2.vue
      - GoogleMap.vue
      - ContactInfobox.vue
---

# Styling:

Styling is written internally on individual components as scoped SCSS, for simplicitys sake.

Global variables are defined as regular CSS variables in the "root" element in "App.vue".

Locally, variables for individual components are defined as SCSS variables, where the the value is equal to the the corresponding global CSS variable, ie.: "$bg-color: var(--primary-color)".  