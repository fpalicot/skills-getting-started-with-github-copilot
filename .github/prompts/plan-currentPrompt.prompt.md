1. Review the current FastAPI activity signup flow and identify where participant updates are not reflected immediately in the UI.
2. Update the frontend so successful signup and unregister actions re-render the activity cards without requiring a manual page refresh.
3. Keep the activity dropdown in sync so options are rebuilt cleanly after each refresh.
4. Add or refine backend FastAPI tests under the tests directory using pytest and the Arrange-Act-Assert pattern.
5. Ensure pytest is listed in requirements.txt so the test suite can be installed and run in a fresh environment.
6. Verify the changes by running the test suite with pytest and confirming the app behavior remains intact.