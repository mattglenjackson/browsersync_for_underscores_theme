
# Browser-Sync package installer for _s (underscores) WordPress theme.

This is for Browser-Sync package for _s (underscores) WP theme.

1. **Download Required Files:**
   - Download the `bs-config.js` and `package.json` files.
   - Place these files in the root directory of your _s (underscores) WordPress theme.

2. **Configure `bs-config.js`:**
   - Open the `bs-config.js` file.
   - Locate the line `"proxy": 'INSERT LOCAL DEV WEBSITE HERE'`.
   - Replace `'INSERT LOCAL DEV WEBSITE HERE'` with the URL of your local development website 
   - eg: "http://192.168.33.10/wordpress".

3. **Install Packages:**
   - Open your command line interface.
   - Navigate to the root folder of your _s WordPress theme.
   - Run the following commands:
     ```bash
     composer install
     npm install
     ```

4. **Run Watcher for SCSS to CSS Conversion:**
   - In the command line interface, while still in the theme's root folder, run:
     ```bash
     npm run watch
     ```
   This command starts a watcher that automatically converts SCSS files to CSS whenever changes are made.

5. **Run Browser-Sync Server:**
   - Still in the command line interface and in the theme's root folder, run:
     ```bash
     npm run sync
     ```
   This command launches the Browser-Sync server.
