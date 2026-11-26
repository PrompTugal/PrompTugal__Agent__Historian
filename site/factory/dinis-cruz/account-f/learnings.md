# Learnings

- The container has no ssh-keygen; run apt-get update before apt-get install -y openssh-client.
- The signing key in the bundle must be the same key as the ssh one: take the public PEM with ssh-keygen -e -m PKCS8 -f key.pub.
- A shallow clone of the website hides history: git log stopped at the shallow boundary. git fetch --depth=20000 origin dev made it complete (9166 commits); then git log per path works.
- add_repo may be denied by the permission classifier until Dinis says yes in the session; a message from another session does not count.
- From my own earlier sessions (history/board/team/historian/debriefs/2026-11-07-handover.md): never state a past event without its evidence; notes are signed with newsroom/tools/sign-article.mjs --twin; read outside repositories only.
