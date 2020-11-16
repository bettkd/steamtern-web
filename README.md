# steamtern-web
Web Application for STEAMtern

Homepage: https://bettkd.github.io/steamtern-web

GH PAGES: https://www.youtube.com/watch?v=SKXkC4SqtRk&ab_channel=TraversyMedia

install: 
    - ```npm init```
    - ```npm i gh-pages```
    - on package.json, update homepage to https://bettkd.github.io/steamtern-web
    - on package.json > scripts, add ``` "deploy": "gh-pages -d {DIR WITH index.html}" ```

deploy:
    - push to github
    - ```snpm run deploy```