# Checklists and Recs for Rails Applications

## Basics

* Rails 7.1+
* Include the default Dockerfile

## Development and Testing

* Use chrome-for-testing w/ selenium
* test with postgres locally
* 3 CI worflows:
    * rspec / unit tests
    * cucumber / integration tests (or just rspec features)
    * accessibility tests
* Rubocop + dedicated rubocop CI file.
    * Consider pronto w/ a GitHub runner for comments.

## Development Tools
* Use SMTP for all emails.
* letter_opener / letter_opener_web
* Setup rack-mini-profiler
* Use an omniauth dev login

## Front-End Assets

sigh...


## Recommended Gems / Tools

* DataTables / DataTables-AJAX
* axe-core / axe-core-cucumber / axe-core-rspec

## Ops Tasks
* Sentry Error Monitorying
* Lograge for logging [TBD, revisit 2025 options?]
* /heath_check endpoint and UCB's pinging service (TBD)
