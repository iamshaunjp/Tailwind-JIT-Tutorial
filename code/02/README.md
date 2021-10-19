## JIT command with purge:
npx tailwindcss -i ./src/styles.css -o ./build/styles.css --JIT --purge="./*.html"

## Add watch:
npx tailwindcss -i ./src/styles.css -o ./build/styles.css --JIT --purge="./*.html" --watch
npx tailwindcss -i ./src/styles.css -o ./build/styles.css --JIT --purge="./*.html" -w

## Creating Tailwind config file:
npx tailwindcss init

## Run watch command with tailwind.config.js
npx tailwindcss -i ./src/styles.css -o ./build/styles.css -w