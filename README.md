# salt-nox-pre-commit
Nox Pre-Commit Repo for Salt

For pre-commit: see https://github.com/pre-commit/pre-commit

For nox-py2: see https://github.com/s0undt3ch/nox

Fox nox: https://github.com/theacodes/nox


### Using nox-py2 with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: https://github.com/saltstack/salt-nox-pre-commit
        rev: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: nox-py2
