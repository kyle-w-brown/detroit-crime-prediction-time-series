# Detroit Crime Time Series Data

This data reflects reported criminal offenses that have occurred in the City of Detroit. Offense data was extracted from the Detroit Police Department's records management system.


The `RMS_Incidents_Report.csv` data can be located at Detroit Open Data website or 
[here](https://data.detroitmi.gov/datasets/detroitmi::rms-crime-incidents/explore?location=42.366192%2C-83.084823%2C10.35).

*The remaining files were prepared for Time Series purposes*

<br>

## `Incident_Timestamp` Crime Totals

```python
incident_timestamp.head()
```

| incident_timestamp  | number_of_crimes |
| :-----------------: | :--------------: |	
| 2017-01-01 05:00:00 |	      1          |
| 2017-01-01 05:15:00	|       1          |
| 2017-01-01 05:20:00	|       2          |
| 2017-01-01 05:30:00	|       3          |
| 2017-01-01 06:00:00	|       3          |


<br>

```python
incident_timestamp.tail()
```
| incident_timestamp  | number_of_crimes |
| :-----------------: | :--------------: |	
| 2022-12-31 12:20:00	|        1         |
| 2022-12-31 12:30:00	|        2         |
| 2022-12-31 12:45:00	|        1         |
| 2022-12-31 12:50:00	|        1         |
| 2022-12-31 12:59:00	|        1         |


<br>

## Hourly Crime Totals

```python
hourly_crime_totals.head()
```

| incident_timestamp  | number_of_crimes |
| :-----------------: | :--------------: |
|  2017-01-01 05:00	  |        7         |
|  2017-01-01 06:00	  |        6         |
|  2017-01-01 07:00	  |        14        |
|  2017-01-01 08:00	  |        6         |
|  2017-01-01 09:00	  |        11        |

<br>

```python
hourly_crime_totals.tail()
```

| incident_timestamp  | number_of_crimes |
| :-----------------: | :--------------: |
| 2022-12-31 08:00:00	|       16         |
| 2022-12-31 09:00:00	|        8         |   
| 2022-12-31 10:00:00	|       15         |
| 2022-12-31 11:00:00	|        8         |
| 2022-12-31 12:00:00	|        9         |

<br>

## Hourly Crime Averages

```python
hourly_crime_avg.head()
```

| incident_timestamp  | number_of_crimes |
| :-----------------: | :--------------: |
|  2017-01-01 05:00	  |        7         |
|  2017-01-01 06:00	  |        6         |
|  2017-01-01 07:00	  |        14        |
|  2017-01-01 08:00	  |        6         |
|  2017-01-01 09:00	  |        11        |

<br>

```python
hourly_crime_avg.tail()
```

| incident_timestamp  | number_of_crimes |
| :-----------------: | :--------------: |
| 2022-12-31 08:00:00	|       16         |
| 2022-12-31 09:00:00	|        8         |   
| 2022-12-31 10:00:00	|       15         |
| 2022-12-31 11:00:00	|        8         |
| 2022-12-31 12:00:00	|        9         |


<br>

## Daily Crime Totals

```python
daily_crime_totals.head()
```

| incident_timestamp  | number_of_crimes |
| :-----------------: | :--------------: |
|    2017-01-01	      |       311        |
|    2017-01-02	      |       239        |
|    2017-01-03	      |       207        |
|    2017-01-04	      |       218        |
|    2017-01-05	      |       182        |

<br>

```python
daily_crime_totals.tail()
```

| incident_timestamp  | number_of_crimes |
| :-----------------: | :--------------: |
|     2022-12-27	    |       166        |
|     2022-12-28	    |       169        |
|     2022-12-29	    |       197        |
|     2022-12-30	    |       193        |
|     2022-12-31	    |       142        |

<br>

## Daily Crime Average

```python
daily_crime_avg.head()
```

| incident_timestamp  |    avg_crimes    |
| :-----------------: | :--------------: |
|     2017-01-01	    |      14.29       |
|     2017-01-02	    |       9.96       |
|     2017-01-03	    |       8.62       |
|     2017-01-04	    |       9.08       |
|     2017-01-05	    |       7.58       |

<br>

```python
daily_crime_avg.tail()
```

| incident_timestamp  |    avg_crimes    |
| :-----------------: | :--------------: |
|      2022-12-27	    |       6.92       |
|      2022-12-28	    |       7.04       |
|      2022-12-29	    |       8.21       |
|      2022-12-30	    |       8.04       |
|      2022-12-31	    |      10.92       |

<br>

## Weekly Crime Totals

```python
weekly_crime_totals.head()
```

| incident_timestamp  | number_of_crimes |
| :-----------------: | :--------------: |
|    2017-01-02	      |       1343       |
|    2017-01-09	      |       1410       |
|    2017-01-16	      |       1376       |
|    2017-01-23	      |       1465       |
|    2017-01-30       |     	1373       |

<br>

```python
weekly_crime_totals.tail()
```
| incident_timestamp  | number_of_crimes |
| :-----------------: | :--------------: |
|     2022-11-28	    |      1667        |
|     2022-12-05	    |      1781        |
|     2022-12-12	    |      1574        |
|     2022-12-19	    |      1311        |
|     2022-12-26	    |      1019        |

<br>

## Weekly Crime Averages

```python
weekly_crime_avg.head()
```

| incident_timestamp  |    avg_crimes    |
| :-----------------: | :--------------: |
|     2017-01-02      |	     191.86      |
|     2017-01-09      |	     201.43      |
|     2017-01-16      |	     196.57      |
|     2017-01-23      |    	 209.29      |
|     2017-01-30	    |      196.14      |

<br>

```python
weekly_crime_avg.tail()
```
| incident_timestamp  |     avg_crimes   |
| :-----------------: | :--------------: |
|     2022-11-28	    |      238.14      |
|     2022-12-05	    |      254.43      |
|     2022-12-12	    |      224.86      |
|     2022-12-19	    |      187.29      |
|     2022-12-26	    |      169.83      |

<br>

## Monthly Crime Totals

```python
monthly_crime_totals.head()
```

| incident_timestamp  | number_of_crimes |
| :-----------------: | :--------------: |
|     2017-01-01      |    	6244         |
|     2017-02-01	    |     5770         |
|     2017-03-01	    |     6582         |
|     2017-04-01	    |     6838         |
|     2017-05-01	    |     7315         |

<br>

```python
monthly_crime_totals.tail()
```

| incident_timestamp  | number_of_crimes |
| :-----------------: | :--------------: |
|     2022-08-01	    |      7647        |
|     2022-09-01	    |      7561        |
|     2022-10-01	    |      7592        |
|     2022-11-01	    |      7215        |
|     2022-12-01	    |      6635        |

<br>

## Monthly Crime Averages

```python
monthly_crime_avg.head()
````

| incident_timestamp  |     avg_crimes   |
| :-----------------: | :--------------: |
|     2017-01-01	    |      201.42      |
|     2017-02-01	    |      206.07      |
|     2017-03-01	    |      212.32      | 
|     2017-04-01	    |      227.93      |
|     2017-05-01	    |      235.97      |

<br>

```python
monthly_crime_avg.tail()
```
| incident_timestamp  |     avg_crimes   |
| :-----------------: | :--------------: |
|     2022-08-01	    |      246.68      |
|     2022-09-01	    |      252.03      |
|     2022-10-01	    |      244.90      |
|     2022-11-01	    |      240.50      |
|     2022-12-01	    |      214.03      |

