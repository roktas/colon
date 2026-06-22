# Sodexo

`sodexo` switches between local Codex accounts stored in `~/.codex/accounts.json`.

The executable lives at `bin/sodexo`. It can list all stored accounts with status, show the active account, switch to an
account with available quota, and import the current Codex login into the account store.

The `CODEX_CLIENT_ID` constant is the public OAuth client id used by Codex CLI token refresh requests. It is not a
client secret. Account tokens and API keys stay in local `~/.codex` files and must not be committed.
