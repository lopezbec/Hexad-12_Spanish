README
================

Download that from GitHub Repo: <https://github.com/>

    ##    X philanthropist socializer freeSpirit achiever player disruptor A2 A4 D3 D4
    ## 1  4             14         14         13       14      7         7  7  7  6  1
    ## 2  5             14         14         14       14     14         2  7  7  1  1
    ## 3  6             13         10         11        9     13        10  3  6  4  6
    ## 4  7             13          2         14        9      2         5  5  4  4  1
    ## 5  9             13          6         13       13      6         7  6  7  6  1
    ## 6 12             14         14         14       14     14        10  7  7  5  5
    ##   F1 F3 P1 P4 R2 R4 S2 S4 Completion.Time Age Gender
    ## 1  6  7  7  7  5  2  7  7          85.868  75   <NA>
    ## 2  7  7  7  7  7  7  7  7          75.567  NA   <NA>
    ## 3  5  6  7  6  7  6  6  4          42.281  NA   <NA>
    ## 4  7  7  7  6  1  1  1  1          66.028  69 female
    ## 5  6  7  7  6  1  5  1  5          91.748  72 female
    ## 6  7  7  7  7  7  7  7  7          41.451  65 female
    ##                                Country                        Education
    ## 1                                                                      
    ## 2                                                                      
    ## 3                                                                      
    ## 4                            Argentina Technical or vocational training
    ## 5 Venezuela (República Bolivariana de)              Professional degree
    ## 6                            Argentina                                 
    ##   Freq.Games
    ## 1          1
    ## 2         NA
    ## 3         NA
    ## 4          7
    ## 5          7
    ## 6         NA

# 4. Results

## 4.2. Sample descriptives

### Number of Participants

Each row represents a data point from a single participant. Total number of participants

    ## [1] 866

### Completion Time Summary statistics

| Statistic          |  Value |
|:-------------------|-------:|
| Average            |  69.33 |
| Median             |  64.27 |
| Min                |  30.38 |
| Max                | 143.52 |
| Standard Deviation |  23.52 |
| Non-Empty Rows     | 866.00 |

Summary Statistics for Completion Time

### Age Summary statistics

| Statistic          |  Value |
|:-------------------|-------:|
| Average            |  37.89 |
| Median             |  32.00 |
| Min                |  18.00 |
| Max                |  87.00 |
| Standard Deviation |  17.25 |
| Non-Empty Rows     | 737.00 |

Summary Statistics for Age

### Gender Summary statistics

| Gender | Count | Percentage |
|:-------|------:|:-----------|
| female |   369 | 58.76%     |
| male   |   256 | 40.76%     |
| other  |     3 | 0.48%      |
| Total  |   628 | 100%       |

Summary of Gender Distribution with Totals

### Education Level Summary statistics

| EducationLevel                   | Count | Percentage |
|:---------------------------------|------:|:-----------|
| High School diploma              |   307 | 43.48%     |
| Technical or vocational training |   117 | 16.57%     |
| Associate’s degree               |    13 | 1.84%      |
| Bachelor’s degree                |   168 | 23.8%      |
| Master’s degree                  |    20 | 2.83%      |
| Professional degree              |    78 | 11.05%     |
| Doctorate                        |     3 | 0.42%      |
| Total                            |   706 | 100%       |

Summary of Education Level Distribution with Totals

### Game frequency Summary statistics

| Statistic          |  Value |
|:-------------------|-------:|
| Average            |   2.70 |
| Median             |   2.00 |
| Min                |   1.00 |
| Max                |   7.00 |
| Standard Deviation |   2.06 |
| Non-Empty Rows     | 648.00 |

Summary Statistics for Frequency of Play

### Country of Origin Summary statistics

| Country                              | Count | Percentage |
|:-------------------------------------|------:|:-----------|
| Total                                |   704 | 100%       |
| Venezuela (República Bolivariana de) |   255 | 36.22%     |
| Argentina                            |   121 | 17.19%     |
| Bolivia (Estado Plurinacional de)    |   115 | 16.34%     |
| Colombia                             |    53 | 7.53%      |
| Nicaragua                            |    51 | 7.24%      |
| El Salvador                          |    21 | 2.98%      |
| Honduras                             |    21 | 2.98%      |
| Guatemala                            |    15 | 2.13%      |
| Perú                                 |     9 | 1.28%      |
| Ecuador                              |     8 | 1.14%      |

Summary of Country Distribution with Totals at the Top

### Hexad determinants Summary statistics

#### Table 3. Summary Statistics of Hexad-12 determinants (N = 866)

|                | Column         |  Mean | Median | Min | Max |   SD | Skewness | Kurtosis |
|:---------------|:---------------|------:|-------:|----:|----:|-----:|---------:|---------:|
| Free Spirit    | Free Spirit    | 12.76 |     14 |   2 |  14 | 2.06 |    -2.36 |     9.43 |
| Achiever       | Achiever       | 12.72 |     13 |   2 |  14 | 1.71 |    -2.11 |     9.88 |
| Philanthropist | Philanthropist | 12.38 |     13 |   2 |  14 | 2.33 |    -2.04 |     7.64 |
| Player         | Player         | 11.84 |     13 |   2 |  14 | 2.54 |    -1.46 |     5.00 |
| Socializer     | Socializer     | 10.96 |     12 |   2 |  14 | 3.10 |    -1.05 |     3.49 |
| Disruptor      | Disruptor      |  7.98 |      8 |   2 |  14 | 3.78 |    -0.14 |     1.90 |

Summary Statistics of Hexad-12 determinants

#### Figure 2: Violin plot of Hexad determinant distributions

![](README_files/figure-gfm/unnamed-chunk-11-1.png)<!-- -->

### Summary statistics for all Hexad-12 determinants across key subgroups

#### Appendix A3. Distribution of Hexad determinants by Education

| Measure | High School diploma | Technical or vocational training | Associate’s degree | Bachelor’s degree | Master’s degree | Professional degree | Doctorate |
|:---|---:|---:|---:|---:|---:|---:|---:|
| N | 307.00 | 117.00 | 13.00 | 168.00 | 20.00 | 78.00 | 3.00 |
| philanthropist_Mean | 12.46 | 12.47 | 12.00 | 12.20 | 12.60 | 12.67 | 12.33 |
| philanthropist_Median | 13.00 | 13.00 | 12.00 | 13.00 | 13.00 | 14.00 | 13.00 |
| philanthropist_Min | 2.00 | 2.00 | 8.00 | 2.00 | 7.00 | 6.00 | 10.00 |
| philanthropist_Max | 14.00 | 14.00 | 14.00 | 14.00 | 14.00 | 14.00 | 14.00 |
| philanthropist_SD | 2.11 | 2.05 | 2.20 | 2.44 | 1.85 | 1.84 | 2.08 |
| socializer_Mean | 10.84 | 10.95 | 11.08 | 11.26 | 11.75 | 11.56 | 11.33 |
| socializer_Median | 12.00 | 12.00 | 12.00 | 12.00 | 12.00 | 12.00 | 14.00 |
| socializer_Min | 2.00 | 2.00 | 4.00 | 2.00 | 7.00 | 4.00 | 6.00 |
| socializer_Max | 14.00 | 14.00 | 14.00 | 14.00 | 14.00 | 14.00 | 14.00 |
| socializer_SD | 3.09 | 2.87 | 2.99 | 2.91 | 2.29 | 2.60 | 4.62 |
| freeSpirit_Mean | 12.91 | 13.13 | 12.85 | 12.77 | 12.20 | 13.09 | 12.67 |
| freeSpirit_Median | 14.00 | 14.00 | 13.00 | 14.00 | 13.50 | 14.00 | 12.00 |
| freeSpirit_Min | 3.00 | 4.00 | 9.00 | 2.00 | 2.00 | 7.00 | 12.00 |
| freeSpirit_Max | 14.00 | 14.00 | 14.00 | 14.00 | 14.00 | 14.00 | 14.00 |
| freeSpirit_SD | 1.79 | 1.51 | 1.63 | 2.17 | 2.84 | 1.53 | 1.15 |
| achiever_Mean | 12.68 | 12.73 | 12.23 | 12.72 | 12.80 | 12.95 | 12.33 |
| achiever_Median | 13.00 | 13.00 | 13.00 | 13.00 | 13.00 | 14.00 | 13.00 |
| achiever_Min | 6.00 | 3.00 | 10.00 | 2.00 | 10.00 | 7.00 | 10.00 |
| achiever_Max | 14.00 | 14.00 | 14.00 | 14.00 | 14.00 | 14.00 | 14.00 |
| achiever_SD | 1.58 | 1.83 | 1.48 | 1.76 | 1.32 | 1.52 | 2.08 |
| player_Mean | 12.07 | 12.04 | 11.00 | 11.86 | 12.10 | 11.74 | 9.00 |
| player_Median | 13.00 | 13.00 | 11.00 | 13.00 | 13.00 | 12.00 | 11.00 |
| player_Min | 2.00 | 2.00 | 6.00 | 4.00 | 7.00 | 2.00 | 5.00 |
| player_Max | 14.00 | 14.00 | 14.00 | 14.00 | 14.00 | 14.00 | 11.00 |
| player_SD | 2.40 | 2.32 | 2.52 | 2.43 | 2.38 | 2.83 | 3.46 |
| disruptor_Mean | 8.30 | 8.11 | 8.31 | 7.40 | 8.15 | 8.05 | 4.67 |
| disruptor_Median | 9.00 | 8.00 | 9.00 | 7.00 | 9.00 | 8.00 | 4.00 |
| disruptor_Min | 2.00 | 2.00 | 2.00 | 2.00 | 2.00 | 2.00 | 4.00 |
| disruptor_Max | 14.00 | 14.00 | 14.00 | 14.00 | 14.00 | 14.00 | 6.00 |
| disruptor_SD | 3.70 | 3.75 | 3.61 | 3.60 | 3.70 | 3.86 | 1.15 |

