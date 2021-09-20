# A mock catalogue for the S2 star

We have produced a mock catalogue for the S2 star in the Galactic Centre, considering a relativistic orbital model in a Schwarzschild spacetime (assuming that SgrA* is a non rotating black hole described by General Relativity) and generated 304 simulated astrometric positions and radial velocity measurements as could be potentially measured by the GRAVITY instrument at VLT in next four orbital periods of S2.

The catalogue has been built by numerically integrating the geodesic equation with the package [PyGRO](https://github.com/rdellamonica/pygro).

In the [Jupyter notebook](https://github.com/rdellamonica/S2-gr-mock-catalogue/blob/d489083d57a85c24aedcb596e7e1c645d2794126/S2%20-%20Mock%20Catalogue.ipynb) you can follow the entire detailed pipeline for the production of the catalogue.

### Plot

![Plot of the S2 mock catalogue](plots/mock_catalogue_plot.png) 

### Table

| |t (yr)        | Date    |RA (as)     |Dec (as)    |VR  (km/s) |
|------|----------|----------|--------|--------|-----|
|0     |2018.08214|2018-30-01|-0.03234|-0.00568|3305 |
|1     |2018.16427|2018-01-03|-0.02632|-0.00960|3674 |
|2     |2018.24641|2018-31-03|-0.01828|-0.01272|4040 |
|3     |2018.26557|2018-07-04|-0.01599|-0.01320|4107 |
|4     |2018.28474|2018-14-04|-0.01351|-0.01354|4094 |
|5     |2018.30390|2018-21-04|-0.01085|-0.01365|4055 |
|6     |2018.32307|2018-28-04|-0.00796|-0.01349|3882 |
|7     |2018.32854|2018-30-04|-0.00711|-0.01340|3803 |
|8     |2018.33402|2018-02-05|-0.00623|-0.01326|3737 |
|9     |2018.33949|2018-04-05|-0.00534|-0.01310|3649 |
|10    |2018.34497|2018-06-05|-0.00443|-0.01291|3515 |
|11    |2018.35044|2018-08-05|-0.00352|-0.01271|3403 |
|12    |2018.35592|2018-10-05|-0.00260|-0.01243|3253 |
|13    |2018.35866|2018-11-05|-0.00214|-0.01230|3195 |
|14    |2018.36140|2018-12-05|-0.00166|-0.01213|3096 |
|15    |2018.36413|2018-13-05|-0.00120|-0.01199|3022 |
|16    |2018.36687|2018-14-05|-0.00073|-0.01182|2948 |
|17    |2018.36961|2018-15-05|-0.00025|-0.01166|2838 |
|18    |2018.37235|2018-16-05|0.00021 |-0.01147|2771 |
|19    |2018.37509|2018-17-05|0.00067 |-0.01129|2670 |
|20    |2018.37782|2018-18-05|0.00115 |-0.01109|2555 |
|21    |2018.38056|2018-19-05|0.00162 |-0.01086|2477 |
|22    |2018.38330|2018-20-05|0.00208 |-0.01066|2387 |
|23    |2018.38604|2018-21-05|0.00254 |-0.01044|2272 |
|24    |2018.38877|2018-22-05|0.00302 |-0.01021|2164 |
|25    |2018.39151|2018-23-05|0.00348 |-0.00997|2088 |
|26    |2018.39425|2018-24-05|0.00395 |-0.00973|1971 |
|27    |2018.39973|2018-26-05|0.00486 |-0.00920|1757 |
|28    |2018.40520|2018-28-05|0.00575 |-0.00867|1561 |
|29    |2018.41068|2018-30-05|0.00664 |-0.00809|1336 |
|30    |2018.41615|2018-01-06|0.00751 |-0.00753|1125 |
|31    |2018.43532|2018-08-06|0.01037 |-0.00533|446  |
|32    |2018.45448|2018-15-06|0.01298 |-0.00298|-90  |
|33    |2018.53662|2018-15-07|0.02141 |0.00730 |-1355|
|34    |2018.61875|2018-14-08|0.02670 |0.01669 |-1726|
|35    |2018.70089|2018-13-09|0.03028 |0.02509 |-1818|
|36    |2018.78303|2018-13-10|0.03279 |0.03265 |-1836|
|37    |2018.86516|2018-12-11|0.03464 |0.03950 |-1806|
|38    |2018.94730|2018-12-12|0.03600 |0.04580 |-1763|
|39    |2019.02943|2019-11-01|0.03700 |0.05170 |-1710|
|40    |2019.11157|2019-10-02|0.03769 |0.05716 |-1669|
|41    |2019.19370|2019-12-03|0.03824 |0.06231 |-1617|
|42    |2019.27584|2019-11-04|0.03856 |0.06715 |-1587|
|43    |2019.35797|2019-11-05|0.03872 |0.07175 |-1536|
|44    |2019.85079|2019-07-11|0.03773 |0.09520 |-1330|
|45    |2020.34360|2020-05-05|0.03465 |0.11355 |-1177|
|46    |2020.83641|2020-01-11|0.03050 |0.12844 |-1050|
|47    |2021.32923|2021-01-05|0.02572 |0.14059 |-920 |
|48    |2021.82204|2021-28-10|0.02048 |0.15060 |-824 |
|49    |2022.31485|2022-25-04|0.01507 |0.15874 |-725 |
|50    |2022.80767|2022-22-10|0.00944 |0.16532 |-639 |
|51    |2023.30048|2023-20-04|0.00378 |0.17039 |-559 |
|52    |2023.79329|2023-17-10|-0.00194|0.17424 |-493 |
|53    |2024.28611|2024-14-04|-0.00766|0.17681 |-422 |
|54    |2024.77892|2024-11-10|-0.01329|0.17828 |-333 |
|55    |2025.27173|2025-10-04|-0.01888|0.17864 |-285 |
|56    |2025.76454|2025-07-10|-0.02433|0.17800 |-218 |
|57    |2026.25736|2026-04-04|-0.02963|0.17636 |-144 |
|58    |2026.75017|2026-01-10|-0.03481|0.17370 |-73  |
|59    |2027.24298|2027-30-03|-0.03976|0.17010 |-8   |
|60    |2027.73580|2027-26-09|-0.04448|0.16551 |58   |
|61    |2028.22861|2028-24-03|-0.04896|0.15997 |139  |
|62    |2028.72142|2028-20-09|-0.05311|0.15342 |215  |
|63    |2029.21424|2029-20-03|-0.05692|0.14590 |294  |
|64    |2029.70705|2029-16-09|-0.06032|0.13727 |376  |
|65    |2030.19986|2030-14-03|-0.06325|0.12759 |493  |
|66    |2030.69268|2030-10-09|-0.06556|0.11670 |599  |
|67    |2031.18549|2031-09-03|-0.06717|0.10458 |756  |
|68    |2031.67830|2031-05-09|-0.06787|0.09104 |867  |
|69    |2032.17112|2032-03-03|-0.06740|0.07597 |1049 |
|70    |2032.66393|2032-30-08|-0.06531|0.05907 |1270 |
|71    |2033.15674|2033-27-02|-0.06071|0.04001 |1601 |
|72    |2033.23888|2033-29-03|-0.05961|0.03657 |1657 |
|73    |2033.32101|2033-28-04|-0.05836|0.03305 |1733 |
|74    |2033.40315|2033-28-05|-0.05698|0.02946 |1807 |
|75    |2033.48528|2033-27-06|-0.05544|0.02581 |1900 |
|76    |2033.56742|2033-27-07|-0.05371|0.02205 |2005 |
|77    |2033.64956|2033-26-08|-0.05175|0.01820 |2123 |
|78    |2033.73169|2033-25-09|-0.04953|0.01427 |2233 |
|79    |2033.81383|2033-25-10|-0.04700|0.01025 |2401 |
|80    |2033.89596|2033-24-11|-0.04407|0.00615 |2571 |
|81    |2033.97810|2033-24-12|-0.04069|0.00198 |2776 |
|82    |2034.06023|2034-22-01|-0.03661|-0.00219|3026 |
|83    |2034.14237|2034-21-02|-0.03165|-0.00631|3331 |
|84    |2034.22450|2034-23-03|-0.02535|-0.01018|3729 |
|85    |2034.30664|2034-22-04|-0.01695|-0.01306|4090 |
|86    |2034.32580|2034-29-04|-0.01457|-0.01344|4104 |
|87    |2034.34497|2034-06-05|-0.01196|-0.01366|4077 |
|88    |2034.36413|2034-13-05|-0.00917|-0.01361|3963 |
|89    |2034.36961|2034-15-05|-0.00833|-0.01354|3923 |
|90    |2034.37509|2034-17-05|-0.00747|-0.01345|3848 |
|91    |2034.38056|2034-19-05|-0.00662|-0.01332|3753 |
|92    |2034.38604|2034-21-05|-0.00573|-0.01321|3676 |
|93    |2034.39151|2034-23-05|-0.00483|-0.01301|3559 |
|94    |2034.39699|2034-25-05|-0.00389|-0.01281|3440 |
|95    |2034.40246|2034-27-05|-0.00300|-0.01257|3290 |
|96    |2034.40520|2034-28-05|-0.00254|-0.01241|3232 |
|97    |2034.40794|2034-29-05|-0.00208|-0.01230|3168 |
|98    |2034.41068|2034-30-05|-0.00161|-0.01214|3063 |
|99    |2034.41342|2034-31-05|-0.00112|-0.01197|2982 |
|100   |2034.41615|2034-01-06|-0.00066|-0.01181|2925 |
|101   |2034.41889|2034-02-06|-0.00018|-0.01163|2830 |
|102   |2034.42163|2034-03-06|0.00030 |-0.01143|2743 |
|103   |2034.42437|2034-04-06|0.00073 |-0.01125|2636 |
|104   |2034.42710|2034-05-06|0.00122 |-0.01105|2548 |
|105   |2034.42984|2034-06-06|0.00170 |-0.01085|2431 |
|106   |2034.43258|2034-07-06|0.00215 |-0.01061|2345 |
|107   |2034.43532|2034-08-06|0.00262 |-0.01040|2244 |
|108   |2034.43806|2034-09-06|0.00308 |-0.01017|2170 |
|109   |2034.44079|2034-10-06|0.00355 |-0.00990|2036 |
|110   |2034.44627|2034-12-06|0.00446 |-0.00942|1826 |
|111   |2034.45175|2034-14-06|0.00538 |-0.00890|1617 |
|112   |2034.45722|2034-16-06|0.00625 |-0.00835|1409 |
|113   |2034.46270|2034-18-06|0.00711 |-0.00776|1191 |
|114   |2034.48186|2034-25-06|0.01003 |-0.00558|537  |
|115   |2034.50103|2034-02-07|0.01270 |-0.00325|-62  |
|116   |2034.58316|2034-01-08|0.02117 |0.00704 |-1351|
|117   |2034.66530|2034-31-08|0.02654 |0.01650 |-1710|
|118   |2034.74743|2034-30-09|0.03013 |0.02493 |-1831|
|119   |2034.82957|2034-30-10|0.03263 |0.03250 |-1846|
|120   |2034.91170|2034-29-11|0.03449 |0.03938 |-1802|
|121   |2034.99384|2034-29-12|0.03583 |0.04571 |-1788|
|122   |2035.07598|2035-28-01|0.03683 |0.05158 |-1732|
|123   |2035.15811|2035-27-02|0.03754 |0.05707 |-1675|
|124   |2035.24025|2035-29-03|0.03802 |0.06221 |-1616|
|125   |2035.32238|2035-28-04|0.03833 |0.06708 |-1595|
|126   |2035.40452|2035-28-05|0.03850 |0.07168 |-1551|
|127   |2035.89733|2035-24-11|0.03741 |0.09511 |-1311|
|128   |2036.39014|2036-22-05|0.03428 |0.11346 |-1148|
|129   |2036.88296|2036-18-11|0.03004 |0.12828 |-1032|
|130   |2037.37577|2037-18-05|0.02519 |0.14046 |-922 |
|131   |2037.86858|2037-14-11|0.01998 |0.15043 |-829 |
|132   |2038.36140|2038-12-05|0.01449 |0.15856 |-715 |
|133   |2038.85421|2038-08-11|0.00884 |0.16507 |-648 |
|134   |2039.34702|2039-07-05|0.00313 |0.17018 |-563 |
|135   |2039.83984|2039-03-11|-0.00261|0.17398 |-495 |
|136   |2040.33265|2040-01-05|-0.00833|0.17656 |-425 |
|137   |2040.82546|2040-28-10|-0.01398|0.17800 |-346 |
|138   |2041.31828|2041-27-04|-0.01956|0.17835 |-275 |
|139   |2041.81109|2041-24-10|-0.02503|0.17769 |-229 |
|140   |2042.30390|2042-21-04|-0.03035|0.17604 |-151 |
|141   |2042.79671|2042-18-10|-0.03549|0.17337 |-73  |
|142   |2043.28953|2043-16-04|-0.04046|0.16975 |2    |
|143   |2043.78234|2043-13-10|-0.04516|0.16516 |65   |
|144   |2044.27515|2044-10-04|-0.04963|0.15962 |142  |
|145   |2044.76797|2044-07-10|-0.05374|0.15309 |207  |
|146   |2045.26078|2045-06-04|-0.05756|0.14553 |308  |
|147   |2045.75359|2045-03-10|-0.06092|0.13694 |390  |
|148   |2046.24641|2046-31-03|-0.06381|0.12725 |493  |
|149   |2046.73922|2046-27-09|-0.06611|0.11638 |608  |
|150   |2047.23203|2047-26-03|-0.06766|0.10427 |722  |
|151   |2047.72485|2047-22-09|-0.06832|0.09077 |871  |
|152   |2048.21766|2048-20-03|-0.06779|0.07570 |1050 |
|153   |2048.71047|2048-16-09|-0.06564|0.05885 |1295 |
|154   |2049.20329|2049-16-03|-0.06097|0.03984 |1588 |
|155   |2049.28542|2049-15-04|-0.05988|0.03642 |1640 |
|156   |2049.36756|2049-15-05|-0.05861|0.03293 |1734 |
|157   |2049.44969|2049-14-06|-0.05723|0.02934 |1811 |
|158   |2049.53183|2049-14-07|-0.05566|0.02570 |1906 |
|159   |2049.61396|2049-13-08|-0.05391|0.02196 |2024 |
|160   |2049.69610|2049-12-09|-0.05195|0.01813 |2108 |
|161   |2049.77823|2049-12-10|-0.04973|0.01421 |2256 |
|162   |2049.86037|2049-11-11|-0.04719|0.01018 |2377 |
|163   |2049.94251|2049-11-12|-0.04425|0.00613 |2571 |
|164   |2050.02464|2050-09-01|-0.04084|0.00197 |2772 |
|165   |2050.10678|2050-08-02|-0.03680|-0.00220|3012 |
|166   |2050.18891|2050-10-03|-0.03184|-0.00632|3356 |
|167   |2050.27105|2050-09-04|-0.02556|-0.01014|3712 |
|168   |2050.35318|2050-09-05|-0.01722|-0.01305|4051 |
|169   |2050.37235|2050-16-05|-0.01487|-0.01343|4094 |
|170   |2050.39151|2050-23-05|-0.01231|-0.01366|4074 |
|171   |2050.41068|2050-30-05|-0.00953|-0.01365|3977 |
|172   |2050.41615|2050-01-06|-0.00869|-0.01358|3910 |
|173   |2050.42163|2050-03-06|-0.00783|-0.01349|3862 |
|174   |2050.42710|2050-05-06|-0.00696|-0.01339|3778 |
|175   |2050.43258|2050-07-06|-0.00610|-0.01326|3695 |
|176   |2050.43806|2050-09-06|-0.00520|-0.01310|3604 |
|177   |2050.44353|2050-11-06|-0.00430|-0.01291|3500 |
|178   |2050.44627|2050-12-06|-0.00386|-0.01278|3419 |
|179   |2050.44901|2050-13-06|-0.00339|-0.01265|3341 |
|180   |2050.45175|2050-14-06|-0.00293|-0.01255|3271 |
|181   |2050.45448|2050-15-06|-0.00247|-0.01241|3213 |
|182   |2050.45722|2050-16-06|-0.00200|-0.01227|3163 |
|183   |2050.45996|2050-17-06|-0.00154|-0.01212|3060 |
|184   |2050.46270|2050-18-06|-0.00105|-0.01195|2978 |
|185   |2050.46543|2050-19-06|-0.00060|-0.01178|2899 |
|186   |2050.46817|2050-20-06|-0.00011|-0.01162|2824 |
|187   |2050.47091|2050-21-06|0.00035 |-0.01144|2730 |
|188   |2050.47365|2050-22-06|0.00082 |-0.01120|2608 |
|189   |2050.47639|2050-23-06|0.00129 |-0.01101|2520 |
|190   |2050.47912|2050-24-06|0.00176 |-0.01081|2443 |
|191   |2050.48186|2050-25-06|0.00223 |-0.01058|2328 |
|192   |2050.48734|2050-27-06|0.00315 |-0.01015|2122 |
|193   |2050.49281|2050-29-06|0.00408 |-0.00964|1879 |
|194   |2050.49829|2050-01-07|0.00497 |-0.00913|1708 |
|195   |2050.50376|2050-03-07|0.00587 |-0.00856|1494 |
|196   |2050.52293|2050-10-07|0.00889 |-0.00649|774  |
|197   |2050.54209|2050-17-07|0.01164 |-0.00420|164  |
|198   |2050.62423|2050-16-08|0.02052 |0.00613 |-1308|
|199   |2050.70637|2050-15-09|0.02608 |0.01569 |-1705|
|200   |2050.78850|2050-15-10|0.02977 |0.02421 |-1815|
|201   |2050.87064|2050-14-11|0.03236 |0.03185 |-1835|
|202   |2050.95277|2050-14-12|0.03421 |0.03878 |-1811|
|203   |2051.03491|2051-13-01|0.03558 |0.04517 |-1781|
|204   |2051.11704|2051-12-02|0.03660 |0.05107 |-1723|
|205   |2051.19918|2051-14-03|0.03731 |0.05660 |-1681|
|206   |2051.28131|2051-13-04|0.03777 |0.06178 |-1656|
|207   |2051.36345|2051-13-05|0.03808 |0.06666 |-1587|
|208   |2051.44559|2051-12-06|0.03825 |0.07127 |-1571|
|209   |2051.93840|2051-09-12|0.03713 |0.09477 |-1332|
|210   |2052.43121|2052-06-06|0.03391 |0.11315 |-1169|
|211   |2052.92402|2052-03-12|0.02968 |0.12802 |-1041|
|212   |2053.41684|2053-02-06|0.02477 |0.14019 |-924 |
|213   |2053.90965|2053-29-11|0.01950 |0.15016 |-820 |
|214   |2054.40246|2054-27-05|0.01398 |0.15829 |-730 |
|215   |2054.89528|2054-23-11|0.00830 |0.16482 |-629 |
|216   |2055.38809|2055-22-05|0.00257 |0.16990 |-561 |
|217   |2055.88090|2055-18-11|-0.00320|0.17368 |-480 |
|218   |2056.37372|2056-16-05|-0.00894|0.17625 |-439 |
|219   |2056.86653|2056-12-11|-0.01460|0.17770 |-366 |
|220   |2057.35934|2057-12-05|-0.02021|0.17806 |-292 |
|221   |2057.85216|2057-08-11|-0.02566|0.17738 |-213 |
|222   |2058.34497|2058-06-05|-0.03098|0.17572 |-125 |
|223   |2058.83778|2058-02-11|-0.03614|0.17306 |-83  |
|224   |2059.33060|2059-01-05|-0.04107|0.16947 |4    |
|225   |2059.82341|2059-28-10|-0.04579|0.16487 |67   |
|226   |2060.31622|2060-25-04|-0.05023|0.15934 |149  |
|227   |2060.80903|2060-22-10|-0.05437|0.15281 |225  |
|228   |2061.30185|2061-21-04|-0.05814|0.14527 |309  |
|229   |2061.79466|2061-18-10|-0.06147|0.13668 |402  |
|230   |2062.28747|2062-15-04|-0.06435|0.12702 |492  |
|231   |2062.78029|2062-12-10|-0.06658|0.11619 |598  |
|232   |2063.27310|2063-10-04|-0.06812|0.10409 |733  |
|233   |2063.76591|2063-07-10|-0.06876|0.09063 |857  |
|234   |2064.25873|2064-04-04|-0.06820|0.07563 |1038 |
|235   |2064.75154|2064-01-10|-0.06598|0.05886 |1268 |
|236   |2065.24435|2065-31-03|-0.06132|0.03989 |1585 |
|237   |2065.32649|2065-30-04|-0.06020|0.03649 |1629 |
|238   |2065.40862|2065-30-05|-0.05895|0.03300 |1723 |
|239   |2065.49076|2065-29-06|-0.05757|0.02947 |1825 |
|240   |2065.57290|2065-29-07|-0.05601|0.02581 |1891 |
|241   |2065.65503|2065-28-08|-0.05424|0.02211 |1993 |
|242   |2065.73717|2065-27-09|-0.05231|0.01828 |2086 |
|243   |2065.81930|2065-27-10|-0.05009|0.01438 |2234 |
|244   |2065.90144|2065-26-11|-0.04754|0.01042 |2381 |
|245   |2065.98357|2065-26-12|-0.04466|0.00636 |2551 |
|246   |2066.06571|2066-24-01|-0.04128|0.00223 |2734 |
|247   |2066.14784|2066-23-02|-0.03727|-0.00192|2988 |
|248   |2066.22998|2066-25-03|-0.03240|-0.00601|3308 |
|249   |2066.31211|2066-24-04|-0.02625|-0.00986|3677 |
|250   |2066.39425|2066-24-05|-0.01815|-0.01288|4041 |
|251   |2066.41342|2066-31-05|-0.01586|-0.01333|4086 |
|252   |2066.43258|2066-07-06|-0.01337|-0.01363|4082 |
|253   |2066.45175|2066-14-06|-0.01069|-0.01372|4023 |
|254   |2066.47091|2066-21-06|-0.00779|-0.01352|3845 |
|255   |2066.47639|2066-23-06|-0.00690|-0.01341|3782 |
|256   |2066.48186|2066-25-06|-0.00602|-0.01327|3678 |
|257   |2066.48734|2066-27-06|-0.00514|-0.01311|3573 |
|258   |2066.49281|2066-29-06|-0.00425|-0.01289|3459 |
|259   |2066.49555|2066-30-06|-0.00377|-0.01277|3416 |
|260   |2066.49829|2066-01-07|-0.00333|-0.01266|3331 |
|261   |2066.50103|2066-02-07|-0.00286|-0.01253|3282 |
|262   |2066.50376|2066-03-07|-0.00240|-0.01241|3196 |
|263   |2066.50650|2066-04-07|-0.00194|-0.01228|3120 |
|264   |2066.50924|2066-05-07|-0.00145|-0.01209|3051 |
|265   |2066.51198|2066-06-07|-0.00099|-0.01194|2951 |
|266   |2066.51472|2066-07-07|-0.00054|-0.01175|2871 |
|267   |2066.51745|2066-08-07|-0.00006|-0.01159|2798 |
|268   |2066.52019|2066-09-07|0.00042 |-0.01140|2688 |
|269   |2066.52293|2066-10-07|0.00088 |-0.01121|2611 |
|270   |2066.52567|2066-11-07|0.00135 |-0.01099|2497 |
|271   |2066.52841|2066-12-07|0.00184 |-0.01077|2406 |
|272   |2066.53114|2066-13-07|0.00228 |-0.01056|2304 |
|273   |2066.53662|2066-15-07|0.00323 |-0.01009|2095 |
|274   |2066.54209|2066-17-07|0.00414 |-0.00961|1876 |
|275   |2066.54757|2066-19-07|0.00505 |-0.00908|1686 |
|276   |2066.55305|2066-21-07|0.00594 |-0.00853|1479 |
|277   |2066.57221|2066-28-07|0.00895 |-0.00643|754  |
|278   |2066.59138|2066-04-08|0.01170 |-0.00412|143  |
|279   |2066.67351|2066-03-09|0.02054 |0.00619 |-1291|
|280   |2066.75565|2066-03-10|0.02604 |0.01579 |-1720|
|281   |2066.83778|2066-02-11|0.02973 |0.02431 |-1846|
|282   |2066.91992|2066-02-12|0.03228 |0.03194 |-1832|
|283   |2067.00205|2067-01-01|0.03411 |0.03888 |-1840|
|284   |2067.08419|2067-31-01|0.03545 |0.04527 |-1788|
|285   |2067.16632|2067-02-03|0.03644 |0.05116 |-1742|
|286   |2067.24846|2067-01-04|0.03711 |0.05667 |-1692|
|287   |2067.33060|2067-01-05|0.03758 |0.06185 |-1633|
|288   |2067.41273|2067-31-05|0.03788 |0.06672 |-1576|
|289   |2067.49487|2067-30-06|0.03803 |0.07134 |-1552|
|290   |2067.98768|2067-27-12|0.03683 |0.09479 |-1351|
|291   |2068.48049|2068-24-06|0.03354 |0.11316 |-1187|
|292   |2068.97331|2068-21-12|0.02920 |0.12798 |-1032|
|293   |2069.46612|2069-20-06|0.02426 |0.14008 |-918 |
|294   |2069.95893|2069-17-12|0.01893 |0.15003 |-826 |
|295   |2070.45175|2070-14-06|0.01338 |0.15814 |-718 |
|296   |2070.94456|2070-11-12|0.00766 |0.16464 |-644 |
|297   |2071.43737|2071-09-06|0.00190 |0.16971 |-555 |
|298   |2071.93018|2071-06-12|-0.00388|0.17344 |-508 |
|299   |2072.42300|2072-03-06|-0.00962|0.17598 |-413 |
|300   |2072.91581|2072-30-11|-0.01532|0.17743 |-334 |
|301   |2073.40862|2073-30-05|-0.02091|0.17774 |-264 |
|302   |2073.90144|2073-26-11|-0.02639|0.17707 |-220 |
|303   |2074.39425|2074-24-05|-0.03171|0.17540 |-149 |




