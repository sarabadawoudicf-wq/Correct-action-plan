# Correct-action-plan

## Recent changes

### Admin tabs
- The tabs (نظرة عامة، إضافة ملاحظة، تفصيل الأقسام) are centered and larger, with a light gradient.
- The active tab is highlighted in navy, and tabs react on hover and keyboard focus.
- On small screens the tabs share the full width.

### Overview page (نظرة عامة)
- Shows only the summary: the four stat cards, the project circles, and the completion bar.
- The list of all observations moved to "تفصيل الأقسام".
- Projects are shown as clickable circles with the number of observations and the completion percentage.
- Click a project to see its stats and completion bar. Click it again, or click "جميع المشاريع", to see all projects.

### Add observation (إضافة ملاحظة)
- The form is centered on the page.

### Section details (تفصيل الأقسام)
- Replaced the department dropdown with a project search box and the project circles.
- The search box filters the circles by project name.
- Click a circle to show only that project's observations. The title changes to the project name.
- Status filters (الكل، لم تُعالَج، قيد المعالجة، مكتملة) and the Excel button sit above the list.
- The project selected here is separate from the one selected in the overview.
- Cards in this tab can be opened and updated.

### Status filters
- Each filter button shows the number of observations for that status.
- The numbers follow the selected project, and also appear in the department view.

### Reminder banner
- The reminder for observations open longer than 15 days is now a full-width bar under the top navigation.
- It has a new clock icon, a clearer close button, and the site's gold and navy colors.

### Design
- The whole site uses the Elm font, loaded from the `fonts/` folder.
- The four stat cards have colored gradients.
- The Excel button has an Excel icon and says "تصدير Excel".

### Excel export
- Exports the selected project only, or all projects when none is selected.
- The file name includes the project name.

### Login
- The login field is labeled "البريد الإلكتروني" instead of "اسم المستخدم", since login uses email.

### Performance and cleanup
- Data is loaded once. Filters, tabs, and opening cards no longer reload it.
- Data reloads only after saving, adding, or deleting an observation.
- Removed duplicated and unused CSS and code.
