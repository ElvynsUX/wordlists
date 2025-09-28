# Wordlists
A curated and categorized collection of wordlists for various purposes including reconnaissance, enumeration, fuzzing, stress testing, and data work. Files are organized by purpose to enable easy access to targeted lists (small/medium) or large sets for exhaustive tests.

## Notice
This repository aggregates third-party lists and generated files. I do not claim ownership of third-party content. Open an issue or PR if you require removal or attribution changes.

## Quick Links
- Discovery: directory, path, and endpoint discovery lists
- Famous: popular names, brands, and terms
- HTB (Hack The Box): HTB-oriented lists (users, subdomains, directories)
- Languages: language dictionaries and locale wordlists
- Miscellaneous: assorted helper lists (profanity, BIP39, etc.)
- Names: first/last/full names and regional name sets
- Passwords: leaked dumps, curated password lists
- Security Question Answers: cities, dates, surnames, zip codes, etc.
- Stressing: generated numeric/alphanumeric/Unicode lists for stress testing
- User Agents: UA strings split by device, OS, and software
- Usernames: aggregated username lists and defaults
- Vulnerabilities: vulnerability patterns, payload fragments, and component-specific strings

## Purpose & Scope
This repository centralizes wordlists used for:
1. Fast reconnaissance and targeted enumeration (use small curated lists first).
2. Deeper enumeration or exhaustive fuzzing (use mid/large lists as needed).
3. Load and stress testing (generated lists intended for high coverage).
Files range from compact, high-signal lists to multi-million-line datasets. Verify tool compatibility before using very large files.

## Usage Notes
- Prefer small curated lists for initial scans; escalate to larger lists only when required.
- Do not open very large files in standard editors; stream or split them (pv, split, or tool streaming).
- Convert case or normalize if your workflow assumes lowercase:
```bash
tr '[:upper:]' '[:lower:]' < list.txt > list-lower.txt
```

## Contributing
- Add new lists under the appropriate folder and include a short SOURCE or README next to large files describing origin and license (if known).
- Submit a pull request with a concise description and source attribution when possible.
- If you supplied a list that appears here without attribution, open an issue or PR to request attribution or removal.

## NOTICE & License Guidance
Third-party files may carry their own licenses. I do not claim copyright on third-party content.
If you need a list removed or attributed differently, open an issue or PR.

## Safety & Legal
These wordlists are provided for authorized, ethical, and legal activities only (security research, permitted penetration testing, education, and tooling). Unauthorized or illegal use is prohibited. By using these files you accept responsibility for complying with applicable laws and terms of service.

## Contact & Issues
For missing attributions, removal requests, or contribution questions: open an issue or submit a pull request.