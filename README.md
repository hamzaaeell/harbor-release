# Harbor

Harbor applies to jobs for you — LinkedIn and company career sites — from your own Mac, at a human pace, with
your own profile and browser.

## Download

Get the latest **Harbor-x.y.z.dmg** from [Releases](../../releases). Apple Silicon Macs (M1 or newer), macOS 12+.

1. Open the DMG and drag **Harbor** into **Applications**.
2. The first time, macOS may say Harbor is from an unidentified developer: open **System Settings → Privacy &
   Security** and click **Open Anyway**.
3. In Harbor, open **Settings** and add your OpenRouter and RemoteHerd API keys, then create your profile.

Later versions install themselves from inside Harbor (**Settings → Updates**).

## Check your download

Each release lists the DMG's SHA-256. In Terminal:

```
shasum -a 256 ~/Downloads/Harbor-*.dmg
```

## Your data

Profiles, resumes, browser sessions and API keys stay on your Mac in `~/Library/Application Support/Harbor`.
Harbor asks before sending anonymous usage reports (job board, whether an application went through, the error if
not) — never your name, email, phone, resume, answers, logins or keys. You can turn this off in Settings.
