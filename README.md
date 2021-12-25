# No-Code API with GitHub Pages

A template for creating a read-only API from a CSV file and hosting it on GitHub Pages
{: .f2}

## How it works

1. Create a copy of this repo template.
2. Replace `mydata.csv` with your data.
3. Publish to GitHub Pages.

Your data is published as a JSON file that you can use to pull content into your apps and design tools.

## More details

### Create a copy of this repo template

- On the code tab, press the `Use this template` button.
- You will be prompted to create a new repository under your account.

### Replace `mydata.csv` with your data

- The `mydata.csv` file is located in the `_data` folder.
- This file contains example data you can test with your repo.
- To replace the data, you can copy and paste text comma-separated-value format over the existing text or you can replace the whole file.
- To keep things simple, name your file "mydata.csv" and replace the existing one.
- If you want to use a different filename, update the `data-file-name` setting in the `_config.yml` file. (Note: Don't include the `.csv` extension in the setting; just the filename.)

### Publish to GitHub Pages

- Under the Settings, go to Pages.
- Set the source to `main` and press `Save`.
- After a few minutes your site will be live at the displayed URL.
- The homepage will show the basic information about this tool.
- The URL of the JSON file is `http://YOUR-GITHUB-ACCOUNT/YOUR-REPO-NAME/api.json`.

## Credit and license
This project was created primarily using the [GitHub Pages gem for Jekyll](https://github.com/github/pages-gem) and a slightly modified [HTML5 Boilerplate](https://github.com/h5bp/html5-boilerplate). It is licensed under [The Unlicense](https://github.com/pglevy/plain-vanilla-gh-pages/blob/main/LICENSE), which allows everything and promises nothing. 😎
