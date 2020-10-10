#    Heroes of Pymoli Game





# Heros of Pymoli Data Analysis Observations:
•As the Total Purchase count is 780, the number of unique players 573.

• Most of the players have repeated their purchases for the Heroes of Pymoli game.

• The game is more popular among male players. The vast majority of players are male (84%);however, female and other/non-disclosed players spent more per person, $4.47 & $4.56 respectively versus $4.07 for males.

• A majority of players fall into the <20-24> (44.79%)age bracket though the age bracket that spent the most per person is 35-39 at $4.76 per player.

• The most popular item is also the most profitable, Oathbreaker, Last Hope of the Breaking Storm.

# Final Report includes each of the following:

[]: https://github.com/fereshtehaghaei/Pandas-Challenge/blob/master/HeroesOfPymoli/HeroesOfPymoli_starter.ipynb


# Purchase Data

| Purchase ID |   SN |           Age | Gender | Item ID | Item Name |                                     Price |      |
| ----------: | ---: | ------------: | -----: | ------: | --------: | ----------------------------------------: | ---- |
|           0 |    0 |       Lisim78 |     20 |    Male |       108 | Extraction, Quickblade Of Trembling Hands | 3.53 |
|           1 |    1 |   Lisovynya38 |     40 |    Male |       143 |                         Frenzied Scimitar | 1.56 |
|           2 |    2 |    Ithergue48 |     24 |    Male |        92 |                              Final Critic | 4.88 |
|           3 |    3 | Chamassasya86 |     24 |    Male |       100 |                               Blindscythe | 3.27 |
|           4 |    4 |     Iskosia90 |     23 |    Male |       131 |                                      Fury | 1.44 |

## Player Count

- Display the total number of players

|      | Total Players |
| ---: | ------------: |
|    0 |           576 |



## Purchasing Analysis (Total)

- Run basic calculations to obtain number of unique items, average price, etc.

- Create a summary data frame to hold the results

- Optional: give the displayed data cleaner formatting

- Display the summary data frame



|      | Number of Unique Items | Average Price | Number of Purchases | Total Revenue |
| ---: | ---------------------: | ------------: | ------------------: | ------------: |
|    0 |                    179 |         $3.05 |                 780 |     $2,379.77 |



## Gender Demographics

- Run basic calculations to obtain number of unique items, average price, etc.
- Create a summary data frame to hold the results
- Optional: give the displayed data cleaner formatting
- Display the summary data frame

|                       | Total Count | Percentage of Players |
| --------------------: | ----------: | --------------------: |
|                Gender |             |                       |
|                  Male |         484 |                84.03% |
|                Female |          81 |                14.06% |
| Other / Non-Disclosed |          11 |                 1.91% |



## Purchasing Analysis (Gender)

- Run basic calculations to obtain purchase count, avg. purchase price, avg. purchase total per person etc. by gender

- Create a summary data frame to hold the results

- Optional: give the displayed data cleaner formatting

- Display the summary data frame

|                       | Purchase Count | Average Purchase Price | Total Purchase Value | AVG Total Purchase per Person |
| --------------------: | -------------: | ---------------------: | -------------------: | ----------------------------: |
|                Gender |                |                        |                      |                               |
|                Female |            113 |                  $3.20 |              $361.94 |                         $4.47 |
|                  Male |            652 |                  $3.02 |             $1967.64 |                         $4.07 |
| Other / Non-Disclosed |             15 |                  $3.35 |               $50.19 |                         $4.56 |

## Age Demographics

- Establish bins for ages

- Categorize the existing players using the age bins. Hint: use pd.cut()

- Calculate the numbers and percentages by age group

- Create a summary data frame to hold the results

- Optional: round the percentage column to two decimal points

- Display Age Demographics Table

 

|       | Total Count | Percent of Players |
| ----: | ----------: | -----------------: |
|   <10 |          17 |              2.95% |
| 10-14 |          22 |              3.82% |
| 15-19 |         107 |             18.58% |
| 20-24 |         258 |             44.79% |
| 25-29 |          77 |             13.37% |
| 30-34 |          52 |              9.03% |
| 35-39 |          31 |              5.38% |
|   40+ |          12 |              2.08% |