Distribution of Hexad determinants by Education

#### Appendix A4. Distribution of Hexad items by Country

<table class="table table-striped table-hover table-condensed table-responsive" style="color: black; margin-left: auto; margin-right: auto;">

<caption>

Transposed Summary Statistics for Hexad Player Types by Country
</caption>

<thead>

<tr>

<th style="text-align:left;">

Statistic
</th>

<th style="text-align:right;">

Venezuela
</th>

<th style="text-align:right;">

Argentina
</th>

<th style="text-align:right;">

Bolivia
</th>

<th style="text-align:right;">

Colombia
</th>

<th style="text-align:right;">

Nicaragua
</th>

<th style="text-align:right;">

El Salvador
</th>

<th style="text-align:right;">

Honduras
</th>

<th style="text-align:right;">

Guatemala
</th>

<th style="text-align:right;">

Perú
</th>

<th style="text-align:right;">

Ecuador
</th>

</tr>

</thead>

<tbody>

<tr>

<td style="text-align:left;">

sample_size
</td>

<td style="text-align:right;">

255.00
</td>

<td style="text-align:right;">

121.00
</td>

<td style="text-align:right;">

115.00
</td>

<td style="text-align:right;">

53.00
</td>

<td style="text-align:right;">

51.00
</td>

<td style="text-align:right;">

21.00
</td>

<td style="text-align:right;">

21.00
</td>

<td style="text-align:right;">

15.00
</td>

<td style="text-align:right;">

9.00
</td>

<td style="text-align:right;">

8.00
</td>

</tr>

<tr>

<td style="text-align:left;">

philanthropist_mean
</td>

<td style="text-align:right;">

12.64
</td>

<td style="text-align:right;">

12.40
</td>

<td style="text-align:right;">

12.16
</td>

<td style="text-align:right;">

12.92
</td>

<td style="text-align:right;">

12.16
</td>

<td style="text-align:right;">

12.57
</td>

<td style="text-align:right;">

12.86
</td>

<td style="text-align:right;">

12.07
</td>

<td style="text-align:right;">

12.33
</td>

<td style="text-align:right;">

11.25
</td>

</tr>

<tr>

<td style="text-align:left;">

philanthropist_median
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

13.00
</td>

<td style="text-align:right;">

13.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

13.00
</td>

<td style="text-align:right;">

13.00
</td>

<td style="text-align:right;">

13.00
</td>

<td style="text-align:right;">

12.00
</td>

<td style="text-align:right;">

13.00
</td>

<td style="text-align:right;">

13.00
</td>

</tr>

<tr>

<td style="text-align:left;">

philanthropist_min
</td>

<td style="text-align:right;">

2.00
</td>

<td style="text-align:right;">

3.00
</td>

<td style="text-align:right;">

3.00
</td>

<td style="text-align:right;">

7.00
</td>

<td style="text-align:right;">

6.00
</td>

<td style="text-align:right;">

5.00
</td>

<td style="text-align:right;">

10.00
</td>

<td style="text-align:right;">

9.00
</td>

<td style="text-align:right;">

10.00
</td>

<td style="text-align:right;">

2.00
</td>

</tr>

<tr>

<td style="text-align:left;">

philanthropist_max
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

</tr>

<tr>

<td style="text-align:left;">

philanthropist_sd
</td>

<td style="text-align:right;">

2.00
</td>

<td style="text-align:right;">

2.21
</td>

<td style="text-align:right;">

1.98
</td>

<td style="text-align:right;">

1.81
</td>

<td style="text-align:right;">

2.39
</td>

<td style="text-align:right;">

2.25
</td>

<td style="text-align:right;">

1.31
</td>

<td style="text-align:right;">

1.71
</td>

<td style="text-align:right;">

1.80
</td>

<td style="text-align:right;">

4.23
</td>

</tr>

<tr>

<td style="text-align:left;">

socializer_mean
</td>

<td style="text-align:right;">

11.40
</td>

<td style="text-align:right;">

10.50
</td>

<td style="text-align:right;">

11.18
</td>

<td style="text-align:right;">

11.47
</td>

<td style="text-align:right;">

10.31
</td>

<td style="text-align:right;">

11.62
</td>

<td style="text-align:right;">

11.29
</td>

<td style="text-align:right;">

10.33
</td>

<td style="text-align:right;">

11.56
</td>

<td style="text-align:right;">

11.50
</td>

</tr>

<tr>

<td style="text-align:left;">

socializer_median
</td>

<td style="text-align:right;">

12.00
</td>

<td style="text-align:right;">

11.00
</td>

<td style="text-align:right;">

12.00
</td>

<td style="text-align:right;">

12.00
</td>

<td style="text-align:right;">

11.00
</td>

<td style="text-align:right;">

11.00
</td>

<td style="text-align:right;">

12.00
</td>

<td style="text-align:right;">

11.00
</td>

<td style="text-align:right;">

11.00
</td>

<td style="text-align:right;">

13.00
</td>

</tr>

<tr>

<td style="text-align:left;">

socializer_min
</td>

<td style="text-align:right;">

2.00
</td>

<td style="text-align:right;">

2.00
</td>

<td style="text-align:right;">

2.00
</td>

<td style="text-align:right;">

3.00
</td>

<td style="text-align:right;">

2.00
</td>

<td style="text-align:right;">

4.00
</td>

<td style="text-align:right;">

2.00
</td>

<td style="text-align:right;">

6.00
</td>

<td style="text-align:right;">

8.00
</td>

<td style="text-align:right;">

4.00
</td>

</tr>

<tr>

<td style="text-align:left;">

socializer_max
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

</tr>

<tr>

<td style="text-align:left;">

socializer_sd
</td>

<td style="text-align:right;">

2.77
</td>

<td style="text-align:right;">

3.03
</td>

<td style="text-align:right;">

2.86
</td>

<td style="text-align:right;">

2.87
</td>

<td style="text-align:right;">

3.37
</td>

<td style="text-align:right;">

2.42
</td>

<td style="text-align:right;">

3.08
</td>

<td style="text-align:right;">

2.89
</td>

<td style="text-align:right;">

2.19
</td>

<td style="text-align:right;">

3.55
</td>

</tr>

<tr>

<td style="text-align:left;">

freeSpirit_mean
</td>

<td style="text-align:right;">

13.02
</td>

<td style="text-align:right;">

12.76
</td>

<td style="text-align:right;">

12.85
</td>

<td style="text-align:right;">

13.04
</td>

<td style="text-align:right;">

13.12
</td>

<td style="text-align:right;">

12.90
</td>

<td style="text-align:right;">

12.90
</td>

<td style="text-align:right;">

13.20
</td>

<td style="text-align:right;">

13.67
</td>

<td style="text-align:right;">

11.88
</td>

</tr>

<tr>

<td style="text-align:left;">

freeSpirit_median
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

13.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

</tr>

<tr>

<td style="text-align:left;">

freeSpirit_min
</td>

<td style="text-align:right;">

4.00
</td>

<td style="text-align:right;">

2.00
</td>

<td style="text-align:right;">

2.00
</td>

<td style="text-align:right;">

4.00
</td>

<td style="text-align:right;">

7.00
</td>

<td style="text-align:right;">

7.00
</td>

<td style="text-align:right;">

10.00
</td>

<td style="text-align:right;">

10.00
</td>

<td style="text-align:right;">

12.00
</td>

<td style="text-align:right;">

3.00
</td>

</tr>

<tr>

<td style="text-align:left;">

freeSpirit_max
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

</tr>

<tr>

<td style="text-align:left;">

freeSpirit_sd
</td>

<td style="text-align:right;">

1.74
</td>

<td style="text-align:right;">

2.00
</td>

<td style="text-align:right;">

1.86
</td>

<td style="text-align:right;">

1.70
</td>

<td style="text-align:right;">

1.68
</td>

<td style="text-align:right;">

1.73
</td>

<td style="text-align:right;">

1.22
</td>

<td style="text-align:right;">

1.26
</td>

<td style="text-align:right;">

0.71
</td>

<td style="text-align:right;">

3.87
</td>

</tr>

<tr>

<td style="text-align:left;">

achiever_mean
</td>

<td style="text-align:right;">

12.72
</td>

<td style="text-align:right;">

12.52
</td>

<td style="text-align:right;">

12.49
</td>

<td style="text-align:right;">

13.32
</td>

<td style="text-align:right;">

13.25
</td>

<td style="text-align:right;">

13.10
</td>

<td style="text-align:right;">

12.29
</td>

<td style="text-align:right;">

12.67
</td>

<td style="text-align:right;">

12.78
</td>

<td style="text-align:right;">

12.75
</td>

</tr>

<tr>

<td style="text-align:left;">

achiever_median
</td>

<td style="text-align:right;">

13.00
</td>

<td style="text-align:right;">

13.00
</td>

<td style="text-align:right;">

13.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

13.00
</td>

<td style="text-align:right;">

13.00
</td>

<td style="text-align:right;">

13.00
</td>

<td style="text-align:right;">

14.00
</td>

</tr>

<tr>

<td style="text-align:left;">

achiever_min
</td>

<td style="text-align:right;">

3.00
</td>

<td style="text-align:right;">

