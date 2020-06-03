# カレンダー(React)

<img width="600" alt="スクリーンショット 2020-06-04 1 06 27" src="https://user-images.githubusercontent.com/8656346/83660734-22aa0500-a600-11ea-9ea8-1c89cc248df9.png">

上部アイコンで翌月、先月に切替

<img width="600" alt="スクリーンショット 2020-06-04 1 06 52" src="https://user-images.githubusercontent.com/8656346/83660855-5422d080-a600-11ea-96d0-65b504ceea36.png">

Datepicker

<img width="600" alt="スクリーンショット 2020-06-04 1 08 13" src="https://user-images.githubusercontent.com/8656346/83660942-6f8ddb80-a600-11ea-99d2-50ab65ab9d8e.png">

CRUD

<img width="600" alt="スクリーンショット 2020-06-04 1 07 40" src="https://user-images.githubusercontent.com/8656346/83661013-85030580-a600-11ea-8272-af21754ea371.png">

<img width="457" alt="スクリーンショット 2020-06-04 1 13 57" src="https://user-images.githubusercontent.com/8656346/83661191-bb408500-a600-11ea-9e6c-fe02ff603245.png">


## セットアップ

```shell
$ make
```
OR
```shell
$ npm --prefix ./front install ./front
$ npm --cwd ./front run build
$ npm --prefix ./server install ./server
$ cp ./server/env/env-local ./server/.env
```

## サーバーの起動と停止

```shell
$ docker-compose up -d
$ docker-compose down
```

## 今後

TypeScriptを導入し型を付けていく
