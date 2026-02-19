# Spree Commerce Deployment

**Live Store:** http://3.111.217.91:3000
**Admin Panel:** http://3.111.217.91:3000/admin

## Status
- EC2 Ubuntu 22.04
- MySQL 8.0 + spree_development  
- Ruby 3.2 + Rails 7.1
- Spree Commerce 5.x
- 46/47 migrations complete

## Quick Start
```bash
bundle install
bundle exec rails db:migrate
bundle exec rails db:seed
bundle exec rails server -b 0.0.0.0