3.00
</td>

<td style="text-align:right;">

2.00
</td>

<td style="text-align:right;">

10.00
</td>

<td style="text-align:right;">

10.00
</td>

<td style="text-align:right;">

10.00
</td>

<td style="text-align:right;">

8.00
</td>

<td style="text-align:right;">

11.00
</td>

<td style="text-align:right;">

9.00
</td>

<td style="text-align:right;">

8.00
</td>

</tr>

<tr>

<td style="text-align:left;">

achiever_max
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

</tr>

<tr>

<td style="text-align:left;">

achiever_sd
</td>

<td style="text-align:right;">

1.78
</td>

<td style="text-align:right;">

1.81
</td>

<td style="text-align:right;">

1.76
</td>

<td style="text-align:right;">

0.92
</td>

<td style="text-align:right;">

1.11
</td>

<td style="text-align:right;">

1.26
</td>

<td style="text-align:right;">

1.68
</td>

<td style="text-align:right;">

1.11
</td>

<td style="text-align:right;">

1.64
</td>

<td style="text-align:right;">

2.19
</td>

</tr>

<tr>

<td style="text-align:left;">

player_mean
</td>

<td style="text-align:right;">

12.16
</td>

<td style="text-align:right;">

11.52
</td>

<td style="text-align:right;">

12.25
</td>

<td style="text-align:right;">

12.02
</td>

<td style="text-align:right;">

11.88
</td>

<td style="text-align:right;">

11.48
</td>

<td style="text-align:right;">

11.86
</td>

<td style="text-align:right;">

12.47
</td>

<td style="text-align:right;">

12.78
</td>

<td style="text-align:right;">

10.88
</td>

</tr>

<tr>

<td style="text-align:left;">

player_median
</td>

<td style="text-align:right;">

13.00
</td>

<td style="text-align:right;">

12.00
</td>

<td style="text-align:right;">

13.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

13.00
</td>

<td style="text-align:right;">

13.00
</td>

<td style="text-align:right;">

13.00
</td>

<td style="text-align:right;">

13.00
</td>

<td style="text-align:right;">

13.00
</td>

<td style="text-align:right;">

12.00
</td>

</tr>

<tr>

<td style="text-align:left;">

player_min
</td>

<td style="text-align:right;">

3.00
</td>

<td style="text-align:right;">

2.00
</td>

<td style="text-align:right;">

4.00
</td>

<td style="text-align:right;">

2.00
</td>

<td style="text-align:right;">

6.00
</td>

<td style="text-align:right;">

5.00
</td>

<td style="text-align:right;">

7.00
</td>

<td style="text-align:right;">

8.00
</td>

<td style="text-align:right;">

10.00
</td>

<td style="text-align:right;">

2.00
</td>

</tr>

<tr>

<td style="text-align:left;">

player_max
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

</tr>

<tr>

<td style="text-align:left;">

player_sd
</td>

<td style="text-align:right;">

2.31
</td>

<td style="text-align:right;">

2.46
</td>

<td style="text-align:right;">

2.15
</td>

<td style="text-align:right;">

2.86
</td>

<td style="text-align:right;">

2.44
</td>

<td style="text-align:right;">

2.86
</td>

<td style="text-align:right;">

2.06
</td>

<td style="text-align:right;">

1.51
</td>

<td style="text-align:right;">

1.48
</td>

<td style="text-align:right;">

3.91
</td>

</tr>

<tr>

<td style="text-align:left;">

disruptor_mean
</td>

<td style="text-align:right;">

7.49
</td>

<td style="text-align:right;">

8.39
</td>

<td style="text-align:right;">

8.32
</td>

<td style="text-align:right;">

8.21
</td>

<td style="text-align:right;">

7.59
</td>

<td style="text-align:right;">

7.38
</td>

<td style="text-align:right;">

7.90
</td>

<td style="text-align:right;">

9.73
</td>

<td style="text-align:right;">

8.22
</td>

<td style="text-align:right;">

8.38
</td>

</tr>

<tr>

<td style="text-align:left;">

disruptor_median
</td>

<td style="text-align:right;">

8.00
</td>

<td style="text-align:right;">

9.00
</td>

<td style="text-align:right;">

8.00
</td>

<td style="text-align:right;">

9.00
</td>

<td style="text-align:right;">

7.00
</td>

<td style="text-align:right;">

7.00
</td>

<td style="text-align:right;">

8.00
</td>

<td style="text-align:right;">

11.00
</td>

<td style="text-align:right;">

9.00
</td>

<td style="text-align:right;">

9.00
</td>

</tr>

<tr>

<td style="text-align:left;">

disruptor_min
</td>

<td style="text-align:right;">

2.00
</td>

<td style="text-align:right;">

2.00
</td>

<td style="text-align:right;">

2.00
</td>

<td style="text-align:right;">

2.00
</td>

<td style="text-align:right;">

2.00
</td>

<td style="text-align:right;">

2.00
</td>

<td style="text-align:right;">

2.00
</td>

<td style="text-align:right;">

2.00
</td>

<td style="text-align:right;">

2.00
</td>

<td style="text-align:right;">

5.00
</td>

</tr>

<tr>

<td style="text-align:left;">

disruptor_max
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

14.00
</td>

<td style="text-align:right;">

13.00
</td>

<td style="text-align:right;">

11.00
</td>

</tr>

<tr>

<td style="text-align:left;">

disruptor_sd
</td>

<td style="text-align:right;">

3.72
</td>

<td style="text-align:right;">

3.75
</td>

<td style="text-align:right;">

3.38
</td>

<td style="text-align:right;">

3.92
</td>

<td style="text-align:right;">

3.99
</td>

<td style="text-align:right;">

4.26
</td>

<td style="text-align:right;">

3.55
</td>

<td style="text-align:right;">

3.61
</td>

<td style="text-align:right;">

3.80
</td>

<td style="text-align:right;">

2.45
</td>

</tr>

</tbody>

</table>

#### Appendix A5. Distribution of Hexad determinants by Gender

| Measure               | female |   male | other |
|:----------------------|-------:|-------:|------:|
| N                     | 369.00 | 256.00 |  3.00 |
| philanthropist_Mean   |  12.70 |  12.15 | 13.67 |
| philanthropist_Median |  13.00 |  13.00 | 14.00 |
| philanthropist_Min    |   4.00 |   2.00 | 13.00 |
| philanthropist_Max    |  14.00 |  14.00 | 14.00 |
| philanthropist_SD     |   1.81 |   2.46 |  0.58 |
| socializer_Mean       |  11.14 |  11.13 | 12.00 |
| socializer_Median     |  12.00 |  12.00 | 12.00 |
| socializer_Min        |   2.00 |   2.00 | 10.00 |
| socializer_Max        |  14.00 |  14.00 | 14.00 |
| socializer_SD         |   2.91 |   2.93 |  2.00 |
| freeSpirit_Mean       |  13.06 |  12.62 | 13.67 |
| freeSpirit_Median     |  14.00 |  14.00 | 14.00 |
| freeSpirit_Min        |   4.00 |   2.00 | 13.00 |
| freeSpirit_Max        |  14.00 |  14.00 | 14.00 |
| freeSpirit_SD         |   1.60 |   2.26 |  0.58 |
| achiever_Mean         |  12.63 |  12.87 | 13.67 |
| achiever_Median       |  13.00 |  13.00 | 14.00 |
| achiever_Min          |   3.00 |   2.00 | 13.00 |
| achiever_Max          |  14.00 |  14.00 | 14.00 |
| achiever_SD           |   1.69 |   1.59 |  0.58 |
| player_Mean           |  11.86 |  11.94 | 13.00 |
| player_Median         |  13.00 |  13.00 | 13.00 |
| player_Min            |   2.00 |   2.00 | 12.00 |
| player_Max            |  14.00 |  14.00 | 14.00 |
| player_SD             |   2.49 |   2.40 |  1.00 |
| disruptor_Mean        |   7.82 |   8.27 |  9.33 |
| disruptor_Median      |   8.00 |   9.00 | 12.00 |
| disruptor_Min         |   2.00 |   2.00 |  2.00 |
| disruptor_Max         |  14.00 |  14.00 | 14.00 |
| disruptor_SD          |   3.61 |   3.81 |  6.43 |

Distribution of Hexad determinants by Gender

#### Appendix A6. Distribution of Hexad determinants by Age Group

