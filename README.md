# Finosu Option Discovery Study

Research materials for **Representing Customer Interests in Financial AI: Making authorized alternatives visible before payment**, by Patricio Daher and Gabriel Kho, Finosu, Inc.

[Download the study kit (v1.0.0)](https://github.com/padaher93/option-discovery-study/releases/download/v1.0.0/Finosu.Option.Discovery.Study.Kit.zip) · [Release details](https://github.com/padaher93/option-discovery-study/releases/tag/v1.0.0)

The ZIP contains synthetic financial scenarios, tested instruction additions, recorded model responses, AI judgments, anonymized human review, and an offline verifier. It includes 144 final test runs and 101 exploratory runs. These are controlled model experiments, not interactions with real borrowers.

## Verify the recorded results

Download and extract the ZIP, then run inside the extracted folder:

```sh
python3 verify.py
```

Python 3 and its standard library are sufficient. The verifier makes no network or model calls. It checks file integrity and reproduces the recorded counts, including the human review. It does not independently validate the judgments.

The full operational baseline and customer conversations are excluded. Exact new inference requires the private baseline; the included instruction additions and preparation script support adaptation to another agent's configuration.

See `README.txt` and `PUBLIC_RELEASE_NOTES.txt` inside the archive for contents and scope. `SHA256SUMS.txt` provides the release archive's checksum.
