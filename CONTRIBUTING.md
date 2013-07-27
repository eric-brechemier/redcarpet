## Submitting a Pull Request

1. [Fork the repository.][fork]
2. [Create a topic branch.][branch]
3. [Install RVM.][rvm]
4. Install ruby 1.9.3:

        rvm install 1.9.3
        rvm use 1.9.3 --default
        ruby --version

5. [Install bundler.][bundler]
6. Check that unit tests pass:

        rake test

7. Write a failing test to capture existing bug or lack of feature.
8. Run `rake test` to verify that test fails.
9. Implement your feature or bug fix.
10. Ensure tests pass.
11. If it's a new feature or a bug fix,
    please add an entry to the changelog file.
12. Add, commit, and push your changes.
13. [Submit a pull request.][pr]

[fork]: https://help.github.com/articles/fork-a-repo
[branch]: http://learn.github.com/p/branching.html
[pr]: https://help.github.com/articles/using-pull-requests

[rvm]: https://rvm.io/rvm/install
[bundler]: http://bundler.io/#getting-started

