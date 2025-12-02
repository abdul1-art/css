# VS Code — Workspace Autocomplete & Assistance Setup ✅

This workspace now contains a few files that help VS Code give you "lanjutan" (continuation) and assisted autocompletions for HTML/CSS development:

- `.vscode/extensions.json` — suggested extensions (Copilot, TabNine, IntelliCode, Live Server, Prettier, etc.)
- `.vscode/settings.json` — workspace settings tuned for better suggestions, inline suggestions, snippets and format-on-save
- `.vscode/html.code-snippets` and `.vscode/css.code-snippets` — useful snippets for faster coding

## How to enable these features on your machine

1. Open this project folder in VS Code.
2. VS Code will show a popup recommending extensions to install. Click "Install" for the extensions you want.

If you prefer to install via the terminal you can use the VS Code CLI (replace IDs below with the ones you choose):

```powershell
# Example - install Live Server and Prettier
code --install-extension ritwickdey.LiveServer
code --install-extension esbenp.prettier-vscode
# Optional AI helpers (sign in after install):
code --install-extension github.copilot
code --install-extension TabNine.tabnine-vscode
code --install-extension VisualStudioExptTeam.vscodeintellicode
```

## Notes and tips

- GitHub Copilot and TabNine require signing in and sometimes subscriptions — follow the extension UI after installing.
- Use `html5` in an `.html` file to expand the HTML5 boilerplate snippet.
- Use `asiknest` to insert the nested `.asik` layout; use `boxstack` for `.box2/.box3` blocks.
- CSS snippets: try `center-flex`, `container-rc`, `box-shadow` and `padmar` while editing `.css` files.

## Want more automation?

- I can add more project-specific snippets and keyboard shortcuts, or configure a dev container so your environment is reproducible. If you'd like that, tell me what else you'd like automated (formatting rules, linting, keyboard shortcuts, or dev container).

Enjoy — this should make writing HTML/CSS faster and more "automatic" ✨
