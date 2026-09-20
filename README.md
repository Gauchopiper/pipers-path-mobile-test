# Piper’s Path mobile TEST preview

Source: Gauchopiper/pipers-path feature/dual-feedback at d97c6378bddd6a8b715875ec096bae1cac68a71a.

Generated using tools/build-pupil-test.cjs, from PupilStandalone.html. The TEST endpoint placeholder is configured, the redundant external feedback script is removed, and production service-worker cleanup is removed to avoid affecting the production site on the shared GitHub Pages origin. No backend changes. No pupil access keys or pupil data are included.

Open the HTTPS page and paste the complete existing dummy pupil test link when prompted. Its credentials are read from the fragment and kept in memory.

All three existing regression suites passed. Leslie reported the physical-phone test PASSED on 2026-09-20: microphone permission, recording, playback, upload and TEST logging, Path loading and Group loading. This is a user-performed real-device result, not an agent microphone test. The tested static page was published at commit 260887b; this documentation update does not change it.

The earlier Apps Script iframe microphone permissions-policy failure is isolated to that hosting context by the successful separate HTTPS test. Keep this temporary site available for now. Production and the approved TEST backend remain unchanged. Targets, badges and production scoring remain outside this diagnostic.
