
# 🔗 LINKS CONNECT - GitHub + Vercel + itch.io

GitHub Repo: https://github.com/montphu999-cyber/montphu-games-factory
GitHub Secrets: https://github.com/montphu999-cyber/montphu-games-factory/settings/secrets/actions
  - VERCEL_TOKEN (from https://vercel.com/account/tokens)
  - ITCH_API_KEY (from https://itch.io/user/settings/api-keys)
GitHub Actions: https://github.com/montphu999-cyber/montphu-games-factory/actions

Vercel:
  Hub: https://montphu-games-factory.vercel.app/
  Dashboard: https://vercel.com/dashboard
  Tokens: https://vercel.com/account/tokens
  Deploy Hooks: Vercel -> Project -> Settings -> Git -> Deploy Hooks

itch.io:
  Page: https://montphu.itch.io/
  Dashboard: https://itch.io/dashboard
  API Keys: https://itch.io/user/settings/api-keys
  Butler: https://itch.io/docs/butler/

Structure:
  games/team-a/ (12 Cozy/Tycoon) -> montphu.itch.io
  games/team-b/ (8 New Style) -> teamb.itch.io (separate)
  index.html -> Hub
  .github/workflows/deploy.yml -> Auto deploy both
