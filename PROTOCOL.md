# Protocol

## `POST /login`
Takes username and password, returns session ID.

## `POST /transfer`
Takes account ID [requires confirmation] or session ID [instant] of account money is coming from and account ID or session ID the money goes to. Returns a link to a page where the user can review the transfer.

## `GET /logout?id=:sessionid`
Takes session ID (because it's invalidated afterwards.

## `GET /balance?id=:accountid`
Gets the balance of account `accountid`.
