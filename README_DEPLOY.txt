FIRSTWOOD ERP - GITHUB PAGES DEPLOY

Thu muc nay la ban public de dua len GitHub Pages.

Quan trong:
- site-config.js dang bat FIRSTWOOD_REQUIRE_LOGIN = true.
- packaged-data.js da duoc thay bang file rong de link public khong dung du lieu dong goi.
- Du lieu ERP se duoc tai tu Supabase sau khi nguoi dung dang nhap.

Cach dung link:
1. Dua toan bo noi dung trong thu muc GITHUB_PAGES_SITE len GitHub repo.
2. Bat GitHub Pages cho repo, branch main, folder root.
3. Khach mo link GitHub Pages.
4. Khach dang nhap bang tai khoan Supabase duoc cap.
5. Quyen admin/viewer lay tu bang public.erp_profiles trong Supabase.

Cap nhat sau nay:
- Cap nhat file trong DU_AN/APP_LOCAL.
- Chay script DU_AN/UPDATE_GITHUB_PAGES_SITE.ps1.
- Commit/push DU_AN/GITHUB_PAGES_SITE len GitHub bang GitHub Desktop.
