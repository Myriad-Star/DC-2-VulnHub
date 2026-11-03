# User Switching: Tom to Jerry

## Objective

Follow the hint discovered in Tom's flag to investigate access through Jerry's account.

## Command Executed

```bash
su jerry
```

The command prompted for Jerry's password and switched the current user.

To verify the switch:

```bash
whoami
```

## Findings

- Successfully switched from `tom` to `jerry`.
- User verification returned `jerry`.

## Analysis

The hint in `flag3.txt` suggested switching to Jerry. Successfully accessing the account provided an opportunity to investigate its permissions and potential privilege escalation paths.

## Conclusion

Access to Jerry's account was successfully obtained, leading to the next stage of privilege enumeration.