| Measure               |  18–24 |  25–34 |  35–49 |    50+ |
|:----------------------|-------:|-------:|-------:|-------:|
| N                     | 219.00 | 180.00 | 145.00 | 193.00 |
| philanthropist_Mean   |  11.85 |  12.56 |  12.72 |  12.77 |
| philanthropist_Median |  12.00 |  13.00 |  13.00 |  14.00 |
| philanthropist_Min    |   2.00 |   2.00 |   7.00 |   2.00 |
| philanthropist_Max    |  14.00 |  14.00 |  14.00 |  14.00 |
| philanthropist_SD     |   2.45 |   2.22 |   1.76 |   2.08 |
| socializer_Mean       |  10.73 |  11.12 |  11.31 |  11.25 |
| socializer_Median     |  12.00 |  12.00 |  12.00 |  12.00 |
| socializer_Min        |   2.00 |   2.00 |   2.00 |   2.00 |
| socializer_Max        |  14.00 |  14.00 |  14.00 |  14.00 |
| socializer_SD         |   3.14 |   2.94 |   2.82 |   2.92 |
| freeSpirit_Mean       |  12.66 |  13.05 |  12.94 |  12.86 |
| freeSpirit_Median     |  14.00 |  14.00 |  14.00 |  14.00 |
| freeSpirit_Min        |   3.00 |   2.00 |   2.00 |   4.00 |
| freeSpirit_Max        |  14.00 |  14.00 |  14.00 |  14.00 |
| freeSpirit_SD         |   2.03 |   1.94 |   1.82 |   1.76 |
| achiever_Mean         |  12.60 |  12.89 |  12.88 |  12.56 |
| achiever_Median       |  13.00 |  14.00 |  14.00 |  13.00 |
| achiever_Min          |   6.00 |   2.00 |   7.00 |   3.00 |
| achiever_Max          |  14.00 |  14.00 |  14.00 |  14.00 |
| achiever_SD           |   1.60 |   1.68 |   1.58 |   1.83 |
| player_Mean           |  12.09 |  12.30 |  12.10 |  11.12 |
| player_Median         |  13.00 |  13.00 |  13.00 |  12.00 |
| player_Min            |   2.00 |   4.00 |   2.00 |   2.00 |
| player_Max            |  14.00 |  14.00 |  14.00 |  14.00 |
| player_SD             |   2.30 |   2.16 |   2.40 |   2.92 |
| disruptor_Mean        |   8.00 |   7.97 |   7.90 |   7.90 |
| disruptor_Median      |   8.00 |   8.00 |   8.00 |   8.00 |
| disruptor_Min         |   2.00 |   2.00 |   2.00 |   2.00 |
| disruptor_Max         |  14.00 |  14.00 |  14.00 |  14.00 |
| disruptor_SD          |   3.70 |   3.67 |   3.52 |   3.99 |

Distribution of Hexad determinants by Age Group

#### Apendix A7. Distribution of Hexad determinants by Weekly Gaming Frequency

| Measure               | 1–2 days | 3–4 days | 5–7 days |
|:----------------------|---------:|---------:|---------:|
| N                     |   379.00 |   133.00 |   136.00 |
| philanthropist_Mean   |    12.45 |    12.47 |    12.23 |
| philanthropist_Median |    13.00 |    13.00 |    13.00 |
| philanthropist_Min    |     2.00 |     4.00 |     2.00 |
| philanthropist_Max    |    14.00 |    14.00 |    14.00 |
| philanthropist_SD     |     2.16 |     2.08 |     2.40 |
| socializer_Mean       |    11.17 |    11.08 |    10.73 |
| socializer_Median     |    12.00 |    12.00 |    12.00 |
| socializer_Min        |     2.00 |     2.00 |     2.00 |
| socializer_Max        |    14.00 |    14.00 |    14.00 |
| socializer_SD         |     2.91 |     2.93 |     3.14 |
| freeSpirit_Mean       |    12.94 |    12.65 |    12.92 |
| freeSpirit_Median     |    14.00 |    13.00 |    14.00 |
| freeSpirit_Min        |     2.00 |     4.00 |     4.00 |
| freeSpirit_Max        |    14.00 |    14.00 |    14.00 |
| freeSpirit_SD         |     1.93 |     1.90 |     1.82 |
| achiever_Mean         |    12.78 |    12.59 |    12.65 |
| achiever_Median       |    13.00 |    13.00 |    13.00 |
| achiever_Min          |     2.00 |     4.00 |     3.00 |
| achiever_Max          |    14.00 |    14.00 |    14.00 |
| achiever_SD           |     1.69 |     1.72 |     1.81 |
| player_Mean           |    11.88 |    12.07 |    12.05 |
| player_Median         |    13.00 |    13.00 |    13.00 |
| player_Min            |     3.00 |     2.00 |     2.00 |
| player_Max            |    14.00 |    14.00 |    14.00 |
| player_SD             |     2.44 |     2.42 |     2.52 |
| disruptor_Mean        |     7.87 |     7.82 |     8.52 |
| disruptor_Median      |     8.00 |     8.00 |     9.00 |
| disruptor_Min         |     2.00 |     2.00 |     2.00 |
| disruptor_Max         |    14.00 |    14.00 |    14.00 |
| disruptor_SD          |     3.74 |     3.71 |     3.65 |

Distribution of Hexad determinants by Weekly Gaming Frequency

## 4.3. Distributional checks

#### Appendix A8. Mardia’s multivariate normality test for Hexad-12 items

<table class="table table-striped table-hover table-condensed table-responsive" style="color: black; width: auto !important; margin-left: auto; margin-right: auto;">

<caption>

Mardia’s Test for Multivariate Normality
</caption>

<thead>

<tr>

<th style="text-align:left;">

Test
</th>

<th style="text-align:left;">

Statistic
</th>

<th style="text-align:left;">

P_Value
</th>

</tr>

</thead>

<tbody>

<tr>

<td style="text-align:left;">

Skewness
</td>

<td style="text-align:left;">

5895.59795179289
</td>

<td style="text-align:left;">

0
</td>

</tr>

<tr>

<td style="text-align:left;">

Kurtosis
</td>

<td style="text-align:left;">

42.0524988084385
</td>

<td style="text-align:left;">

0
</td>

</tr>

</tbody>

</table>

## 4.4. Item-level diagnostics

#### Appendix A9. Summary Statistics per item

|     | vars |   n | mean |   sd | median | trimmed |  mad | min | max | range |  skew | kurtosis |   se |
|:----|-----:|----:|-----:|-----:|-------:|--------:|-----:|----:|----:|------:|------:|---------:|-----:|
| A2  |    1 | 866 | 6.17 | 1.11 |      7 |    6.39 | 0.00 |   1 |   7 |     6 | -1.58 |     2.61 | 0.04 |
| A4  |    2 | 866 | 6.55 | 0.88 |      7 |    6.76 | 0.00 |   1 |   7 |     6 | -2.64 |     8.71 | 0.03 |
| D3  |    3 | 866 | 4.12 | 2.12 |      4 |    4.16 | 2.97 |   1 |   7 |     6 | -0.18 |    -1.29 | 0.07 |
| D4  |    4 | 866 | 3.86 | 2.14 |      4 |    3.82 | 2.97 |   1 |   7 |     6 |  0.00 |    -1.37 | 0.07 |
| F1  |    5 | 866 | 6.38 | 1.14 |      7 |    6.65 | 0.00 |   1 |   7 |     6 | -2.38 |     6.21 | 0.04 |
| F3  |    6 | 866 | 6.39 | 1.17 |      7 |    6.67 | 0.00 |   1 |   7 |     6 | -2.44 |     6.34 | 0.04 |
| P1  |    7 | 866 | 6.36 | 1.21 |      7 |    6.66 | 0.00 |   1 |   7 |     6 | -2.58 |     7.14 | 0.04 |
| P4  |    8 | 866 | 6.01 | 1.38 |      7 |    6.29 | 0.00 |   1 |   7 |     6 | -1.70 |     2.70 | 0.05 |
| R2  |    9 | 866 | 5.88 | 1.41 |      6 |    6.12 | 1.48 |   1 |   7 |     6 | -1.35 |     1.40 | 0.05 |
| R4  |   10 | 866 | 5.96 | 1.51 |      7 |    6.28 | 0.00 |   1 |   7 |     6 | -1.64 |     2.11 | 0.05 |
| S2  |   11 | 866 | 5.50 | 1.70 |      6 |    5.78 | 1.48 |   1 |   7 |     6 | -1.11 |     0.41 | 0.06 |
| S4  |   12 | 866 | 5.46 | 1.69 |      6 |    5.72 | 1.48 |   1 |   7 |     6 | -1.07 |     0.34 | 0.06 |

Summary Statistics per item

#### Appendix A10. Response distributions for each Hexad-12 item

![](README_files/figure-gfm/unnamed-chunk-19-1.png)<!-- -->

#### Appendix A11. Multimodality Silverman tests results

    ## A2   bw = 0.520  p = 0.274
    ## A4   bw = 0.589  p = 0.468
    ## D3   bw = 1.079  p = 0.008
    ## D4   bw = 1.279  p = 0.023
    ## F1   bw = 0.685  p = 0.160
    ## F3   bw = 0.668  p = 0.176
    ## P1   bw = 0.837  p = 0.098
    ## P4   bw = 0.542  p = 0.338
    ## R2   bw = 0.421  p = 0.360
    ## R4   bw = 0.571  p = 0.303
    ## S2   bw = 0.685  p = 0.012
    ## S4   bw = 0.652  p = 0.020

#### Appendix A12. Item–total correlation for each subscale

|     |    x |
|:----|-----:|
| A2  | 0.33 |
| A4  | 0.40 |
| D3  | 0.11 |
| D4  | 0.09 |
| F1  | 0.49 |
| F3  | 0.44 |
| P1  | 0.50 |
| P4  | 0.38 |
| R2  | 0.35 |
| R4  | 0.33 |
| S2  | 0.40 |
| S4  | 0.39 |

Item–total correlation for each subscale

## 4.5. Confirmatory Factor Analysis

#### Table 4: Estimated factor loadings for Hexad-12 items

<table class="table" style="color: black; margin-left: auto; margin-right: auto;">

<caption>

Estimated factor loading for Hexad-12 items
</caption>

<thead>

<tr>

<th style="text-align:left;">

op
</th>

<th style="text-align:left;">

rhs
</th>

<th style="text-align:right;">

exo
</th>

<th style="text-align:right;">

est
</th>

<th style="text-align:right;">

se
</th>

<th style="text-align:right;">

z
</th>

<th style="text-align:right;">

pvalue
</th>

<th style="text-align:right;">

std.all
</th>

</tr>

</thead>

<tbody>

<tr>

