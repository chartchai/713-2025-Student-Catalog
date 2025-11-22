# The Backend Student List

This is a simple, responsive web template for listing students. It is designed to be hosted on GitHub Pages.

## Project Structure

- `docs/`: Contains the website files. This folder is used for GitHub Pages deployment.
    - `index.html`: The main HTML file.
    - `style.css`: The CSS styles.
    - `assets/`: Folder containing images (avatars).

## How to Add Your Information

1.  **Clone the repository** to your local machine.
2.  Open `docs/index.html` in a text editor.
3.  Find the table body (`<tbody>`) section.
4.  **Copy** the example row (or the commented-out template row).
```html
<tr>
    <td data-label="Avatar" class="avatar-cell">
        <img src="assets/avatar_placeholder.png" alt="New Student Avatar" class="avatar-img">
    </td>
    <td data-label="Student ID">ID Here</td>
    <td data-label="Name Surname">Name Here</td>
    <td data-label="Nickname">Nickname Here</td>
</tr>
```
5.  **Paste** it as a new row in the table.
6.  **Update** the details:
    - **Avatar**: Add your image to `docs/assets/` and update the `src` attribute (e.g., `assets/your_image.jpg`).
    - **Student ID**: Enter your 10-digit student ID.
    - **Name Surname**: Enter your full name.
    - **Nickname**: Enter your nickname.
7.  **Save** the file.

## How to Deploy

1.  **Commit** your changes:
    ```bash
    git add .
    git commit -m "Add student [Your Name]"
    ```
2.  **Push** to the repository:
    ```bash
    git push origin main
    ```
3.  Ensure GitHub Pages is configured to serve from the `/docs` folder in the repository settings.
