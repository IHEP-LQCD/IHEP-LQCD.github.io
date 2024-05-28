### Website of IHEP-LQCD Collaboration
#### instructions on updating the information
* new **activities** goes into the **_posts** directory, with markdown file named as *year-month-day-postname.md*
* new **news** goes into **_news** directory
* new **publications** will be added into *_bibliography/papers.bib* file
* new **projects** will be added into the **_projects** directory
* update and push the commits, the web will be deployed automatically
* preview the content with `bundler exec jekyll serve --watch --port=8080 --host=0.0.0.0 --livereload --verbose --trace`
