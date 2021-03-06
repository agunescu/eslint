v0.0.7 - July 22, 2013

* 0.0.7 (Nicholas C. Zakas)
* Add code coverage checks to npm test and update rule tests to have better coverage (Nicholas C. Zakas)
* Merge pull request #39 from jamesallardice/rule-missing-radix (Nicholas C. Zakas)
* Merge pull request #88 from mduvall/optional-args-for-rule (Nicholas C. Zakas)
* Merge pull request #106 from iancmyers/fix-cli-results (Nicholas C. Zakas)
* Merge pull request #105 from goatslacker/rm-maxlen (Nicholas C. Zakas)
* Fixed CLI output on serial programatic executions (Ian Christian Myers)
* Removes line length from code style convention docs (Josh Perez)
* Merge pull request #98 from goatslacker/templates (Nicholas C. Zakas)
* Merge pull request #97 from goatslacker/dot-notation (Nicholas C. Zakas)
* Adds escapeRegExp and fixes documentation (Josh Perez)
* Add quotes rule and test coverage for configuration options (Matt DuVall)
* Adds templating for lint messages and refactors rules to use it (Josh Perez)
* Fixes lint rules for unchecked test file (Josh Perez)
* Changes dotnotation rule to match JSHint style (Josh Perez)
* Change configInfo to options and add test coverage (Matt DuVall)
* Merge branch 'master' of https://github.com/nzakas/eslint into optional-args-for-rule (Matt DuVall)
* Adds dot notation lint rule (Josh Perez)
* Merge pull request #83 from mamacdon/new-parens-func-fix (Nicholas C. Zakas)
* Merge pull request #96 from qmx/ml (Nicholas C. Zakas)
* Merge pull request #95 from captainbrosset/camelcase (Nicholas C. Zakas)
* Strip trailing underscores in camelcase rule - Fixes #94 (Patrick Brosset)
* add mailing list link (Douglas Campos)
* Strip leading underscores in camelcase rule - Fixes #94 (Patrick Brosset)
* Merge pull request #87 from iancmyers/rule-no-dangle (Nicholas C. Zakas)
* Merge pull request #85 from ilyavolodin/no-new-func (Nicholas C. Zakas)
* Merge pull request #92 from jamesallardice/rule-no-implied-eval (Nicholas C. Zakas)
* Created no-dangle rule. (Ian Christian Myers)
* Merge pull request #89 from iancmyers/fix-config-option (Nicholas C. Zakas)
* Merge pull request #24 from mduvall/rule-fall-through (Nicholas C. Zakas)
* Merge pull request #91 from spmurrayzzz/master (Nicholas C. Zakas)
* Fixed rule name (James Allardice)
* Make sure the callee type is Identifier (James Allardice)
* Add rule for implied eval via setTimeout/Interval (James Allardice)
* Fix rule name in config (James Allardice)
* Fixes #90 -- updates docstrings (Stephen Murray)
* Fixes issue with fs.existsSync on NodeJS 0.6 (Ian Christian Myers)
* Fixing -c config option. (Ian Christian Myers)
* Allow arrays to be passed as multiple args to rule (Matt DuVall)
* Test to make sure empty case with one line break is safe (Matt DuVall)
* Rule: The Function constructor is eval (Ilya Volodin)
* Merge pull request #80 from iancmyers/fix-require (Nicholas C. Zakas)
* Enabled require("eslint") and exposed out CLI. (Ian Christian Myers)
* Merge pull request #73 from iancmyers/rule-one-true-brace (Nicholas C. Zakas)
* Merge pull request #71 from Constellation/estraverse-controller (Nicholas C. Zakas)
* Adds test and fix for issue #82 (Mark Macdonald)
* Merge branch 'master' of https://github.com/nzakas/eslint into ok (Yusuke Suzuki)
* Created brace-style rule. (Ian Christian Myers)
* Merge pull request #81 from xjamundx/multi-formatters (Nicholas C. Zakas)
* Formatters can now process multiple files at once (Jamund Ferguson)
* Merge pull request #79 from ilyavolodin/no-new (Nicholas C. Zakas)
* Merge pull request #75 from goatslacker/smarter-eqeqeq-rule (Nicholas C. Zakas)
* Merge pull request #67 from jedhunsaker/editorconfig (Nicholas C. Zakas)
* Rule: Do not use 'new' for side effects (Ilya Volodin)
* Adds smarter-eqeqeq rule (Josh Perez)
* Merge pull request #72 from mamacdon/no-octal-0 (Nicholas C. Zakas)
* Add EditorConfig file for consistent editor/IDE behavior (Jed Hunsaker)
* Merge pull request #74 from jrfeenst/master (Nicholas C. Zakas)
* Fix the positive case for no-unreachable where there is no return statement at all, or if the return is at the end. Those cases should not return any errors. The error condition was not be checked before throwing the rule error. (Joel Feenstra)
* Adds test and fix for no-octal on 0 literal (Mark Macdonald)
* Don't report no-empty warnings when a parent is FunctionExpression / FunctionDeclaration (Yusuke Suzuki)
* Add api.getAncestors (Yusuke Suzuki)
* Ensure estraverse version 1.2.0 or later (Yusuke Suzuki)
* Merge pull request #62 from goatslacker/fix-no-alert (Nicholas C. Zakas)
* Merge pull request #61 from goatslacker/dont-die-on-undefined (Nicholas C. Zakas)
* Merge pull request #60 from goatslacker/fix-octal-check (Nicholas C. Zakas)
* Fixes no-alert lint rule for non identifier calls (Josh Perez)
* Fixes exception when init is null (Josh Perez)
* Fixes no-octal check to only check for numbers (Josh Perez)
* 0.0.7-dev (Nicholas C. Zakas)
* 0.0.6 (Nicholas C. Zakas)
* Follow the rule naming conventions (James Allardice)
* Add rule for missing radix argument to parseInt (James Allardice)
* Allow return, falls-through comment, and throw for falls-through (Matt DuVall)
* Merge branch 'master' of https://github.com/nzakas/eslint into rule-fall-through (Matt DuVall)
* Globals are not good, declare len (Matt DuVall)
* Rule to add no-fall-through (Matt DuVall)

