# Contributing guidelines

## Before contributing

Welcome to [geekquad/Image-Processing-OpenCV](https://github.com/geekquad/AlgoBook). Before sending your pull requests, make sure that you **read the whole guidelines**.


* Make sure you do not copy codes from external sources because that work will not be considered. Plagiarism is strictly not allowed.
* You can only work on issues that you have been assigned to you.
* If you want to contribute for an existing algorithm, we prefer that you create an issue before making a PR and link your PR to that issue.
* If you have modified/added code work, make sure the code compiles before submitting.

### Contribution

We appreciate any contribution, from fixing a grammar mistake in a comment to implementing complex algorithms. Please read this section if you are contributing your work.

#### Coding Style

We want your work to be readable by others; therefore, we encourage you to note the following:

- Follow PEP8 guidelines. Read more about it <a href="https://pep8.org/"> here. </a>
- Please write in Python 3.7+.  __print()__ is a function in Python 3 so __print "Hello"__ will _not_ work but __print("Hello")__ will.
- Please focus hard on naming of functions, classes, and variables.  Help your reader by using __descriptive names__ that can help you to remove redundant comments.
  - Please follow the [Python Naming Conventions](https://pep8.org/#prescriptive-naming-conventions) so variable_names and function_names should be lower_case, CONSTANTS in UPPERCASE, ClassNames should be CamelCase, etc.
  - Expand acronyms because __gcf()__ is hard to understand but __greatest_common_factor()__ is not.

- Using only OpenCV modules are highly recommended.
- Avoid importing external libraries for basic algorithms. Only use those libraries for complicated algorithms.
- If you need a third party module that is not in the file __requirements.txt__, please add it to that file as part of your submission.

#### Other points to remember while submitting your work:
- **We won't be accepting just the dataset in the form of PRs.** If you are using any of the dataset in the implementation, then only we'll accept it.
- Jupyter notebook files should be there with proper step-wise implementation.
- Each file should be added with a dedicated README.md so that it gets easier for people to know your approach and the logic behind.
- File extension for code should be `.py`. 
- Strictly use snake_case (underscore_separated) in your file_name, as it will be easy to parse in future using scripts.
- Please avoid creating new directories if at all possible. Try to fit your work into the existing directory structure. If you want to. Please contact us on our <a href="https://join.slack.com/t/geekquad/shared_invite/zt-l3t67zvr-JMKbn57PpxjEi7uC2k0etg"> Slack </a> channel.
- If you have modified/added code work, make sure the code compiles before submitting.
- If you have modified/added documentation work, ensure your language is concise and contains no grammar errors.
- Do not update the README.md and CONTRIBUTING.md.

**Join our <a href="https://join.slack.com/t/geekquad/shared_invite/zt-l3t67zvr-JMKbn57PpxjEi7uC2k0etg"> Slack </a> channel now.**
Happy Coding :)

