# Private Administrator Panel

Real application records are stored in Supabase.

- Sign in with an authorized administrator account.
- View submitted applications (reference, date, status).
- Only users listed in `kdf_demo_admin_accounts` can access the dashboard.

Ensure RLS policies allow public inserts on the applications table and restrict reads to enrolled administrators.
