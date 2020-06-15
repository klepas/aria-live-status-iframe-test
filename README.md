# aria-live-status-iframe-test

This is a simple test for usage of ARIA live regions (`role="status` regions in this case) _inside_ of an iframe.

Inspired by https://github.com/FreedomScientific/VFO-standards-support/issues/111

This setup places numerous ARIA status regions inside the iframe instead of on a wrapping div outside the iframe, since we need to have granular control as to what is read out (we don’t want to read out the Submission ID).
