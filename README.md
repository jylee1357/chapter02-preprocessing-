# chapter02-preprocessing-
```
#Don't forget to put two brackets! Otherwise, keyError...

Example)
away_data = pd.merge(uriage_data, kokyaku_data, left_on = "customer_name", right_on = "고객이름", how = "right")
away_data[away_data['purchase_date'].isnull()][['고객이름','등록일']]
```
