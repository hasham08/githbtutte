`README.md` is a plain text instruction file inside the zip. You don't run it or install it. You just read it, and any text editor can open it (Notepad, VS Code, or double-click it).

The steps in it are:

1. **Unzip** `rifaah-billing-react.zip` into a folder on your computer.
2. **Install Node.js** (the LTS version) from nodejs.org if you don't have it.
3. **Open a terminal in the project folder.** On Windows, open the folder, click the address bar, type `cmd` and press Enter.
4. **Install the packages:** `npm install`
5. **Test on your computer (optional):** `npm run dev`, then open the address it shows, usually http://localhost:5173.
6. **Build the website files:** `npm run build`. This creates a `dist` folder.
7. **Upload to cPanel:** open File Manager → `public_html`, delete the old files, and upload everything **inside** `dist` (not the `dist` folder itself).
8. **Refresh the site** with Ctrl+F5.

Login: **admin / admin123**. Change it in Admin → My account.

For the mobile apps (installing from the website, and Android and iOS builds), read `MOBILE.md` in the same folder.

If you get stuck on any step, send me the error message or a screenshot and I'll help.
