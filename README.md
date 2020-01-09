See https://sonarcloud.io/code?id=python-tests-missing-syntax-highlighting

- Files under `src` correctly have syntax highlighting.
- Files under `tests` do not have syntax highlighting.

Run example:

    sonar-scanner -Dsonar.projectKey=your-projectkey -Dsonar.organization=your-org -Dsonar.login=your-token
