# Streaming CSV encryption demo

## Steps

```sh
npm i -g yarn
yarn install
yarn start

## open another shell, same dir
yarn test
```

## Default test csv

```csv
a,b,c,d,e,f,g,h,i,j
一二三四五六七八九十一二三四五六七八九十,一二三四五六七八九十一二三四五六七八九十,一二三四五六七八九十一二三四五六七八九十,一二三四五六七八九十一二三四五六七八九十,一二三四五六七八九十一二三四五六七八九十,一二三四五六七八九十一二三四五六七八九十,一二三四五六七八九十一二三四五六七八九十,一二三四五六七八九十一二三四五六七八九十,一二三四五六七八九十一二三四五六七八九十,一二三四五六七八九十一二三四五六七八九十
```

1,000,000 rows, ~583 MB csv file

## Results

```
1,000,000 rows 43.774s
```