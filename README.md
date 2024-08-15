# Travis_Test_Website
## Job Cycle 
Installation
install: skip
script: bundle exec thor build
script:
- bundle exec rake build
- bundle exec rake builddoc
- deploy:
  skip_cleanup: true
