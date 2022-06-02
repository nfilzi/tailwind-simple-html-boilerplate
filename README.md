Built following guidelines from https://tailwindcss.com/docs/installation

To access HTML output with proper tailwind CSS output, you need to run the following commands in parallel

```bash
# First terminal tab
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
```

```bash
# Second terminal tab
# Command set for Le Wagon alumni during setup day
serve .
```
