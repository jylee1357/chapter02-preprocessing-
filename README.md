# chapter02-preprocessing-
```
#Don't forget to put two brackets! Otherwise, keyError...

Example)
away_data = pd.merge(uriage_data, kokyaku_data, left_on = "customer_name", right_on = "고객이름", how = "right")
away_data[away_data['purchase_date'].isnull()][['고객이름','등록일']]
```

#Converting int date(excel) to datetime format (python)

Example)
fromSerial = pd.to_timedelta(kokyaku_data.loc[flg_is_serial, '등록일'].astype("float") - 2, unit = "D") + pd.to_datetime("1900/01/01")
fromSerial
```