<td style="text-align:left;width: 2cm; ">

=~
</td>

<td style="text-align:left;width: 2cm; ">

A2
</td>

<td style="text-align:right;width: 2cm; ">

0
</td>

<td style="text-align:right;width: 2cm; ">

0.676
</td>

<td style="text-align:right;width: 2cm; ">

0.067
</td>

<td style="text-align:right;width: 2cm; ">

10.093
</td>

<td style="text-align:right;width: 2cm; ">

0
</td>

<td style="text-align:right;width: 2cm; ">

0.607
</td>

</tr>

<tr>

<td style="text-align:left;width: 2cm; ">

=~
</td>

<td style="text-align:left;width: 2cm; ">

A4
</td>

<td style="text-align:right;width: 2cm; ">

0
</td>

<td style="text-align:right;width: 2cm; ">

0.670
</td>

<td style="text-align:right;width: 2cm; ">

0.069
</td>

<td style="text-align:right;width: 2cm; ">

9.722
</td>

<td style="text-align:right;width: 2cm; ">

0
</td>

<td style="text-align:right;width: 2cm; ">

0.758
</td>

</tr>

<tr>

<td style="text-align:left;width: 2cm; ">

=~
</td>

<td style="text-align:left;width: 2cm; ">

D3
</td>

<td style="text-align:right;width: 2cm; ">

0
</td>

<td style="text-align:right;width: 2cm; ">

1.402
</td>

<td style="text-align:right;width: 2cm; ">

0.133
</td>

<td style="text-align:right;width: 2cm; ">

10.521
</td>

<td style="text-align:right;width: 2cm; ">

0
</td>

<td style="text-align:right;width: 2cm; ">

0.661
</td>

</tr>

<tr>

<td style="text-align:left;width: 2cm; ">

=~
</td>

<td style="text-align:left;width: 2cm; ">

D4
</td>

<td style="text-align:right;width: 2cm; ">

0
</td>

<td style="text-align:right;width: 2cm; ">

1.843
</td>

<td style="text-align:right;width: 2cm; ">

0.167
</td>

<td style="text-align:right;width: 2cm; ">

11.059
</td>

<td style="text-align:right;width: 2cm; ">

0
</td>

<td style="text-align:right;width: 2cm; ">

0.860
</td>

</tr>

<tr>

<td style="text-align:left;width: 2cm; ">

=~
</td>

<td style="text-align:left;width: 2cm; ">

F1
</td>

<td style="text-align:right;width: 2cm; ">

0
</td>

<td style="text-align:right;width: 2cm; ">

0.901
</td>

<td style="text-align:right;width: 2cm; ">

0.061
</td>

<td style="text-align:right;width: 2cm; ">

14.663
</td>

<td style="text-align:right;width: 2cm; ">

0
</td>

<td style="text-align:right;width: 2cm; ">

0.789
</td>

</tr>

<tr>

<td style="text-align:left;width: 2cm; ">

=~
</td>

<td style="text-align:left;width: 2cm; ">

F3
</td>

<td style="text-align:right;width: 2cm; ">

0
</td>

<td style="text-align:right;width: 2cm; ">

0.868
</td>

<td style="text-align:right;width: 2cm; ">

0.070
</td>

<td style="text-align:right;width: 2cm; ">

12.380
</td>

<td style="text-align:right;width: 2cm; ">

0
</td>

<td style="text-align:right;width: 2cm; ">

0.744
</td>

</tr>

<tr>

<td style="text-align:left;width: 2cm; ">

=~
</td>

<td style="text-align:left;width: 2cm; ">

P1
</td>

<td style="text-align:right;width: 2cm; ">

0
</td>

<td style="text-align:right;width: 2cm; ">

1.039
</td>

<td style="text-align:right;width: 2cm; ">

0.071
</td>

<td style="text-align:right;width: 2cm; ">

14.556
</td>

<td style="text-align:right;width: 2cm; ">

0
</td>

<td style="text-align:right;width: 2cm; ">

0.860
</td>

</tr>

<tr>

<td style="text-align:left;width: 2cm; ">

=~
</td>

<td style="text-align:left;width: 2cm; ">

P4
</td>

<td style="text-align:right;width: 2cm; ">

0
</td>

<td style="text-align:right;width: 2cm; ">

0.987
</td>

<td style="text-align:right;width: 2cm; ">

0.064
</td>

<td style="text-align:right;width: 2cm; ">

15.510
</td>

<td style="text-align:right;width: 2cm; ">

0
</td>

<td style="text-align:right;width: 2cm; ">

0.715
</td>

</tr>

<tr>

<td style="text-align:left;width: 2cm; ">

=~
</td>

<td style="text-align:left;width: 2cm; ">

R2
</td>

<td style="text-align:right;width: 2cm; ">

0
</td>

<td style="text-align:right;width: 2cm; ">

1.046
</td>

<td style="text-align:right;width: 2cm; ">

0.079
</td>

<td style="text-align:right;width: 2cm; ">

13.200
</td>

<td style="text-align:right;width: 2cm; ">

0
</td>

<td style="text-align:right;width: 2cm; ">

0.741
</td>

</tr>

<tr>

<td style="text-align:left;width: 2cm; ">

=~
</td>

<td style="text-align:left;width: 2cm; ">

R4
</td>

<td style="text-align:right;width: 2cm; ">

0
</td>

<td style="text-align:right;width: 2cm; ">

1.038
</td>

<td style="text-align:right;width: 2cm; ">

0.074
</td>

<td style="text-align:right;width: 2cm; ">

14.052
</td>

<td style="text-align:right;width: 2cm; ">

0
</td>

<td style="text-align:right;width: 2cm; ">

0.688
</td>

</tr>

<tr>

<td style="text-align:left;width: 2cm; ">

=~
</td>

<td style="text-align:left;width: 2cm; ">

S2
</td>

<td style="text-align:right;width: 2cm; ">

0
</td>

<td style="text-align:right;width: 2cm; ">

1.401
</td>

<td style="text-align:right;width: 2cm; ">

0.063
</td>

<td style="text-align:right;width: 2cm; ">

22.080
</td>

<td style="text-align:right;width: 2cm; ">

0
</td>

<td style="text-align:right;width: 2cm; ">

0.825
</td>

</tr>

<tr>

<td style="text-align:left;width: 2cm; ">

=~
</td>

<td style="text-align:left;width: 2cm; ">

S4
</td>

<td style="text-align:right;width: 2cm; ">

0
</td>

<td style="text-align:right;width: 2cm; ">

1.372
</td>

<td style="text-align:right;width: 2cm; ">

0.064
</td>

<td style="text-align:right;width: 2cm; ">

21.347
</td>

<td style="text-align:right;width: 2cm; ">

0
</td>

<td style="text-align:right;width: 2cm; ">

0.812
</td>

</tr>

</tbody>

</table>

#### CFA

#### CFA fit indices with 95% CI using bootstrapping with 10,000 samples (Table 5)

<table class="table table-striped table-hover table-condensed table-responsive" style="color: black; width: auto !important; margin-left: auto; margin-right: auto;">

<caption>

CFA metrics with confident interval
</caption>

<thead>

<tr>

<th style="text-align:left;">

Metric
</th>

<th style="text-align:right;">

Estimate
</th>

<th style="text-align:right;">

CI_Lower
</th>

<th style="text-align:right;">

CI_Upper
</th>

</tr>

</thead>

<tbody>

<tr>

<td style="text-align:left;">

chisq.scaled
</td>

<td style="text-align:right;">

77.320
</td>

<td style="text-align:right;">

69.545
</td>

<td style="text-align:right;">

141.811
</td>

</tr>

<tr>

<td style="text-align:left;">

srmr
</td>

<td style="text-align:right;">

0.026
</td>

<td style="text-align:right;">

0.024
</td>

<td style="text-align:right;">

0.037
</td>

</tr>

<tr>

<td style="text-align:left;">

tli.scaled
</td>

<td style="text-align:right;">

0.914
</td>

<td style="text-align:right;">

0.766
</td>

<td style="text-align:right;">

0.933
</td>

</tr>

<tr>

<td style="text-align:left;">

cfi.scaled
</td>

<td style="text-align:right;">

0.949
</td>

<td style="text-align:right;">

0.862
</td>

<td style="text-align:right;">

0.960
</td>

</tr>

<tr>

<td style="text-align:left;">

rmsea.scaled
</td>

<td style="text-align:right;">

0.034
</td>

<td style="text-align:right;">

0.030
</td>

<td style="text-align:right;">

0.055
</td>

</tr>

<tr>

<td style="text-align:left;">

CR.Achiever
</td>

<td style="text-align:right;">

0.619
</td>

<td style="text-align:right;">

0.524
</td>

<td style="text-align:right;">

0.698
</td>

</tr>

<tr>

<td style="text-align:left;">

CR.Disruptor
</td>

<td style="text-align:right;">

0.738
</td>

<td style="text-align:right;">

0.693
</td>

<td style="text-align:right;">

0.817
</td>

</tr>

<tr>

<td style="text-align:left;">

CR.FreeSpirit
</td>

<td style="text-align:right;">

0.740
</td>

<td style="text-align:right;">

0.665
</td>

<td style="text-align:right;">

0.800
</td>

</tr>

<tr>

<td style="text-align:left;">

CR.Philanthropist
</td>

<td style="text-align:right;">

0.758
</td>

<td style="text-align:right;">

0.693
</td>

<td style="text-align:right;">

0.813
</td>

</tr>

<tr>

<td style="text-align:left;">

CR.Player
</td>

<td style="text-align:right;">

0.674
</td>

