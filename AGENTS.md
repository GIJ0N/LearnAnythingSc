# LearnAnything Agent Rules

- Preserve existing endpoints, localStorage key `ruta-adaptativa-v4`, and one zoom generation call.
- Do not expose `GEMINI_API_KEY`.
- Keep changes small and reversible.
- Test with mocks; never call Gemini in tests.
- Preserve diagnostic, lesson, microtutor, context-stack and review flows.
- A guided correct answer is not independent mastery.
- Run `python app_legacy.py --self-test` before declaring success.
