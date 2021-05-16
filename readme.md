# Awesome List Template

This is an [awesome-list](https://github.com/sindresorhus/awesome) template with CI to run [awesome-lint](https://github.com/sindresorhus/awesome-lint) and [awesome_bot](https://github.com/dkhamsing/awesome_bot) to be compliant from the beginning.

## Usage

1. [generate a template of this repo](https://github.com/jthegedus/awesome-list-template/generate)
2. edit `readme-template.md`
   - update the h1 title
   - update the subtitle
   - update the description
   - add img src, make it link to the site of the thing in the image. uncomment the img code.
   - update `TODO_YOUR_REPO_NAME_HERE` in the "contributors" link and uncomment the line
3. edit `code_of_conduct.md`
   - update `TODO_INSERT_YOUR_EMAIL_HERE`
4. edit `contributing.md`
   - update `TODO_YOUR_REPO_NAME_HERE`
5. choose a CI template
   - github action: move config folver from `repo-root/ci/.github/` to `repo-root/.github`
   - circle ci: move config folder from `repo-root/ci/.circleci/*` to `repo-root/.circleci/*`
   - gitlab ci: move config file from `repo-root/ci/.gitlab-ci.yml` to the `repo-root/.gitlab-ci.yml`
6. delete this file
7. rename `readme-template.md` to `readme.md`

## Contributing

Contributions welcome!
