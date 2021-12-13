サイト: (Dockerを利用して、React実行環境を簡単に構築する)[https://www.cloudnotes.tech/entry/react_docker]

■ Docker Images作成

```
docker-compose build
```

■ React Project作成 

```
docker-compose run --rm node sh -c "npx create-react-app <project_name> --use-npm"
```

■React 起動

```
docker-compose up
```

※プロジェクト名に応じてcommandのフォルダ名の部分を変更してください。
> command: sh -c "cd reactapp && npm start"
    