<td style="text-align:right;">

0.611
</td>

<td style="text-align:right;">

0.731
</td>

</tr>

<tr>

<td style="text-align:left;">

CR.Socializer
</td>

<td style="text-align:right;">

0.802
</td>

<td style="text-align:right;">

0.759
</td>

<td style="text-align:right;">

0.841
</td>

</tr>

<tr>

<td style="text-align:left;">

AVE.Achiever
</td>

<td style="text-align:right;">

0.448
</td>

<td style="text-align:right;">

0.356
</td>

<td style="text-align:right;">

0.537
</td>

</tr>

<tr>

<td style="text-align:left;">

AVE.Disruptor
</td>

<td style="text-align:right;">

0.589
</td>

<td style="text-align:right;">

0.532
</td>

<td style="text-align:right;">

0.711
</td>

</tr>

<tr>

<td style="text-align:left;">

AVE.FreeSpirit
</td>

<td style="text-align:right;">

0.587
</td>

<td style="text-align:right;">

0.499
</td>

<td style="text-align:right;">

0.667
</td>

</tr>

<tr>

<td style="text-align:left;">

AVE.Philanthropist
</td>

<td style="text-align:right;">

0.611
</td>

<td style="text-align:right;">

0.531
</td>

<td style="text-align:right;">

0.685
</td>

</tr>

<tr>

<td style="text-align:left;">

AVE.Player
</td>

<td style="text-align:right;">

0.509
</td>

<td style="text-align:right;">

0.441
</td>

<td style="text-align:right;">

0.576
</td>

</tr>

<tr>

<td style="text-align:left;">

AVE.Socializer
</td>

<td style="text-align:right;">

0.670
</td>

<td style="text-align:right;">

0.612
</td>

<td style="text-align:right;">

0.725
</td>

</tr>

</tbody>

</table>

#### CFA fit indices with 95% CI using bootstrapping with 10,000 samples (Sensitivy analysis:without “fast_responders” \< 52.28sec )

    ## [1] 650  25

<table class="table table-striped table-hover table-condensed table-responsive" style="color: black; width: auto !important; margin-left: auto; margin-right: auto;">

<caption>

CFA metrics with confident interval
</caption>

<thead>

<tr>

<th style="text-align:left;">

Metric
</th>

<th style="text-align:right;">

Estimate
</th>

<th style="text-align:right;">

CI_Lower
</th>

<th style="text-align:right;">

CI_Upper
</th>

</tr>

</thead>

<tbody>

<tr>

<td style="text-align:left;">

chisq.scaled
</td>

<td style="text-align:right;">

77.320
</td>

<td style="text-align:right;">

64.277
</td>

<td style="text-align:right;">

132.580
</td>

</tr>

<tr>

<td style="text-align:left;">

srmr
</td>

<td style="text-align:right;">

0.026
</td>

<td style="text-align:right;">

0.027
</td>

<td style="text-align:right;">

0.043
</td>

</tr>

<tr>

<td style="text-align:left;">

tli.scaled
</td>

<td style="text-align:right;">

0.914
</td>

<td style="text-align:right;">

0.685
</td>

<td style="text-align:right;">

0.917
</td>

</tr>

<tr>

<td style="text-align:left;">

cfi.scaled
</td>

<td style="text-align:right;">

0.949
</td>

<td style="text-align:right;">

0.814
</td>

<td style="text-align:right;">

0.951
</td>

</tr>

<tr>

<td style="text-align:left;">

rmsea.scaled
</td>

<td style="text-align:right;">

0.034
</td>

<td style="text-align:right;">

0.032
</td>

<td style="text-align:right;">

0.061
</td>

</tr>

</tbody>

</table>

#### Appendix A13. Standardized Residuals for the Hexad-12 items from the CFA

<table class="kable_wrapper">

<caption>

Standardized Residuals for the Hexad-12 items from the CFA
</caption>

<tbody>

<tr>

<td>

| x            |
|:-------------|
| standardized |

</td>

<td>

|  | A2 | A4 | D3 | D4 | F1 | F3 | P1 | P4 | R2 | R4 | S2 | S4 |
|:---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| A2 | 0.000 | 0.000 | 1.440 | 0.150 | -1.056 | 1.468 | -0.298 | -2.295 | -0.560 | -0.921 | 1.984 | 1.439 |
| A4 | 0.000 | 0.000 | -0.100 | -1.113 | -1.045 | 1.046 | 2.628 | 0.974 | -0.977 | 2.708 | -1.844 | -1.547 |
| D3 | 1.440 | -0.100 | 0.000 | 0.000 | 1.244 | 0.704 | -0.015 | -0.812 | -1.361 | -0.840 | 0.525 | 0.067 |
| D4 | 0.150 | -1.113 | 0.000 | 0.000 | 0.983 | -2.826 | 2.289 | -1.642 | 0.210 | 1.795 | -0.167 | -0.337 |
| F1 | -1.056 | -1.045 | 1.244 | 0.983 | 0.000 | 0.000 | -0.533 | -2.289 | -0.554 | 3.620 | -0.639 | 1.376 |
| F3 | 1.468 | 1.046 | 0.704 | -2.826 | 0.000 | 0.000 | 2.587 | 0.816 | -2.281 | -0.836 | -0.631 | -0.226 |
| P1 | -0.298 | 2.628 | -0.015 | 2.289 | -0.533 | 2.587 | 0.000 | 0.000 | 1.277 | 1.709 | -1.929 | -0.921 |
| P4 | -2.295 | 0.974 | -0.812 | -1.642 | -2.289 | 0.816 | 0.000 | 0.000 | -0.235 | -2.554 | 0.929 | 1.306 |
| R2 | -0.560 | -0.977 | -1.361 | 0.210 | -0.554 | -2.281 | 1.277 | -0.235 | 0.000 | 0.000 | 2.901 | 0.851 |
| R4 | -0.921 | 2.708 | -0.840 | 1.795 | 3.620 | -0.836 | 1.709 | -2.554 | 0.000 | 0.000 | -0.927 | -2.877 |
| S2 | 1.984 | -1.844 | 0.525 | -0.167 | -0.639 | -0.631 | -1.929 | 0.929 | 2.901 | -0.927 | 0.000 | 0.000 |
| S4 | 1.439 | -1.547 | 0.067 | -0.337 | 1.376 | -0.226 | -0.921 | 1.306 | 0.851 | -2.877 | 0.000 | 0.000 |

</td>

</tr>

</tbody>

</table>

#### Appendix A14. Correlation Residuals for the Hexad-12 items from the CFA

<table class="kable_wrapper">

<caption>

Correlation Residuals for the Hexad-12 items from the CFA
</caption>

<tbody>

<tr>

<td>

| x          |
|:-----------|
| cor.bollen |

</td>

<td>

|  | A2 | A4 | D3 | D4 | F1 | F3 | P1 | P4 | R2 | R4 | S2 | S4 |
|:---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| A2 | 0.000 | 0.000 | 0.035 | 0.003 | -0.021 | 0.031 | -0.006 | -0.041 | -0.011 | -0.018 | 0.040 | 0.025 |
| A4 | 0.000 | 0.000 | -0.002 | -0.021 | -0.022 | 0.023 | 0.057 | 0.019 | -0.019 | 0.056 | -0.030 | -0.024 |
| D3 | 0.035 | -0.002 | 0.000 | 0.000 | 0.024 | 0.015 | 0.000 | -0.016 | -0.031 | -0.019 | 0.009 | 0.001 |
| D4 | 0.003 | -0.021 | 0.000 | 0.000 | 0.018 | -0.057 | 0.039 | -0.031 | 0.004 | 0.038 | -0.003 | -0.005 |
| F1 | -0.021 | -0.022 | 0.024 | 0.018 | 0.000 | 0.000 | -0.010 | -0.037 | -0.009 | 0.078 | -0.009 | 0.020 |
| F3 | 0.031 | 0.023 | 0.015 | -0.057 | 0.000 | 0.000 | 0.051 | 0.014 | -0.041 | -0.017 | -0.010 | -0.003 |
| P1 | -0.006 | 0.057 | 0.000 | 0.039 | -0.010 | 0.051 | 0.000 | 0.000 | 0.025 | 0.027 | -0.029 | -0.014 |
| P4 | -0.041 | 0.019 | -0.016 | -0.031 | -0.037 | 0.014 | 0.000 | 0.000 | -0.004 | -0.042 | 0.015 | 0.025 |
| R2 | -0.011 | -0.019 | -0.031 | 0.004 | -0.009 | -0.041 | 0.025 | -0.004 | 0.000 | 0.000 | 0.057 | 0.017 |
| R4 | -0.018 | 0.056 | -0.019 | 0.038 | 0.078 | -0.017 | 0.027 | -0.042 | 0.000 | 0.000 | -0.016 | -0.054 |
| S2 | 0.040 | -0.030 | 0.009 | -0.003 | -0.009 | -0.010 | -0.029 | 0.015 | 0.057 | -0.016 | 0.000 | 0.000 |
| S4 | 0.025 | -0.024 | 0.001 | -0.005 | 0.020 | -0.003 | -0.014 | 0.025 | 0.017 | -0.054 | 0.000 | 0.000 |

</td>

</tr>

</tbody>

</table>

#### Appendix A15. Modification indices Hexad-12 scale

