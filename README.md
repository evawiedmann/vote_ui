# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

## Lee's notes

* session_store.rb not doing anything right now

* sucker_punch gem for asynchronous background jobs probably not the best for high-load applications

#### working

* user auth

* each user session now unique

* throttling - for ddos and brute-force password attacks

* better email verification

#### to do?

* automatic timeout

* no need to refresh for new messages

* handle weird exceptions
