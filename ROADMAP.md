# Roadmap

Planned improvements for Crop Guardian, roughly in order. Tick an item when it ships.

## Done

- [x] Python backend: classifier, hybrid diagnosis, RAG, weather risk, reports
- [x] React + TypeScript + Vite frontend preview (English and Bangla)
- [x] CI check that compiles the Python files and validates the JSON data

## Next

- [ ] README: add screenshots of the main pages and a short "how it works" section
- [ ] Tests: turn the `test_*.py` scripts into a runnable test suite and run it in CI
- [ ] API: validate uploaded images (type, size) and return clear error messages
- [ ] Connect the React frontend to the FastAPI backend as described in `frontend_preview/crop-guardian/docs/BACKEND_INTEGRATION.md`
- [ ] Frontend: loading, empty and error states for every page
- [ ] Bangla: review the translations and fill any missing text
- [ ] Accessibility and responsive polish (labels, contrast, keyboard use, small screens)
- [ ] History page for past diagnoses
- [ ] PDF report polish
- [ ] Dockerfile for running the API
- [ ] Frontend type check and build in CI

## Notes

- The existing backend behaviour and the model file must stay unchanged unless a change is explicitly planned.
- Never commit API keys or `.env` files.