|     | Path       |     |     |    MI |    EPC | Std.EPC |
|:----|:-----------|:----|:----|------:|-------:|--------:|
| 105 | Socializer | =~  | R4  | 5.755 |  0.146 |   0.136 |
| 104 | Socializer | =~  | R2  | 5.755 | -0.147 |  -0.146 |
| 148 | F1         | \~~ | R4  | 4.734 | -0.203 |  -0.264 |
| 71  | FreeSpirit | =~  | P4  | 3.631 |  0.299 |   0.195 |
| 70  | FreeSpirit | =~  | P1  | 3.631 | -0.315 |  -0.235 |
| 137 | D4         | \~~ | F3  | 3.459 |  0.197 |   0.232 |
| 170 | R4         | \~~ | S4  | 3.393 |  0.207 |   0.191 |
| 167 | R2         | \~~ | S2  | 3.321 | -0.209 |  -0.229 |
| 93  | Player     | =~  | P4  | 3.147 |  0.127 |   0.096 |
| 92  | Player     | =~  | P1  | 3.147 | -0.134 |  -0.116 |

Modification indices Hexad-12 scale

## 4.6. Reliability

#### Table 5: Reliability metrics

|  |  |  |  |  |  |  |
|:---|:---|:---|:---|:---|:---|:---|
| Subscale | Philanthropist | Socializer | Achiever | Player | Disruptor | Free Spirit |
| SB_Estimate | 0.76 | 0.80 | 0.63 | 0.68 | 0.72 | 0.74 |
| SB_CI_Lower | 0.70 | 0.76 | 0.54 | 0.61 | 0.68 | 0.67 |
| SB_CI_Upper | 0.82 | 0.84 | 0.71 | 0.73 | 0.76 | 0.80 |
| Omega_Estimate | 0.76 | 0.80 | 0.63 | 0.68 | 0.72 | 0.74 |
| Omega_CI_Lower | 0.70 | 0.76 | 0.53 | 0.61 | 0.68 | 0.66 |
| Omega_CI_Upper | 0.82 | 0.84 | 0.71 | 0.73 | 0.76 | 0.80 |
| OrdOmega_Estimate | 0.84 | 0.85 | 0.72 | 0.75 | 0.77 | 0.83 |
| OrdOmega_CI_Lower | 0.80 | 0.82 | 0.65 | 0.69 | 0.73 | 0.78 |
| OrdOmega_CI_Upper | 0.87 | 0.88 | 0.78 | 0.79 | 0.80 | 0.87 |

Reliability Table for Hexad-12 Subscales

| Subscale       | OrdCR_Estimate | OrdCR_CI_Lower | OrdCR_CI_Upper |
|:---------------|---------------:|---------------:|---------------:|
| Philanthropist |           0.86 |           0.83 |           0.89 |
| Socializer     |           0.87 |           0.85 |           0.89 |
| Achiever       |           0.78 |           0.74 |           0.82 |
| Player         |           0.80 |           0.77 |           0.83 |
| Disruptor      |           0.81 |           0.79 |           0.83 |
| Free Spirit    |           0.85 |           0.82 |           0.88 |

Oridinal CR for Hexad-12 Subscales

## 4.7. Convergent and discriminant validity

#### Appendix A16. Heterotrait–Monotrait (HTMT) ratios

    ## 
    ## Maximum HTMT: 0.705  | Strict OK (< .85)? TRUE  | Lenient OK (< .90)? TRUE

    ## 
    ## 
    ## Table: HTMT (polychoric) with 95% bootstrap CIs; max HTMT = 0.705  [R_boot = 10000]
    ## 
    ## |Factor1        |Factor2    |  HTMT| CI_lower| CI_upper|
    ## |:--------------|:----------|-----:|--------:|--------:|
    ## |Philanthropist |Socializer | 0.705|    0.637|    0.770|
    ## |Philanthropist |FreeSpirit | 0.612|    0.521|    0.695|
    ## |Philanthropist |Achiever   | 0.440|    0.326|    0.551|
    ## |Philanthropist |Player     | 0.313|    0.212|    0.413|
    ## |Philanthropist |Disruptor  | 0.161|    0.067|    0.260|
    ## |Socializer     |FreeSpirit | 0.412|    0.311|    0.506|
    ## |Socializer     |Achiever   | 0.368|    0.271|    0.462|
    ## |Socializer     |Player     | 0.357|    0.258|    0.453|
    ## |Socializer     |Disruptor  | 0.243|    0.149|    0.334|
    ## |FreeSpirit     |Achiever   | 0.662|    0.560|    0.760|
    ## |FreeSpirit     |Player     | 0.455|    0.356|    0.551|
    ## |FreeSpirit     |Disruptor  | 0.105|    0.050|    0.197|
    ## |Achiever       |Player     | 0.543|    0.437|    0.647|
    ## |Achiever       |Disruptor  | 0.042|    0.025|    0.145|
    ## |Player         |Disruptor  | 0.067|    0.026|    0.172|

#### Table 6 Bivariate correlation coefficients Kendall’s tau between the Hexad subscales

<table class="table table-striped table-hover table-condensed table-responsive" style="color: black; width: auto !important; margin-left: auto; margin-right: auto;">

<caption>

Lower Triangle of Kendall Tau Correlation Matrix with Significance. Significance Legend: \*\*\* p \< 0.001, \*\* p \< 0.01, \* p \< 0.05
</caption>

<thead>

<tr>

<th style="text-align:left;">

</th>

<th style="text-align:left;">

Philanthropic
</th>

<th style="text-align:left;">

Socializer
</th>

<th style="text-align:left;">

Achiever
</th>

<th style="text-align:left;">

Player
</th>

<th style="text-align:left;">

Disruptor
</th>

<th style="text-align:left;">

Free Spirit
</th>

</tr>

</thead>

<tbody>

<tr>

<td style="text-align:left;">

Philanthropic
</td>

<td style="text-align:left;">

1.000
</td>

<td style="text-align:left;">

</td>

<td style="text-align:left;">

</td>

<td style="text-align:left;">

</td>

<td style="text-align:left;">

</td>

<td style="text-align:left;">

</td>

</tr>

<tr>

<td style="text-align:left;">

Socializer
</td>

<td style="text-align:left;">

0.397\*\*\*
</td>

<td style="text-align:left;">

1.000
</td>

<td style="text-align:left;">

</td>

<td style="text-align:left;">

</td>

<td style="text-align:left;">

</td>

<td style="text-align:left;">

</td>

</tr>

<tr>

<td style="text-align:left;">

Achiever
</td>

<td style="text-align:left;">

0.221\*\*\*
</td>

<td style="text-align:left;">

0.194\*\*\*
</td>

<td style="text-align:left;">

1.000
</td>

<td style="text-align:left;">

</td>

<td style="text-align:left;">

</td>

<td style="text-align:left;">

</td>

</tr>

<tr>

<td style="text-align:left;">

Player
</td>

<td style="text-align:left;">

0.171\*\*\*
</td>

<td style="text-align:left;">

0.218\*\*\*
</td>

<td style="text-align:left;">

0.261\*\*\*
</td>

<td style="text-align:left;">

1.000
</td>

<td style="text-align:left;">

</td>

<td style="text-align:left;">

</td>

</tr>

<tr>

<td style="text-align:left;">

Disruptor
</td>

<td style="text-align:left;">

-0.091\*\*
</td>

<td style="text-align:left;">

-0.122\*\*\*
</td>

<td style="text-align:left;">

0.022
</td>

<td style="text-align:left;">

0.036
</td>

<td style="text-align:left;">

1.000
</td>

<td style="text-align:left;">

</td>

</tr>

<tr>

<td style="text-align:left;">

Free Spirit
</td>

<td style="text-align:left;">

0.29\*\*\*
</td>

<td style="text-align:left;">

0.201\*\*\*
</td>

<td style="text-align:left;">

0.341\*\*\*
</td>

<td style="text-align:left;">

0.237\*\*\*
</td>

<td style="text-align:left;">

0.053\*
</td>

<td style="text-align:left;">

1.000
</td>

</tr>

</tbody>

</table>

#### Appendix A17. Latent correlations among Hexad determinants

|     | Factor 1       | Factor 2       | Latent r | 95% CI Lower | 95% CI Upper |
|:----|:---------------|:---------------|---------:|-------------:|-------------:|
| 31  | Achiever       | Disruptor      |    0.033 |       -0.056 |        0.119 |
| 32  | Achiever       | FreeSpirit     |    0.565 |        0.225 |        0.463 |
| 33  | Achiever       | Philanthropist |    0.339 |        0.118 |        0.358 |
| 34  | Achiever       | Player         |    0.443 |        0.194 |        0.432 |
| 35  | Achiever       | Socializer     |    0.299 |        0.174 |        0.392 |
| 36  | Disruptor      | FreeSpirit     |    0.057 |       -0.049 |        0.192 |
| 37  | Disruptor      | Philanthropist |   -0.139 |       -0.350 |       -0.056 |
| 38  | Disruptor      | Player         |    0.071 |       -0.041 |        0.251 |
| 39  | Disruptor      | Socializer     |   -0.208 |       -0.622 |       -0.197 |
| 40  | FreeSpirit     | Philanthropist |    0.598 |        0.375 |        0.746 |
| 41  | FreeSpirit     | Player         |    0.353 |        0.218 |        0.446 |
| 42  | FreeSpirit     | Socializer     |    0.356 |        0.288 |        0.611 |
| 43  | Philanthropist | Player         |    0.227 |        0.123 |        0.371 |
| 44  | Philanthropist | Socializer     |    0.663 |        0.735 |        1.197 |
| 45  | Player         | Socializer     |    0.273 |        0.246 |        0.555 |

Latent correlations among Hexad determinants

## 4.8. Criterion-related and group-level analyses

### Game frequency-related patterns in Hexad-12 scores.

