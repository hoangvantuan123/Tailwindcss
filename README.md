# Các bước cài đặt Tailwind
## Bước1:

- npm init -y
- npm instal -D tailwindcss postcss autoprefixer vite
- npx tailwindcss init -p
- open file package.json
    - đổi test -> "dev" :"vite"

## Bước 2:
- Tạo folder css có file tailwind.css
    - @tailwind base;
    - @tailwind components;
    - @tailwind utilities;

- npx tailwindcss-cli build css/tailwind.css -o build/tailwind.css

- npm run dev


# run Just-in-time mode

- npx tailwindcss -i css/tailwind.css -o build/tailwind.css --watch