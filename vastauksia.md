# H1 a (hakemusten kommentit)

```
>>> udf.loc[udf['action']=='add-comment'].groupby('applicationId').count()
                datetime  municipalityId  userId  role  action  target
applicationId                                                         
LP-1001-219067        17              17      17    17      17      17
LP-1001-223087        12              12      12    12      12      12
LP-1018-217443         4               4       4     4       4       4
LP-1021-215545         2               2       2     2       2       2
LP-1024-219662         3               3       3     3       3       3
LP-1025-224784         2               2       2     2       2       2
LP-1025-224789         3               3       3     3       3       3
LP-1058-218591        27              27      27    27      27      27
```


# M1 a (lupapiste käyttäjät käytönaikainen data)
```
>>> udf.userId.nunique()
71
```

# M2 a (lupapiste käyttäjät operatiivinen data)

```
>>> odf.applicationId.nunique()
10
```

 //wat mutta eihän tässä dataframessa edes ole mitään käyttäjiin liittyvää?
//tehty siis https://github.com/timole/solitadds-backend datalla