v0.0.6 - July 16, 2013

* 0.0.6 (Nicholas C. Zakas)
* Changed semi rule to use tokens instead of source (Nicholas C. Zakas)
* Merge pull request #49 from ilyavolodin/ctor-parentheses (Nicholas C. Zakas)
* Merge pull request #51 from ilyavolodin/no-ctor (Nicholas C. Zakas)
* Renaming new-parens rule (Ilya Volodin)
* Merge pull request #55 from nschonni/add-license-url (Nicholas C. Zakas)
* Renaming no-new-wrappers rule and adding tests (Ilya Volodin)
* Add license URL (Nick Schonning)
* Merge pull request #54 from nschonni/remove-unused-variables (Nicholas C. Zakas)
* Remove unused sinon requires (Nick Schonning)
* Merge pull request #52 from nschonni/remover-redundant-jshint-directives (Nicholas C. Zakas)
* Merge pull request #50 from nschonni/add-node-unstable-to-travis (Nicholas C. Zakas)
* Remove redundant JSHint directives (Nick Schonning)
* Rule: Do not use constructor for wrapper objects (Ilya Volodin)
* Test node 0.11 unstable but allow it to fail (Nick Schonning)
* Rule: Constructor should use parentheses (Ilya Volodin)
* Merge pull request #46 from andzdroid/master (Nicholas C. Zakas)
* Merge pull request #47 from puffnfresh/master (Nicholas C. Zakas)
* Fix reference to "CSS Lint" in Contributing documentation (Brian McKenna)
* Add git attributes file for line endings (Andy Hu)
* Merge pull request #42 from evangoer/add_docs_dir (Nicholas C. Zakas)
* Rename to create an 'index' file in GH web view (Evan Goer)
* Avoid accidentally creating a markdown link (Evan Goer)
* Add headings and correct internal links (Evan Goer)
* Add wiki files to docs directory (Evan Goer)
* Merge pull request #35 from ilyavolodin/no-octal (Nicholas C. Zakas)
* Merge pull request #38 from jamesallardice/rule-no-floating-decimal (Nicholas C. Zakas)
* Merge pull request #37 from jamesallardice/rule-use-isnan (Nicholas C. Zakas)
* Add rules for leading/trailing decimal points (James Allardice)
* Add rule to prevent comparisons with value NaN (James Allardice)
* Fixing jshint error (Ilya Volodin)
* Rule: no octal literals (Ilya Volodin)
* Merge pull request #34 from ilyavolodin/no-undef-init (Nicholas C. Zakas)
* Rule: no undefined when initializing variables (Ilya Volodin)
* Updated CONTRIBUTING.md (Nicholas C. Zakas)
* Make sure namespaces are honored in new-cap (Nicholas C. Zakas)
* Make sure no-empty also checks for ';;' (Nicholas C. Zakas)
* Add CLI option to output version (Nicholas C. Zakas)
* Updated contribution guidelines (Nicholas C. Zakas)
* Merge pull request #26 from jrfeenst/master (Nicholas C. Zakas)
* Fixing jshint complaints. (Joel Feenstra)
* Converting to a switch statement and declaring variables. (Joel Feenstra)
* Added .jshintrc file (until ESLint can lint itself) and cleaned up JSHint warnings (Nicholas C. Zakas)
* Merge branch 'master' of github.com:nzakas/jscheck (Nicholas C. Zakas)
* A bit of cleanup (Nicholas C. Zakas)
* Add unreachable code detection for switch cases and after continue/break. (Joel Feenstra)
* Add support for detecting unreachable code after a throw or return statement. (Joel Feenstra)
* Merge pull request #25 from jrfeenst/master (Nicholas C. Zakas)
* Fix curly brace check when an if statement is the alternate. (Joel Feenstra)
* Merge pull request #23 from mduvall/check-empty-switch-statements (Nicholas C. Zakas)
* Merge pull request #22 from mduvall/verify-file-path (Nicholas C. Zakas)
* Check for empty switch statements with no cases. (Matt DuVall)
* Added CONTRIBUTING.md (Nicholas C. Zakas)
* Added rule to check for missing semicolons (fixes #9) (Nicholas C. Zakas)
* Verify that file paths exist before reading the file (Matt DuVall)
* Added guard-for-in rule (fixes #1) (Nicholas C. Zakas)
* Run linting with npm test as well (Nicholas C. Zakas)
* Removed foo.txt (Nicholas C. Zakas)
* Updated config file with new no-caller ID (Nicholas C. Zakas)
* Changed name of no-arg to no-caller (Nicholas C. Zakas)
* Increased test coverage (Nicholas C. Zakas)
* Got npm test to work with istanbul, huzzah\! (Nicholas C. Zakas)
* Moved /config to /conf (Nicholas C. Zakas)
* Added script to auto-generate changelog (Nicholas C. Zakas)
* Merge pull request #17 from mathiasbynens/quote-props (Nicholas C. Zakas)
* Add `quote-props` rule (Mathias Bynens)
* Cleaned up relationship between bin/eslint, lib/cli.js, and lib/eslint.js (Nicholas C. Zakas)
* Add problem count to compact formatter (Nicholas C. Zakas)
* Fix merge conflict (Nicholas C. Zakas)
* Change reporters to formatters, add format command line option. Also added tests for compact format. (Nicholas C. Zakas)
* Change reporters to formatters, add format command line option (Nicholas C. Zakas)
* Start development of 0.0.6-dev (Nicholas C. Zakas)

