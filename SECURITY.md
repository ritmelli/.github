# Security policy

## Reporting a vulnerability

Please don't report security problems in a public issue. Report them privately on GitHub instead:
[Report a vulnerability](https://github.com/ritmelli/ritmelli/security/advisories/new) (the **Security** tab of
[ritmelli/ritmelli](https://github.com/ritmelli/ritmelli), then **Report a vulnerability**). Only you and the Ritmelli
team can see the report. You need a free GitHub account, and you can write in English or Portuguese.

Please include:

- what is affected and how someone could exploit it;
- the steps to reproduce it;
- the Ritmelli version (**Settings > Apps** in Windows shows it next to Ritmelli).

We reply in the report itself, work on the fix there with you and publish it in a new release, which installed copies
of Ritmelli get through their automatic updates. Once the fix is out, the report becomes a public security advisory,
with credit to you if you want it.

## What to report

Anything that lets someone do what they shouldn't through Ritmelli, for example:

- controlling Ritmelli from another device on the network without pairing it with the 6-digit code;
- getting the installed Ritmelli to install an update that isn't signed by the Ritmelli team, or an older version;
- gaining administrator or SYSTEM rights through the installer, the "Ritmelli Atualiza" task or the microphone task;
- making the microphone filter crash the Windows audio service or leak audio to another program.

## Supported versions

Only the latest release gets security fixes. Installed copies of Ritmelli update themselves, so keep automatic updates
working (they install when Ritmelli is closed).

Problems in a component that Ritmelli ships but doesn't make (yt-dlp, ffmpeg, Deno, Python libraries) belong to that
project; if one affects Ritmelli in a way the upstream fix doesn't cover, report it here too.

## Em português

Para avisar de uma falha de segurança, não abra uma issue pública: use o link
[Report a vulnerability](https://github.com/ritmelli/ritmelli/security/advisories/new), que só a equipe do Ritmelli vê.
Pode escrever em português.
