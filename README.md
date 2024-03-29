<h1 align="center">Welcome</h1>

<h3 align="center">Install TailwindCSS</h3>

<p align="center">Follow some very easy step to install TailwindCSS into your system</p>

## Requirements

1. <a href="https://code.visualstudio.com/">VSCode</a>
2. <a href="https://nodejs.org/en">NodeJS</a>

## Install from GitHub

1. Clone this repository

```sh
git clone https://github.com/rironib/tailwindcss.git
```

<h3 align="center" style="color:#ff0000;">OR</h3>

## Custom Installation Process

1. Run

   ```sh
   npm init -y

   ```

2. Run

   ```sh
   npm install -D tailwindcss

   ```

3. Run

   ```sh
   npx tailwindcss init

   ```

4. Create a folder name <b style="color:green;">public</b>

   ```sh
   public

   ```

5. Replace 3rd line of tailwind.config.js file from <b style="color:#ff0000;">content: []</b> to <b style="color:green;">content: ["./public/**/*.{html,js}"]</b>

   ```sh
   content: ["./public/**/*.{html,js}"],

   ```

6. Create a folder name <b style="color:green;">src</b>

   ```sh
   src

   ```

7. Create a file inside this folder and file name will be <b style="color:green;">tailwind.css</b>

   ```sh
   tailwind.css

   ```

8. Insert these code in <b style="color:#00FFFF;">tailwind.css</b>

   ```sh
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
   ```

9. Replace 7th line of package.json file from <b style="color:#ff0000;">"test": "echo \"Error: no test specified\" && exit 1"</b> to <b style="color:green;">"build": "npx tailwindcss -i ./src/tailwind.css -o ./public/style.css --watch"</b>

```sh
"build": "npx tailwindcss -i ./src/tailwind.css -o ./public/style.css --watch"
```

10. Run

```sh
npm run build
```

11. Create a new file inside <b style="color:#00FFFF;">public</b> folder & file name will be <b style="color:green;">index.html</b>

```sh
index.html
```

12. Insert under mention code inside <b style="color:#00FFFF;">&lt;head&gt;</b> part of <b style="color:green;">index.html</b>

```sh
<link rel="stylesheet" href="style.css">
```

Done... Enjoy!

## Contact

<p align="center">
<a style="color: green; text-decoration: none;" href="https://github.com/rironib">GitHub</a> <a style="color: green; text-decoration: none;" href="https://t.me/rironib">Telegram</a> <a style="color: green; text-decoration: none;" href="https://dev.to/rironib">Dev.to</a>
</p>
