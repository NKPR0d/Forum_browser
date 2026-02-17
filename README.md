# Audiogames Forum Browser

A lightweight and fast program designed for convenient browsing of the [AudioGames.net](https://forum.audiogames.net) forum. 

This project was inspired by a legacy forum browser from years ago. I have completely rewritten it in NVGT, optimizing the code and updating the parser to work with the modern HTML structure of the forum.

## ⚠️ Cloudflare Bypass Information

Due to security changes on the AudioGames.net website, Cloudflare protection must be bypassed to access the forum content.

### For Source Code Users:
If you are running the program from source code, you will need a local instance of FlareSolverr:
1. Download and run [FlareSolverr](https://github.com/FlareSolverr/FlareSolverr/releases).
2. Ensure it is running on its default port (`http://localhost:8191`).

### For Release Version Users:
If you are using the **compiled release (.exe)**, you **do not need** to download or run FlareSolverr. The program is pre-configured to use a remote proxy to handle the bypass automatically. Just launch the app and enjoy!

## Controls
The application is designed with accessibility in mind and follows standard keyboard navigation:

*   **Up / Down Arrows:** Scroll through the menus.
*   **Left / Right Arrows:** Switch between pages of topics or posts.
*   **Space:** Jump to a specific page number.
*   **Enter:** 
    *   Select a menu item.
    *   When on a post: Open it in a separate dialog for line-by-line reading, copying, etc.
*   **Alt + Enter:** (On a post with links) Open a dedicated links menu to quickly open URLs in your default browser.
*   **F1 - F6:** (While focused on a post) View detailed user information:
    *   **F1:** User Rank
    *   **F2:** Status (Online/Offline)
    *   **F3:** Location (From)
    *   **F4:** Registration Date
    *   **F5:** Total Post Count
    *   **F6:** User Karma
*   **Escape:** Go back or exit the application.

## Credits & Support
Developed by **Nikita K.**

Feel free to use, modify, or do whatever you want with this "thingy"! If you encounter issues with the Cloudflare bypass in the source version, ensure your local FlareSolverr is up to date.

Enjoy browsing!
