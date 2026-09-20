# Piper’s Path mobile TEST preview

Source: Gauchopiper/pipers-path feature/dual-feedback at d97c6378bddd6a8b715875ec096bae1cac68a71a.

Generated using tools/build-pupil-test.cjs, from PupilStandalone.html. The TEST endpoint placeholder is configured, the redundant external feedback script is removed, and production service-worker cleanup is removed to avoid affecting the production site on the shared GitHub Pages origin. No backend changes. No pupil access keys or pupil data are included.

Open the HTTPS page and paste the complete existing dummy pupil test link when prompted. Its credentials are read from the fragment and kept in memory.

All three existing regression suites passed. Physical mobile recording/upload remains to be tested by Leslie.
