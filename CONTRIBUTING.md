## Contributing to Chat‑SQL

Thanks for your interest in contributing! This guide helps you get set up and make successful pull requests.

### Code of Conduct
By participating, you agree to abide by our Code of Conduct (see CODE_OF_CONDUCT.md).

### Development setup
1. Fork the repository and clone your fork
2. Create and activate a virtual environment
   - Windows PowerShell:
     ```bash
     python -m venv .venv
     .\.venv\Scripts\activate
     ```
3. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```
4. Run the app
   ```bash
   streamlit run app.py
   ```

### Project tips
- `student.db` is opened read-only by default. Use your own MySQL DB for write scenarios.
- You need a Groq API key to use the chat agent.

### Style
- Write clear, readable Python. Prefer descriptive names and early returns.
- Keep functions small and focused.
- Add docstrings where behavior or parameters aren’t obvious.

### Testing
- There is no test suite yet. Contributions adding a light test scaffold are welcome.

### Making changes
1. Create a feature branch: `git checkout -b feat/your-feature`
2. Commit with clear messages
3. Push and open a Pull Request (PR) against `main`
4. In your PR description, include:
   - What changed and why
   - Screenshots/GIFs for UI changes
   - Manual test steps

### Review process
- Maintainers will review for clarity, correctness, and scope.
- Please be responsive to feedback. Small, focused PRs are reviewed faster.

### Releasing
- Maintainers will tag releases. If your change is user-facing, add a brief note to the changelog section in the PR.

### Security
- Please do not file public issues for security problems. Follow SECURITY.md.


