1. Update all packages using pip

On Windows
` for /F "skip=2 delims= " %i in ('pip list --outdated') do pip install --upgrade %i `

On Linux/MacOS
` pip list --outdated --format=freeze | grep -v '^\\-e' | cut -d = -f 1 | xargs -n1 pip install -U `

2. How to be better at python

You don't :); Just be better at it, or read/reread https://www.w3schools.com/python and https://www.python.org/doc


3. PEP 8 Style Guide for Python Code
Follow the official style guide for Python code formatting, including naming conventions, line length, and indentation:
https://peps.python.org/pep-0008/#introduction
>"Use 4 spaces per indentation level" and "Limit all lines to a maximum of 79 characters".
> This ensures code readability and consistency across projects. 
> It'll help trust