#### Appendix A18. Correlations between Hexad determinants and gaming frequency

| Determinant    |   n |    tau | p_value |
|:---------------|----:|-------:|--------:|
| philanthropist | 648 | -0.054 |   0.092 |
| socializer     | 648 | -0.067 |   0.031 |
| freeSpirit     | 648 | -0.059 |   0.075 |
| achiever       | 648 | -0.078 |   0.016 |
| player         | 648 |  0.013 |   0.673 |
| disruptor      | 648 |  0.026 |   0.394 |

Correlations between Hexad determinants and gaming frequency

#### Appendix A19. Kruskal–Wallis test for Hexad determinants by gaming frequency

| Determinant    | n_total | n_groups | statistic |  df | p_value |
|:---------------|--------:|---------:|----------:|----:|--------:|
| achiever       |     648 |        3 |      2.03 |   2 |   0.362 |
| disruptor      |     648 |        3 |      3.63 |   2 |   0.163 |
| freeSpirit     |     648 |        3 |      5.72 |   2 |   0.057 |
| philanthropist |     648 |        3 |      0.93 |   2 |   0.627 |
| player         |     648 |        3 |      1.07 |   2 |   0.586 |
| socializer     |     648 |        3 |      2.14 |   2 |   0.343 |

Kruskal–Wallis test for Hexad determinants by gaming frequency

#### Multigroup Confirmatory factor Analysis

    ## 
    ## 1-2 days 3-4 days 5-7 days     <NA> 
    ##      379      133      136      218

    ## 
    ## 1-2 days 3-4 days 5-7 days 
    ##      379      133      136

    ## [1] 648

    ## 
    ## Scaled Chi-Squared Difference Test (method = "satorra.bentler.2001")
    ## 
    ## lavaan->lavTestLRT():  
    ##    lavaan NOTE: The "Chisq" column contains standard test statistics, not the 
    ##    robust test that should be reported per model. A robust difference test is 
    ##    a function of two standard (not robust) statistics.
    ##             Df   AIC   BIC  Chisq Chisq diff Df diff Pr(>Chisq)  
    ## fit_config 117 24902 25587 152.87                                
    ## fit_metric 129 24910 25541 184.59     22.936      12    0.02828 *
    ## fit_scalar 141 24905 25482 203.73     19.524      12    0.07664 .
    ## ---
    ## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1

    ##          cfi rmsea  srmr
    ## config 0.984 0.038 0.037
    ## metric 0.975 0.045 0.043
    ## scalar 0.971 0.045 0.044

### Gender-related patterns in Hexad-12 scores.

#### Appendix A20. Kruskal–Wallis test for Hexad determinants by Gender

    ## [1] 628  26

| Determinant    |   n | n_groups | statistic |  df | p_value |
|:---------------|----:|---------:|----------:|----:|--------:|
| philanthropist | 628 |        3 |      7.76 |   2 |   0.021 |
| socializer     | 628 |        3 |      0.13 |   2 |   0.937 |
| freeSpirit     | 628 |        3 |      5.87 |   2 |   0.053 |
| achiever       | 628 |        3 |      5.07 |   2 |   0.079 |
| player         | 628 |        3 |      0.38 |   2 |   0.826 |
| disruptor      | 628 |        3 |      3.06 |   2 |   0.217 |

Kruskal–Wallis test for Hexad determinants by Gender

#### Multigroup Confirmatory factor Analysis

    ## 
    ## Female   Male 
    ##    369    256

    ## [1] 625

    ## 
    ## Scaled Chi-Squared Difference Test (method = "satorra.bentler.2001")
    ## 
    ## lavaan->lavTestLRT():  
    ##    lavaan NOTE: The "Chisq" column contains standard test statistics, not the 
    ##    robust test that should be reported per model. A robust difference test is 
    ##    a function of two standard (not robust) statistics.
    ##            Df   AIC   BIC   Chisq Chisq diff Df diff Pr(>Chisq)   
    ## fit_config 78 23961 24414  99.598                                 
    ## fit_metric 84 23955 24381 105.049      3.658       6   0.722839   
    ## fit_scalar 90 23961 24360 123.042     19.016       6   0.004137 **
    ## ---
    ## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1

    ##          cfi rmsea  srmr
    ## config 0.988 0.030 0.030
    ## metric 0.988 0.028 0.033
    ## scalar 0.982 0.034 0.035

### Age-related patterns in Hexad-12 scores.

#### Appendix A21. Correlations between Hexad determinants and Age

| Determinant    |   n |    tau | p_value |
|:---------------|----:|-------:|--------:|
| philanthropist | 737 |  0.143 |   0.000 |
| socializer     | 737 |  0.062 |   0.020 |
| freeSpirit     | 737 |  0.018 |   0.517 |
| achiever       | 737 |  0.006 |   0.828 |
| player         | 737 | -0.098 |   0.000 |
| disruptor      | 737 | -0.005 |   0.839 |

Correlations between Hexad determinants and Age

#### Appendix A22. Kruskal–Wallis test for Hexad determinants by Age Group

| Determinant    |   n | n_groups | statistic |  df | p_value |
|:---------------|----:|---------:|----------:|----:|--------:|
| philanthropist | 737 |        4 |     33.01 |   3 |   0.000 |
| socializer     | 737 |        4 |      4.94 |   3 |   0.176 |
| freeSpirit     | 737 |        4 |      7.29 |   3 |   0.063 |
| achiever       | 737 |        4 |      9.26 |   3 |   0.026 |
| player         | 737 |        4 |     22.11 |   3 |   0.000 |
| disruptor      | 737 |        4 |      0.14 |   3 |   0.987 |

Kruskal–Wallis test for Hexad determinants by Age Group

#### Dunn post-hoc tests

    ## [1] "philanthropist" "player"

    ## # A tibble: 12 × 5
    ##    Determinant    Comparison          Z P.unadj   P.adj
    ##    <chr>          <chr>           <dbl>   <dbl>   <dbl>
    ##  1 philanthropist 18–24 - 25–34 -3.80   0.00014 0.00043
    ##  2 philanthropist 18–24 - 35–49 -3.74   0.00019 0.00037
    ##  3 philanthropist 25–34 - 35–49 -0.161  0.872   0.872  
    ##  4 philanthropist 18–24 - 50+   -5.43   0       0      
    ##  5 philanthropist 25–34 - 50+   -1.48   0.138   0.207  
    ##  6 philanthropist 35–49 - 50+   -1.23   0.217   0.261  
    ##  7 player         18–24 - 25–34 -0.954  0.340   0.510  
    ##  8 player         18–24 - 35–49 -0.0417 0.967   0.967  
    ##  9 player         25–34 - 35–49  0.820  0.412   0.495  
    ## 10 player         18–24 - 50+    3.56   0.00037 0.00112
    ## 11 player         25–34 - 50+    4.32   0.00002 0.00009
    ## 12 player         35–49 - 50+    3.24   0.0012  0.00241

#### Multigroup Confirmatory factor Analysis

    ## 
    ## 18–24 25–34 35–49   50+ 
    ##   219   180   145   193

    ##             Df      AIC      BIC   Chisq Chisq diff Df diff Pr(>Chisq)
    ## fit_config 156 28359.83 29298.76 233.285         NA      NA         NA
    ## fit_metric 174 28361.49 29217.57 270.942     20.452      18    0.30795
    ## fit_scalar 192 28366.05 29139.28 311.501     40.431      18    0.00182

    ##    Model   cfi rmsea  srmr
    ## 1 config 0.968 0.052 0.043
    ## 2 metric 0.960 0.055 0.050
    ## 3 scalar 0.951 0.058 0.054

## Country-related patterns in Hexad-12 scores.

#### Appendix A23. Kruskal–Wallis test for Hexad determinants by top 10 countries

| Determinant    |   n | n_groups | statistic |  df | p_value |
|:---------------|----:|---------:|----------:|----:|--------:|
| philanthropist | 669 |       10 |     16.17 |   9 |   0.063 |
| socializer     | 669 |       10 |     15.83 |   9 |   0.070 |
| freeSpirit     | 669 |       10 |      6.53 |   9 |   0.686 |
| achiever       | 669 |       10 |     21.76 |   9 |   0.010 |
| player         | 669 |       10 |     13.42 |   9 |   0.145 |
| disruptor      | 669 |       10 |     11.68 |   9 |   0.232 |

Kruskal–Wallis test for Hexad determinants by Age Group

#### Multigroup Confirmatory factor Analysis

    ## 
    ## Counts per Region3:

    ## 
    ## Central_America_Mex_Caribbean               Northern_Andean 
    ##                           108                           308 
    ##                 Southern_Cone 
    ##                           253

    ## 
    ## Scaled Chi-Squared Difference Test (method = "satorra.bentler.2001")
    ## 
    ## lavaan->lavTestLRT():  
    ##    lavaan NOTE: The "Chisq" column contains standard test statistics, not the 
    ##    robust test that should be reported per model. A robust difference test is 
    ##    a function of two standard (not robust) statistics.
    ##             Df   AIC   BIC  Chisq Chisq diff Df diff Pr(>Chisq)
    ## fit_config 117 25592 26281 154.93                              
    ## fit_metric 129 25582 26217 168.79      8.837      12     0.7168
    ## fit_scalar 141 25570 26151 181.12     12.847      12     0.3803

    ## 
    ## Fit Indices (Robust):

    ##          CFI RMSEA  SRMR
    ## config 0.981 0.037 0.034
    ## metric 0.983 0.033 0.037
    ## scalar 0.983 0.032 0.039
