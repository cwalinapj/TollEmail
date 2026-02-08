TollEmail/
  README.md
  LICENSE
  docker-compose.yml
  .env.example

  smtp/
    Dockerfile
    postfix/   (or haraka/)
    srs/       (sender rewriting config)
    scripts/

  policy-service/
    package.json
    src/
      server.ts          # /email/policy, /quarantine, /release, /settings
      risk/
      ledger/
      auth/
    test/

  wp-plugin/
    toll-email-forwarding/   # optional later (admin UI on WP)
  
  packages/
    credits-client/          # thin client for credits coordinator (optional)
  
  docs/
    TOLLEMAIL_MVP.md
    DELIVERABILITY.md
    RISK_SCORING.md
    LEDGER_SCHEMA_EMAIL.md
