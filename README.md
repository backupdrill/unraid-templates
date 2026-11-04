# BackupDrill templates for Unraid

Community Apps template for [BackupDrill](https://backupdrill.com): scheduled backups of a Supabase project's Postgres database, and optionally its Storage files, to an S3, R2 or B2 bucket you own.

- Template: [`templates/backupdrill.xml`](templates/backupdrill.xml)
- Image: `ghcr.io/backupdrill/backupdrill`, built from [backupdrill/cli](https://github.com/backupdrill/cli) (MIT)
- Every setting is an environment variable; the full list and what each one does is in the [CLI README](https://github.com/backupdrill/cli#docker--scheduled-backups-on-your-own-server)

Bugs and questions go to [backupdrill/cli issues](https://github.com/backupdrill/cli/issues).
