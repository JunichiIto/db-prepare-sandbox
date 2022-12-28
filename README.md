# db-prepare-sandbox

```
git clone (this repositry)
cd db-prepare-sandbox 
bin/setup 
rails test
```

will display:

``` 
rails aborted!
ActiveRecord::EnvironmentMismatchError: You are attempting to modify a database that was last run in `development` environment.
You are running in `test` environment. If you are sure you want to continue, first set the environment using:

        bin/rails db:environment:set RAILS_ENV=test


Tasks: TOP => db:test:load => db:test:purge => db:check_protected_environments
(See full trace by running task with --trace)
Running 0 tests in a single process (parallelization threshold is 50)
Run options: --seed 54729

# Running:



Finished in 0.000382s, 0.0000 runs/s, 0.0000 assertions/s.
0 runs, 0 assertions, 0 failures, 0 errors, 0 skips
```