## Purchasing Analysis (Age)

- Bin the purchase_data data frame by age

- Run basic calculations to obtain purchase count, avg. purchase price, avg. purchase total per person etc. in the table below

- Create a summary data frame to hold the results

- Optional: give the displayed data cleaner formatting

- Display the summary data frame



|       | Purchase Count | Average Purchase Price | Total Purchase Value | Avg Total Purchase per Person |
| ----: | -------------: | ---------------------: | -------------------: | ----------------------------: |
|   <10 |             23 |                  $3.35 |               $77.13 |                         $4.54 |
| 10-14 |             28 |                  $2.96 |               $82.78 |                         $3.76 |
| 15-19 |            136 |                  $3.04 |              $412.89 |                         $3.86 |
| 20-24 |            365 |                  $3.05 |            $1,114.06 |                         $4.32 |
| 25-29 |            101 |                  $2.90 |              $293.00 |                         $3.81 |
| 30-34 |             73 |                  $2.93 |              $214.00 |                         $4.12 |
| 35-39 |             41 |                  $3.60 |              $147.67 |                         $4.76 |
|   40+ |             13 |                  $2.94 |               $38.24 |                         $3.19 |



## Top Spenders

- Run basic calculations to obtain the results in the table below

- Create a summary data frame to hold the results

- Sort the total purchase value column in descending order

- Optional: give the displayed data cleaner formatting

- Display a preview of the summary data frame

|             | Purchase Count | Average Purchase Price | Total Purchase Value |
| ----------: | -------------: | ---------------------: | -------------------: |
|          SN |                |                        |                      |
|   Lisosia93 |              5 |                  $3.79 |               $18.96 |
| Idastidru52 |              4 |                  $3.86 |               $15.45 |
|  Chamjask73 |              3 |                  $4.61 |               $13.83 |
|      Iral74 |              4 |                  $3.40 |               $13.62 |
| Iskadarya95 |              3 |                  $4.37 |               $13.10 |

## Most Popular Items

- Retrieve the Item ID, Item Name, and Item Price columns

- Group by Item ID and Item Name. Perform calculations to obtain purchase count, item price, and total purchase value

- Create a summary data frame to hold the results

- Sort the purchase count column in descending order

- Optional: give the displayed data cleaner formatting

- Display a preview of the summary data frame

|         |                                              | Purchase Count | Item Price | Total Purchase Value |
| ------: | -------------------------------------------: | -------------: | ---------: | -------------------: |
| Item ID |                                    Item Name |                |            |                      |
|      92 |                                 Final Critic |             13 |      $4.61 |               $59.99 |
|     178 | Oathbreaker, Last Hope of the Breaking Storm |             12 |      $4.23 |               $50.76 |
|     145 |                         Fiery Glass Crusader |              9 |      $4.58 |               $41.22 |
|     132 |                                   Persuasion |              9 |      $3.22 |               $28.99 |
|     108 |    Extraction, Quickblade Of Trembling Hands |              9 |      $3.53 |               $31.77 |



# Most Profitable Items

- Sort the above table by total purchase value in descending order

- Optional: give the displayed data cleaner formatting

- Display a preview of the data frame



|         |                                              | Purchase Count | Item Price | Total Purchase Value |
| ------: | -------------------------------------------: | -------------: | ---------: | -------------------: |
| Item ID |                                    Item Name |                |            |                      |
|      92 |                                 Final Critic |             13 |      $4.61 |               $59.99 |
|     178 | Oathbreaker, Last Hope of the Breaking Storm |             12 |      $4.23 |               $50.76 |
|      82 |                                      Nirvana |              9 |      $4.90 |               $44.10 |
|     145 |                         Fiery Glass Crusader |              9 |      $4.58 |               $41.22 |
|     103 |                               Singed Scalpel |              8 |      $4.35 |               $34.80 |

