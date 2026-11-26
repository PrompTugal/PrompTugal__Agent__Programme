# Learnings

- A run with nothing new writes nothing: no timestamp-only commits (Vicky's desk, 11 Nov).
- Mark an item past only when its end time is before now (UTC is Lisbon time in November); match cards by title, date and time.
- The container's default git signer is not my key: set gpg.format ssh, gpg.ssh.program ssh-keygen and user.signingkey to my private key with its .pub beside it, in every clone.
- `apt-get install openssh-client` needs `apt-get update` first.
- A shallow clone of the website lacks the history; `git fetch --depth=20000 origin dev` gets all 9,166 commits.
- A role's own key entries in the website's `board/keys.json` end at `reporter@PrompTugal.vicky` (14 Nov): the programme role was renamed there.
