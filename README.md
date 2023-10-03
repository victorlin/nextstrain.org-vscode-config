UPDATE: I just realized this isn't necessary. VSCode can run the NPM script (e.g. `npm run dev`) through the Run and Debug view. It automatically attaches the debugger.

This repository provides VSCode configuration files for local development of
nextstrain.org.

Commands to add the configuration files to a local copy of nextstrain.org:

    git remote add vscode-config https://github.com/victorlin/nextstrain.org-vscode-config
    git fetch vscode-config
    git checkout vscode-config/main .vscode/
    git restore --staged .vscode/
