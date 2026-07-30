# daily-action

## Sync organization forks

`Sync organization forks` runs daily at 00:00 Asia/Shanghai and can also be
started manually. Add a repository Actions secret named `SYNC_FORKS_TOKEN`
using a fine-grained PAT with access to all organization repositories and
`Contents: Read and write` permission.
