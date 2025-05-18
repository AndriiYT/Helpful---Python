1. Update all packages using pip

On Windows
` for /F "skip=2 delims= " %i in ('pip list --outdated') do pip install --upgrade %i `
