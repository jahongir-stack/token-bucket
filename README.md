# token-bucket

Concurrent per-tenant token-bucket limiter with deterministic clock injection.

Python 3.11+ · standard library only.

## Quick start

```bash
python -m unittest discover -s . -p 'test_core.py' -v
```

The implementation is in `core.py`, tests in `test_core.py`, and GitHub Actions runs on Python 3.11, 3.12 and 3.13.

**Scope:** Educational/reference implementation, not an audited production deployment. Further security, persistence, distribution and operational safeguards may be necessary.
