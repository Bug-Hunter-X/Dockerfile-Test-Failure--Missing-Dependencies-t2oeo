# Dockerfile Bug: Missing Dependencies

This repository demonstrates a common error in Dockerfiles: forgetting to install project dependencies before running the application.  The initial `Dockerfile` fails to execute tests because the necessary Python packages are not installed.

The solution adds a `requirements.txt` and modifies the `Dockerfile` to install the dependencies prior to running the tests, resolving the issue.  This example highlights the importance of explicitly defining project dependencies within a Docker image to ensure consistent and predictable behavior.