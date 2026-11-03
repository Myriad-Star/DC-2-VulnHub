# Custom Wordlist Generation with CeWL

## Objective

Generate a target-specific wordlist from the DC-2 website for password auditing.

## Tool and Command

**CeWL**

```bash
cewl http://dc-2/ -w wordlist.txt
```

CeWL crawls the specified website and extracts words into a custom wordlist.

## Findings

- Generated 238 unique words.
- Wordlist saved as `wordlist.txt`.
- File size: approximately 1.7 KB.

## Analysis

The generated words were used as password candidates during subsequent WordPress authentication testing. CeWL only generates the wordlist; it does not crack passwords.

## Conclusion

A custom wordlist was successfully generated and prepared for use with WPScan.