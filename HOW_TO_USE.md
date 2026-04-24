# How to Use This Research Pack

1. Download and unzip this pack.
2. Copy all files into the root of your local GitHub repository.
3. Open the repo in Cursor.
4. Review `README.md` and `research/sources.md`.
5. Run the first commit.
6. Install transcript dependency:

```bash
pip install -r requirements.txt
```

7. Run transcript collection:

```bash
python scripts/fetch_youtube_transcripts.py
```

8. Manually collect LinkedIn posts and non-YouTube source notes.
9. Update `research/other/synthesis-notes.md`.
10. Commit and push regularly.

See `research/other/git-commands.md` for suggested commit commands.
