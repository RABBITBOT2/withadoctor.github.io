# 블로그

## 출처
https://mmistakes.github.io/minimal-mistakes/  
https://github.com/mmistakes/minimal-mistakes  

## 주소
https://withadoctor.github.io/

## 설치하는 방법. window는 링크 보고.
https://shryu8902.github.io/jekyll/jekyll-on-windows/

## 설치하는 방법. mac

루비 에러 링크 https://jojoldu.tistory.com/288  
brew install rbenv ruby-build  
rbenv versions  
rbenv install -l  
rbenv install 2.6.6  
rbenv global 2.6.6  
vim ~/.zshrc  

[[ -d ~/.rbenv  ]] && \  
  export PATH=${HOME}/.rbenv/bin:${PATH} && \  
  eval "$(rbenv init -)"  

source ~/.zshrc

gem install jekyll  
gem install minima  
gem install bundler  
gem install jekyll-feed  
gem install tzinfo-data  
bundle  
bundle exec jekyll serve  