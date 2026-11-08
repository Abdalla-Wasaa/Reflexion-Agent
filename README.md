# Reflexion Agent

Run the chains module from the project root:

```bash
uv run python -m reflexion_agent.chains
```

`uv run` installs the project and its dependencies into the project environment.
Run this as a module instead of running `src/reflexion_agent/chains.py` directly,
so Python can resolve package-relative imports such as `from .schemas import AnswerQuestion`.
Ensure the required provider credentials are available in your environment.

For VS Code debugging, select **Python: Reflexion chains** in Run and Debug,
then press **F5**. This configuration runs the module and loads credentials from
the project's `.env` file. Select the project's `.venv` Python interpreter when
prompted.
