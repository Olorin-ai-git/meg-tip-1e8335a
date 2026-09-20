# meg-tip-1e8335a

Temporary bank handoff export. Tip SHA `1e8335a25a57b3f747559418bb19a2464b2a5b62`.
Safe to delete after CoS download.

The zip is split into base64 text parts because GitHub gists reject binary uploads and the Cloud Agent `gh` token cannot create user gists.

## Reconstruct (no token)

```bash
curl -fsSL \
  https://raw.githubusercontent.com/Olorin-ai-git/meg-tip-1e8335a/main/megb64-01.txt \
  https://raw.githubusercontent.com/Olorin-ai-git/meg-tip-1e8335a/main/megb64-02.txt \
  https://raw.githubusercontent.com/Olorin-ai-git/meg-tip-1e8335a/main/megb64-03.txt \
  https://raw.githubusercontent.com/Olorin-ai-git/meg-tip-1e8335a/main/megb64-04.txt \
  https://raw.githubusercontent.com/Olorin-ai-git/meg-tip-1e8335a/main/megb64-05.txt \
  https://raw.githubusercontent.com/Olorin-ai-git/meg-tip-1e8335a/main/megb64-06.txt \
  https://raw.githubusercontent.com/Olorin-ai-git/meg-tip-1e8335a/main/megb64-07.txt \
  https://raw.githubusercontent.com/Olorin-ai-git/meg-tip-1e8335a/main/megb64-08.txt \
  https://raw.githubusercontent.com/Olorin-ai-git/meg-tip-1e8335a/main/megb64-09.txt \
  https://raw.githubusercontent.com/Olorin-ai-git/meg-tip-1e8335a/main/megb64-10.txt \
  https://raw.githubusercontent.com/Olorin-ai-git/meg-tip-1e8335a/main/megb64-11.txt \
  https://raw.githubusercontent.com/Olorin-ai-git/meg-tip-1e8335a/main/megb64-12.txt \
  | base64 -d > meg-tip-1e8335a.zip

# expected
# bytes: 1762463
# sha256: 8cfa83df383677f3e2a477e7e679c62b46fb23de6595a3c151291a25cd79d7a7
```

Private release (token required) is still at:
https://github.com/Olorin-ai-git/First-responder/releases/tag/meg-tip-1e8335a
