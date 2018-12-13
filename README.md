

[Nikola Tutorials](https://getnikola.com/getting-started.html)


```
pipenv shell
pipenv install --upgrade pip setuptools wheel
pipenv install --upgrade "Nikola[extras]"
nikola theme -i hyde
nikola init .
nikola new_post -f ipynb
nikola auto
nikola github_deploy
```

[pipenv 가상환경 설명](https://graspthegist.com/post/python-pipenv/)
[Blog글](https://partrita.github.io/posts/nikola-for-jupyer-blog/)

수정 잘 되는가?