# SimpleDiscuss
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FSamuNatsu%2FSimpleDiscuss.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2FSamuNatsu%2FSimpleDiscuss?ref=badge_shield)

A simple discussion forum system

## Configuring
1. Edit "config.php", configured database info
2. Create a database according to what you configured in step 1
3. Execute "reset.php" to get reset token in newly created file "reset_token.php"
4. Execute "reset.php" with query string "?token=(Token in 'reset_token.php')", database will be automatically initialized


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FSamuNatsu%2FSimpleDiscuss.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2FSamuNatsu%2FSimpleDiscuss?ref=badge_large)