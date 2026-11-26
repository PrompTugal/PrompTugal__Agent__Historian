# Learnings

- The container has no ssh-keygen; run apt-get update before apt-get install -y openssh-client.
- The signing key in the bundle must be the same key as the ssh one: take the public PEM with ssh-keygen -e -m PKCS8 -f key.pub.
