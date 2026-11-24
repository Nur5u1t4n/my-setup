# Security baseline

This checklist defines the baseline for protecting computers documented in this
repository. It is a maintenance guide, not proof that every control is currently
enabled.

## Public-information policy

Never commit or publish:

- Serial numbers, UUIDs, asset tags, MAC addresses, product keys, recovery keys,
  passwords, tokens, private keys, or authentication cookies.
- Full diagnostic exports containing unique device identifiers.
- Exact firmware and driver inventories unless there is a clear public support
  reason.
- Private network details, internal hostnames, VPN configuration, or remote-access
  endpoints.
- Screenshots that expose account names, email addresses, device IDs, or security
  settings beyond what is necessary.

For public documentation, prefer broad descriptions such as device family,
processor class, memory capacity, storage capacity, and operating-system edition.
Keep detailed inventories in private local files.

## Windows and firmware checklist

- [ ] Install Windows, browser, application, and driver security updates promptly.
- [ ] Obtain firmware and drivers from the device manufacturer or trusted
      component vendors. Verify the model before applying firmware updates.
- [ ] Check TPM 2.0 status locally using Windows Security and `tpm.msc`.
- [ ] Review Secure Boot status locally. Enable it when supported and compatible
      with the installed operating system and boot configuration.
- [ ] Enable BitLocker or Device Encryption where available; store the recovery
      key separately from the computer.
- [ ] Keep Microsoft Defender Antivirus and Windows Firewall enabled unless a
      documented, justified exception exists.
- [ ] Use a standard (non-administrator) account for everyday work; elevate only
      when required.
- [ ] Use a strong, unique sign-in method and enable multifactor authentication
      on important online accounts.
- [ ] Disable remote access and services that are not needed.
- [ ] Maintain tested backups, including at least one copy that is not continuously
      writable from the computer.

## Local verification notes

Record detailed results in a private file, not in this public repository:

- TPM readiness and activation state.
- Secure Boot state and any reason it cannot be enabled.
- Device Manager errors and missing drivers.
- Firmware and driver versions needed for a support case.
- Encryption status and backup recovery test results.

Do not paste recovery keys, serial numbers, UUIDs, MAC addresses, or full diagnostic
reports into issues, pull requests, public discussions, or AI prompts.

## Incident response

If a credential, recovery key, token, or other secret is exposed:

1. Revoke or rotate it immediately.
2. Review relevant account and device activity.
3. Remove the secret from the repository and its history where appropriate.
4. Treat the exposed value as compromised even after removal from the latest commit.
