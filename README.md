# AI Group Presentation Evaluation App

Files:
- index.html: student evaluation page
- admin.html: teacher dashboard
- schema.sql: Supabase database/security setup

## Setup
1. Create a Supabase project.
2. Run schema.sql in Supabase SQL Editor.
3. Create a teacher user in Authentication > Users.
4. Copy the Supabase Project URL and Publishable Key.
5. Replace the two placeholders in both HTML files.
6. Test index.html.
7. Upload index.html and admin.html to a public GitHub repository.
8. Enable GitHub Pages.

Student page: /index.html
Teacher page: /admin.html

The database blocks self-group evaluation and duplicate evaluation of the same group. Teacher results require Supabase authentication.

Important: never put a Supabase service-role/secret key in the HTML.
