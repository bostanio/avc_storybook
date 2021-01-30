# ViewComponent::Storybook Example
This project demonstrates [Storybook Server](https://github.com/storybookjs/storybook/) running using Stories and [ViewComponents](https://github.com/github/view_component) generated by [ViewComponent::Storybook](https://github.com/jonspalmer/view_component_storybook).

## Ruby Version
Use your favorite Ruby version manager to install 2.7.2

## Install Gems and Node modules
```bash
bundle install
yarn
```

## Genrate the Strobook stories JSON
```bash
rake view_component_storybook:write_stories_json
```

## Run the Rails backend:

```bash
rails s
```
This starts a Rails dev server on port 3000.

## Run Storybook
To view the stories in the storybook UI:

```bash
yarn storybook
```

This runs the Storybook dev server loading stories from the Rails endpoint
