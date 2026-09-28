# Correct-action-plan

## Recent changes

### Overview page
- Projects are now shown as clickable circles instead of a horizontal filter bar.
- Each circle shows the number of observations and the completion percentage.
- Click a project to see only its observations. Click it again, or click "جميع المشاريع", to see all projects.
- The status filters (لم تُعالَج, قيد المعالجة, مكتملة) now work together with the project filter.
- The stat cards and the completion bar show the data for the selected project.
- The completion bar is now below the project circles.

### Design
- The four stat cards at the top now have colored gradients.
- The project circles are centered.
- The Excel button has a new Excel icon and says "تصدير Excel".

### Excel export
- Exports the selected project only, or all projects when none is selected.
- The file name includes the project name.

### Login
- The login field is now labeled "البريد الإلكتروني" instead of "اسم المستخدم", since login uses email.

### Performance and cleanup
- Data is loaded once. Filters, tabs, and opening cards no longer reload it.
- Data reloads only after saving, adding, or deleting an information.
- Removed duplicated CSS and code.

### Fixes
- Cards in the "تفصيل الأقسام" tab can now be opened and updated.
