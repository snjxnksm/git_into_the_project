# git_into_the_project
Introducing Git into the project


## インストール

asciidoctorなどをローカルにインストールする。 
 > bundle install --path vender/bundler

## html出力
 > bundle exec asciidoctor GitIntoProject.adoc

## pdf出力
 > bundle exec asciidoctor-pdf GitIntoProject.adoc

## スライドの出力

pythonを入れて、cdk入れて、htmlでだす。

1. pythonインストール

 > brew install python3
2. pip3でCDKインストール
 > pip3 install cdk
3. cdkでhtmlを出力

 > cdk GitIntoProject.adoc
 
 > mv GitIntoProject.html index.html
