## Lab Report 3
 > Find command 
 
 First, we use find -name in terminal. The input is as following:
   ```
    heejin@Annabelles-MBP skill-demo1 % find ./technical -name chapter-6.txt
   ```
 The output we saw is:
```
    ./technical/911report/chapter-6.txt
``` 
For the find -name command, the output is showing the path of the file that we are going to look for and return it. We can use it when we want to see the file that match the input name.

Second, I want to try find -ls in the terminal and see how it is different than simply printing the -ls.
Input:
```
    find ./technical -ls
```
Output:
```
9948378       24 -rwxr-xr-x    1 heejin           staff               10659 Oct 26 13:56 ./technical/plos/pmed.0020210.txt
9948387       16 -rwxr-xr-x    1 heejin           staff                4455 Oct 26 13:56 ./technical/plos/pmed.0020238.txt
9948238       24 -rwxr-xr-x    1 heejin           staff               10350 Oct 26 13:56 ./technical/plos/journal.pbio.0030051.txt
9948168       40 -rwxr-xr-x    1 heejin           staff               16825 Oct 26 13:56 ./technical/plos/journal.pbio.0020068.txt
9948164       40 -rwxr-xr-x    1 heejin           staff               20355 Oct 26 13:56 ./technical/plos/journal.pbio.0020054.txt
9948157       16 -rwxr-xr-x    1 heejin           staff                7538 Oct 26 13:56 ./technical/plos/journal.pbio.0020040.txt
9948283       48 -rwxr-xr-x    1 heejin           staff               24269 Oct 26 13:56 ./technical/plos/pmed.0010066.txt
9948249       24 -rwxr-xr-x    1 heejin           staff               10049 Oct 26 13:56 ./technical/plos/journal.pbio.0030131.txt
9948216       24 -rwxr-xr-x    1 heejin           staff               11804 Oct 26 13:56 ./technical/plos/journal.pbio.0020337.txt
9948371       16 -rwxr-xr-x    1 heejin           staff                4567 Oct 26 13:56 ./technical/plos/pmed.0020198.txt
9948284        8 -rwxr-xr-x    1 heejin           staff                2534 Oct 26 13:56 ./technical/plos/pmed.0010067.txt
9948177       40 -rwxr-xr-x    1 heejin           staff               17333 Oct 26 13:56 ./technical/plos/journal.pbio.0020121.txt
9948291       24 -rwxr-xr-x    1 heejin           staff               11122 Oct 26 13:56 ./technical/plos/pmed.0020007.txt
9948237       40 -rwxr-xr-x    1 heejin           staff               16704 Oct 26 13:56 ./technical/plos/journal.pbio.0030050.txt
9948388       16 -rwxr-xr-x    1 heejin           staff                4952 Oct 26 13:56 ./technical/plos/pmed.0020239.txt
9948204       32 -rwxr-xr-x    1 heejin           staff               15004 Oct 26 13:56 ./technical/plos/journal.pbio.0020241.txt
9948290       24 -rwxr-xr-x    1 heejin           staff                9559 Oct 26 13:56 ./technical/plos/pmed.0020005.txt
9948159       40 -rwxr-xr-x    1 heejin           staff               20221 Oct 26 13:56 ./technical/plos/journal.pbio.0020043.txt
9948309       32 -rwxr-xr-x    1 heejin           staff               13575 Oct 26 13:56 ./technical/plos/pmed.0020039.txt
9948288       16 -rwxr-xr-x    1 heejin           staff                5496 Oct 26 13:56 ./technical/plos/pmed.0010071.txt
9948247       40 -rwxr-xr-x    1 heejin           staff               17424 Oct 26 13:56 ./technical/plos/journal.pbio.0030127.txt
9948278       32 -rwxr-xr-x    1 heejin           staff               16284 Oct 26 13:56 ./technical/plos/pmed.0010058.txt
9948287        8 -rwxr-xr-x    1 heejin           staff                4041 Oct 26 13:56 ./technical/plos/pmed.0010070.txt
9948282       64 -rwxr-xr-x    1 heejin           staff               30314 Oct 26 13:56 ./technical/plos/pmed.0010064.txt
9948356       16 -rwxr-xr-x    1 heejin           staff                5757 Oct 26 13:56 ./technical/plos/pmed.0020158.txt
9948158       24 -rwxr-xr-x    1 heejin           staff               10153 Oct 26 13:56 ./technical/plos/journal.pbio.0020042.txt
9948210       24 -rwxr-xr-x    1 heejin           staff                9843 Oct 26 13:56 ./technical/plos/journal.pbio.0020297.txt
9948375       32 -rwxr-xr-x    1 heejin           staff               15713 Oct 26 13:56 ./technical/plos/pmed.0020206.txt
9948379       32 -rwxr-xr-x    1 heejin           staff               14906 Oct 26 13:56 ./technical/plos/pmed.0020212.txt
9948380       40 -rwxr-xr-x    1 heejin           staff               20019 Oct 26 13:56 ./technical/plos/pmed.0020216.txt
9948243       32 -rwxr-xr-x    1 heejin           staff               13564 Oct 26 13:56 ./technical/plos/journal.pbio.0030094.txt
9948160       40 -rwxr-xr-x    1 heejin           staff               19069 Oct 26 13:56 ./technical/plos/journal.pbio.0020046.txt
9948304        8 -rwxr-xr-x    1 heejin           staff                2016 Oct 26 13:56 ./technical/plos/pmed.0020028.txt
9948162       32 -rwxr-xr-x    1 heejin           staff               15002 Oct 26 13:56 ./technical/plos/journal.pbio.0020052.txt
9948351        8 -rwxr-xr-x    1 heejin           staff                3731 Oct 26 13:56 ./technical/plos/pmed.0020148.txt
9948357       56 -rwxr-xr-x    1 heejin           staff               28305 Oct 26 13:56 ./technical/plos/pmed.0020160.txt
9948272       16 -rwxr-xr-x    1 heejin           staff                4529 Oct 26 13:56 ./technical/plos/pmed.0010048.txt
9948279       24 -rwxr-xr-x    1 heejin           staff               11952 Oct 26 13:56 ./technical/plos/pmed.0010060.txt
9948251       40 -rwxr-xr-x    1 heejin           staff               20378 Oct 26 13:56 ./technical/plos/journal.pbio.0030137.txt
9948250       24 -rwxr-xr-x    1 heejin           staff               10649 Oct 26 13:56 ./technical/plos/journal.pbio.0030136.txt
9948280       16 -rwxr-xr-x    1 heejin           staff                7706 Oct 26 13:56 ./technical/plos/pmed.0010061.txt
9948273        8 -rwxr-xr-x    1 heejin           staff                4082 Oct 26 13:56 ./technical/plos/pmed.0010049.txt
9948358       40 -rwxr-xr-x    1 heejin           staff               20118 Oct 26 13:56 ./technical/plos/pmed.0020161.txt
9948179       32 -rwxr-xr-x    1 heejin           staff               13106 Oct 26 13:56 ./technical/plos/journal.pbio.0020127.txt
9948352        8 -rwxr-xr-x    1 heejin           staff                3794 Oct 26 13:56 ./technical/plos/pmed.0020149.txt
9948180       32 -rwxr-xr-x    1 heejin           staff               14772 Oct 26 13:56 ./technical/plos/journal.pbio.0020133.txt
9948293       48 -rwxr-xr-x    1 heejin           staff               24126 Oct 26 13:56 ./technical/plos/pmed.0020015.txt
9948163       48 -rwxr-xr-x    1 heejin           staff               21038 Oct 26 13:56 ./technical/plos/journal.pbio.0020053.txt
9948161       16 -rwxr-xr-x    1 heejin           staff                5847 Oct 26 13:56 ./technical/plos/journal.pbio.0020047.txt
9948374       16 -rwxr-xr-x    1 heejin           staff                5378 Oct 26 13:56 ./technical/plos/pmed.0020203.txt
9948239       32 -rwxr-xr-x    1 heejin           staff               15033 Oct 26 13:56 ./technical/plos/journal.pbio.0030056.txt
9948373        8 -rwxr-xr-x    1 heejin           staff                4092 Oct 26 13:56 ./technical/plos/pmed.0020201.txt
9948244       24 -rwxr-xr-x    1 heejin           staff               12085 Oct 26 13:56 ./technical/plos/journal.pbio.0030097.txt
9948295       24 -rwxr-xr-x    1 heejin           staff               12116 Oct 26 13:56 ./technical/plos/pmed.0020017.txt
9948178       32 -rwxr-xr-x    1 heejin           staff               15094 Oct 26 13:56 ./technical/plos/journal.pbio.0020125.txt
9948233       40 -rwxr-xr-x    1 heejin           staff               20030 Oct 26 13:56 ./technical/plos/journal.pbio.0020440.txt
9948281       56 -rwxr-xr-x    1 heejin           staff               28156 Oct 26 13:56 ./technical/plos/pmed.0010062.txt
9948364        8 -rwxr-xr-x    1 heejin           staff                3455 Oct 26 13:56 ./technical/plos/pmed.0020189.txt
9948359       56 -rwxr-xr-x    1 heejin           staff               26844 Oct 26 13:56 ./technical/plos/pmed.0020162.txt
9948294       56 -rwxr-xr-x    1 heejin           staff               27076 Oct 26 13:56 ./technical/plos/pmed.0020016.txt
9948289       24 -rwxr-xr-x    1 heejin           staff               10869 Oct 26 13:56 ./technical/plos/pmed.0020002.txt
9948372        8 -rwxr-xr-x    1 heejin           staff                3880 Oct 26 13:56 ./technical/plos/pmed.0020200.txt
9948382       24 -rwxr-xr-x    1 heejin           staff                8322 Oct 26 13:56 ./technical/plos/pmed.0020231.txt
9948206       16 -rwxr-xr-x    1 heejin           staff                8027 Oct 26 13:56 ./technical/plos/journal.pbio.0020263.txt
9948303        8 -rwxr-xr-x    1 heejin           staff                2356 Oct 26 13:56 ./technical/plos/pmed.0020027.txt
9948305       24 -rwxr-xr-x    1 heejin           staff                8919 Oct 26 13:56 ./technical/plos/pmed.0020033.txt
9948172       32 -rwxr-xr-x    1 heejin           staff               12821 Oct 26 13:56 ./technical/plos/journal.pbio.0020101.txt
9948271        8 -rwxr-xr-x    1 heejin           staff                4056 Oct 26 13:56 ./technical/plos/pmed.0010047.txt
9948246       16 -rwxr-xr-x    1 heejin           staff                6794 Oct 26 13:56 ./technical/plos/journal.pbio.0030105.txt
9948211       32 -rwxr-xr-x    1 heejin           staff               15486 Oct 26 13:56 ./technical/plos/journal.pbio.0020302.txt
9948270       16 -rwxr-xr-x    1 heejin           staff                6385 Oct 26 13:56 ./technical/plos/pmed.0010046.txt
9948276       32 -rwxr-xr-x    1 heejin           staff               15953 Oct 26 13:56 ./technical/plos/pmed.0010052.txt
9948365        8 -rwxr-xr-x    1 heejin           staff                 876 Oct 26 13:56 ./technical/plos/pmed.0020191.txt
9948171       16 -rwxr-xr-x    1 heejin           staff                8016 Oct 26 13:56 ./technical/plos/journal.pbio.0020100.txt
9948350        8 -rwxr-xr-x    1 heejin           staff                3817 Oct 26 13:56 ./technical/plos/pmed.0020146.txt
9948205       16 -rwxr-xr-x    1 heejin           staff                7642 Oct 26 13:56 ./technical/plos/journal.pbio.0020262.txt
9948241       32 -rwxr-xr-x    1 heejin           staff               14373 Oct 26 13:56 ./technical/plos/journal.pbio.0030065.txt
9948209       32 -rwxr-xr-x    1 heejin           staff               12539 Oct 26 13:56 ./technical/plos/journal.pbio.0020276.txt
9948383       32 -rwxr-xr-x    1 heejin           staff               16033 Oct 26 13:56 ./technical/plos/pmed.0020232.txt
9948381        8 -rwxr-xr-x    1 heejin           staff                 920 Oct 26 13:56 ./technical/plos/pmed.0020226.txt
9948302        8 -rwxr-xr-x    1 heejin           staff                2848 Oct 26 13:56 ./technical/plos/pmed.0020024.txt
9948296       80 -rwxr-xr-x    1 heejin           staff               37686 Oct 26 13:56 ./technical/plos/pmed.0020018.txt
9948348       16 -rwxr-xr-x    1 heejin           staff                5668 Oct 26 13:56 ./technical/plos/pmed.0020144.txt
9948353        8 -rwxr-xr-x    1 heejin           staff                3741 Oct 26 13:56 ./technical/plos/pmed.0020150.txt
9948176       32 -rwxr-xr-x    1 heejin           staff               13142 Oct 26 13:56 ./technical/plos/journal.pbio.0020116.txt
9948363       16 -rwxr-xr-x    1 heejin           staff                4837 Oct 26 13:56 ./technical/plos/pmed.0020187.txt
9948274        8 -rwxr-xr-x    1 heejin           staff                3467 Oct 26 13:56 ./technical/plos/pmed.0010050.txt
9948275       24 -rwxr-xr-x    1 heejin           staff                8321 Oct 26 13:56 ./technical/plos/pmed.0010051.txt
9948366        8 -rwxr-xr-x    1 heejin           staff                1042 Oct 26 13:56 ./technical/plos/pmed.0020192.txt
9948269       56 -rwxr-xr-x    1 heejin           staff               24586 Oct 26 13:56 ./technical/plos/pmed.0010045.txt
9948349        8 -rwxr-xr-x    1 heejin           staff                2891 Oct 26 13:56 ./technical/plos/pmed.0020145.txt
9948297        8 -rwxr-xr-x    1 heejin           staff                3270 Oct 26 13:56 ./technical/plos/pmed.0020019.txt
9948165       16 -rwxr-xr-x    1 heejin           staff                6873 Oct 26 13:56 ./technical/plos/journal.pbio.0020063.txt
9948242       24 -rwxr-xr-x    1 heejin           staff               12215 Oct 26 13:56 ./technical/plos/journal.pbio.0030076.txt
9948240       40 -rwxr-xr-x    1 heejin           staff               17821 Oct 26 13:56 ./technical/plos/journal.pbio.0030062.txt
9948386        8 -rwxr-xr-x    1 heejin           staff                4013 Oct 26 13:56 ./technical/plos/pmed.0020237.txt
9948167       24 -rwxr-xr-x    1 heejin           staff               10929 Oct 26 13:56 ./technical/plos/journal.pbio.0020067.txt
9948292       40 -rwxr-xr-x    1 heejin           staff               17310 Oct 26 13:56 ./technical/plos/pmed.0020009.txt
9948170       24 -rwxr-xr-x    1 heejin           staff                9467 Oct 26 13:56 ./technical/plos/journal.pbio.0020073.txt
9948307       16 -rwxr-xr-x    1 heejin           staff                6027 Oct 26 13:56 ./technical/plos/pmed.0020035.txt
9948299        8 -rwxr-xr-x    1 heejin           staff                2765 Oct 26 13:56 ./technical/plos/pmed.0020021.txt
9948175       48 -rwxr-xr-x    1 heejin           staff               21467 Oct 26 13:56 ./technical/plos/journal.pbio.0020113.txt
9948354       16 -rwxr-xr-x    1 heejin           staff                6985 Oct 26 13:56 ./technical/plos/pmed.0020155.txt
9948286        8 -rwxr-xr-x    1 heejin           staff                3963 Oct 26 13:56 ./technical/plos/pmed.0010069.txt
9948267       16 -rwxr-xr-x    1 heejin           staff                7641 Oct 26 13:56 ./technical/plos/pmed.0010041.txt
9948362       72 -rwxr-xr-x    1 heejin           staff               35433 Oct 26 13:56 ./technical/plos/pmed.0020182.txt
9948369        8 -rwxr-xr-x    1 heejin           staff                3811 Oct 26 13:56 ./technical/plos/pmed.0020196.txt
9948215       32 -rwxr-xr-x    1 heejin           staff               13391 Oct 26 13:56 ./technical/plos/journal.pbio.0020311.txt
9948245       32 -rwxr-xr-x    1 heejin           staff               14381 Oct 26 13:56 ./technical/plos/journal.pbio.0030102.txt
9948214       32 -rwxr-xr-x    1 heejin           staff               14197 Oct 26 13:56 ./technical/plos/journal.pbio.0020310.txt
9948370       16 -rwxr-xr-x    1 heejin           staff                5701 Oct 26 13:56 ./technical/plos/pmed.0020197.txt
9948285        8 -rwxr-xr-x    1 heejin           staff                2754 Oct 26 13:56 ./technical/plos/pmed.0010068.txt
9948347       48 -rwxr-xr-x    1 heejin           staff               20867 Oct 26 13:56 ./technical/plos/pmed.0020140.txt
9948174       16 -rwxr-xr-x    1 heejin           staff                7411 Oct 26 13:56 ./technical/plos/journal.pbio.0020112.txt
9948298        8 -rwxr-xr-x    1 heejin           staff                3761 Oct 26 13:56 ./technical/plos/pmed.0020020.txt
9948306       40 -rwxr-xr-x    1 heejin           staff               20118 Oct 26 13:56 ./technical/plos/pmed.0020034.txt
9948385       16 -rwxr-xr-x    1 heejin           staff                4766 Oct 26 13:56 ./technical/plos/pmed.0020236.txt
9948208       24 -rwxr-xr-x    1 heejin           staff                8485 Oct 26 13:56 ./technical/plos/journal.pbio.0020272.txt
9948376       16 -rwxr-xr-x    1 heejin           staff                6589 Oct 26 13:56 ./technical/plos/pmed.0020208.txt
9948166       40 -rwxr-xr-x    1 heejin           staff               16977 Oct 26 13:56 ./technical/plos/journal.pbio.0020064.txt
9948300        8 -rwxr-xr-x    1 heejin           staff                2965 Oct 26 13:56 ./technical/plos/pmed.0020022.txt
9948308       16 -rwxr-xr-x    1 heejin           staff                6396 Oct 26 13:56 ./technical/plos/pmed.0020036.txt
9948277       32 -rwxr-xr-x    1 heejin           staff               15680 Oct 26 13:56 ./technical/plos/pmed.0010056.txt
9948368        8 -rwxr-xr-x    1 heejin           staff                3163 Oct 26 13:56 ./technical/plos/pmed.0020195.txt
9948268       24 -rwxr-xr-x    1 heejin           staff               10380 Oct 26 13:56 ./technical/plos/pmed.0010042.txt
9948361       16 -rwxr-xr-x    1 heejin           staff                6993 Oct 26 13:56 ./technical/plos/pmed.0020181.txt
9948212       32 -rwxr-xr-x    1 heejin           staff               15057 Oct 26 13:56 ./technical/plos/journal.pbio.0020306.txt
9948248       16 -rwxr-xr-x    1 heejin           staff                6224 Oct 26 13:56 ./technical/plos/journal.pbio.0030129.txt
9948213       24 -rwxr-xr-x    1 heejin           staff               11321 Oct 26 13:56 ./technical/plos/journal.pbio.0020307.txt
9948360       16 -rwxr-xr-x    1 heejin           staff                7775 Oct 26 13:56 ./technical/plos/pmed.0020180.txt
9948367       16 -rwxr-xr-x    1 heejin           staff                5238 Oct 26 13:56 ./technical/plos/pmed.0020194.txt
9948355        8 -rwxr-xr-x    1 heejin           staff                1408 Oct 26 13:56 ./technical/plos/pmed.0020157.txt
9948173       16 -rwxr-xr-x    1 heejin           staff                7623 Oct 26 13:56 ./technical/plos/journal.pbio.0020105.txt
9948301        8 -rwxr-xr-x    1 heejin           staff                3554 Oct 26 13:56 ./technical/plos/pmed.0020023.txt
9948169       16 -rwxr-xr-x    1 heejin           staff                6924 Oct 26 13:56 ./technical/plos/journal.pbio.0020071.txt
9948384       16 -rwxr-xr-x    1 heejin           staff                4749 Oct 26 13:56 ./technical/plos/pmed.0020235.txt
9948207       40 -rwxr-xr-x    1 heejin           staff               20392 Oct 26 13:56 ./technical/plos/journal.pbio.0020267.txt
9948377       40 -rwxr-xr-x    1 heejin           staff               20056 Oct 26 13:56 ./technical/plos/pmed.0020209.txt
9948390       80 -rwxr-xr-x    1 heejin           staff               38881 Oct 26 13:56 ./technical/plos/pmed.0020246.txt
9948202       32 -rwxr-xr-x    1 heejin           staff               12946 Oct 26 13:56 ./technical/plos/journal.pbio.0020228.txt
9948197       40 -rwxr-xr-x    1 heejin           staff               17069 Oct 26 13:56 ./technical/plos/journal.pbio.0020214.txt
9948314       56 -rwxr-xr-x    1 heejin           staff               28669 Oct 26 13:56 ./technical/plos/pmed.0020050.txt
9948344       16 -rwxr-xr-x    1 heejin           staff                5747 Oct 26 13:56 ./technical/plos/pmed.0020118.txt
9948263        8 -rwxr-xr-x    1 heejin           staff                3234 Oct 26 13:56 ./technical/plos/pmed.0010030.txt
9948258        8 -rwxr-xr-x    1 heejin           staff                3597 Oct 26 13:56 ./technical/plos/pmed.0010024.txt
9948219       32 -rwxr-xr-x    1 heejin           staff               15412 Oct 26 13:56 ./technical/plos/journal.pbio.0020348.txt
9948227       48 -rwxr-xr-x    1 heejin           staff               23165 Oct 26 13:56 ./technical/plos/journal.pbio.0020406.txt
9948259        8 -rwxr-xr-x    1 heejin           staff                2843 Oct 26 13:56 ./technical/plos/pmed.0010025.txt
9948329        8 -rwxr-xr-x    1 heejin           staff                2115 Oct 26 13:56 ./technical/plos/pmed.0020086.txt
9948311       72 -rwxr-xr-x    1 heejin           staff               35111 Oct 26 13:56 ./technical/plos/pmed.0020045.txt
9948198       24 -rwxr-xr-x    1 heejin           staff               10017 Oct 26 13:56 ./technical/plos/journal.pbio.0020215.txt
9948391       24 -rwxr-xr-x    1 heejin           staff               12133 Oct 26 13:56 ./technical/plos/pmed.0020247.txt
9948312        8 -rwxr-xr-x    1 heejin           staff                3981 Oct 26 13:56 ./technical/plos/pmed.0020047.txt
9948150       40 -rwxr-xr-x    1 heejin           staff               18130 Oct 26 13:56 ./technical/plos/journal.pbio.0020001.txt
9948331        8 -rwxr-xr-x    1 heejin           staff                3431 Oct 26 13:56 ./technical/plos/pmed.0020090.txt
9948188       48 -rwxr-xr-x    1 heejin           staff               20933 Oct 26 13:56 ./technical/plos/journal.pbio.0020161.txt
9948232       56 -rwxr-xr-x    1 heejin           staff               26338 Oct 26 13:56 ./technical/plos/journal.pbio.0020439.txt
9948226       40 -rwxr-xr-x    1 heejin           staff               16508 Oct 26 13:56 ./technical/plos/journal.pbio.0020404.txt
9948260       16 -rwxr-xr-x    1 heejin           staff                6414 Oct 26 13:56 ./technical/plos/pmed.0010026.txt
9948185       40 -rwxr-xr-x    1 heejin           staff               18804 Oct 26 13:56 ./technical/plos/journal.pbio.0020148.txt
9948328        8 -rwxr-xr-x    1 heejin           staff                2473 Oct 26 13:56 ./technical/plos/pmed.0020085.txt
9948332        8 -rwxr-xr-x    1 heejin           staff                3561 Oct 26 13:56 ./technical/plos/pmed.0020091.txt
9948155       32 -rwxr-xr-x    1 heejin           staff               16239 Oct 26 13:56 ./technical/plos/journal.pbio.0020028.txt
9948199       24 -rwxr-xr-x    1 heejin           staff               11519 Oct 26 13:56 ./technical/plos/journal.pbio.0020216.txt
9948400        8 -rwxr-xr-x    1 heejin           staff                2738 Oct 26 13:56 ./technical/plos/pmed.0020278.txt
9948395       16 -rwxr-xr-x    1 heejin           staff                4198 Oct 26 13:56 ./technical/plos/pmed.0020268.txt
9948195       40 -rwxr-xr-x    1 heejin           staff               19384 Oct 26 13:56 ./technical/plos/journal.pbio.0020206.txt
9948151       16 -rwxr-xr-x    1 heejin           staff                6894 Oct 26 13:56 ./technical/plos/journal.pbio.0020010.txt
9948189       40 -rwxr-xr-x    1 heejin           staff               17708 Oct 26 13:56 ./technical/plos/journal.pbio.0020164.txt
9948256       16 -rwxr-xr-x    1 heejin           staff                6073 Oct 26 13:56 ./technical/plos/pmed.0010022.txt
9948265       72 -rwxr-xr-x    1 heejin           staff               35535 Oct 26 13:56 ./technical/plos/pmed.0010036.txt
9948224       32 -rwxr-xr-x    1 heejin           staff               16211 Oct 26 13:56 ./technical/plos/journal.pbio.0020400.txt
9948225       32 -rwxr-xr-x    1 heejin           staff               13918 Oct 26 13:56 ./technical/plos/journal.pbio.0020401.txt
9948257        8 -rwxr-xr-x    1 heejin           staff                3619 Oct 26 13:56 ./technical/plos/pmed.0010023.txt
9948346       56 -rwxr-xr-x    1 heejin           staff               25177 Oct 26 13:56 ./technical/plos/pmed.0020123.txt
9948333        8 -rwxr-xr-x    1 heejin           staff                3163 Oct 26 13:56 ./technical/plos/pmed.0020094.txt
9948196       40 -rwxr-xr-x    1 heejin           staff               19111 Oct 26 13:56 ./technical/plos/journal.pbio.0020213.txt
9948393       16 -rwxr-xr-x    1 heejin           staff                4677 Oct 26 13:56 ./technical/plos/pmed.0020257.txt
9948153       24 -rwxr-xr-x    1 heejin           staff               12045 Oct 26 13:56 ./technical/plos/journal.pbio.0020013.txt
9948315       16 -rwxr-xr-x    1 heejin           staff                6282 Oct 26 13:56 ./technical/plos/pmed.0020055.txt
9948327        8 -rwxr-xr-x    1 heejin           staff                1538 Oct 26 13:56 ./technical/plos/pmed.0020082.txt
9948255       32 -rwxr-xr-x    1 heejin           staff               12576 Oct 26 13:56 ./technical/plos/pmed.0010021.txt
9948264       16 -rwxr-xr-x    1 heejin           staff                8190 Oct 26 13:56 ./technical/plos/pmed.0010034.txt
9948252       56 -rwxr-xr-x    1 heejin           staff               26050 Oct 26 13:56 ./technical/plos/pmed.0010008.txt
9948345        8 -rwxr-xr-x    1 heejin           staff                1444 Oct 26 13:56 ./technical/plos/pmed.0020120.txt
9948191       24 -rwxr-xr-x    1 heejin           staff               10733 Oct 26 13:56 ./technical/plos/journal.pbio.0020172.txt
9948310       40 -rwxr-xr-x    1 heejin           staff               17506 Oct 26 13:56 ./technical/plos/pmed.0020040.txt
9948322       32 -rwxr-xr-x    1 heejin           staff               16026 Oct 26 13:56 ./technical/plos/pmed.0020068.txt
9948152       40 -rwxr-xr-x    1 heejin           staff               17471 Oct 26 13:56 ./technical/plos/journal.pbio.0020012.txt
9948401        8 -rwxr-xr-x    1 heejin           staff                2811 Oct 26 13:56 ./technical/plos/pmed.0020281.txt
9948389       16 -rwxr-xr-x    1 heejin           staff                5076 Oct 26 13:56 ./technical/plos/pmed.0020242.txt
9947018        0 drwxr-xr-x  839 heejin           staff               26848 Oct 26 13:56 ./technical/biomed
9947511       40 -rwxr-xr-x    1 heejin           staff               18059 Oct 26 13:56 ./technical/biomed/1472-6807-2-2.txt
9947388       64 -rwxr-xr-x    1 heejin           staff               29678 Oct 26 13:56 ./technical/biomed/1471-2350-4-3.txt
9947148       40 -rwxr-xr-x    1 heejin           staff               19344 Oct 26 13:56 ./technical/biomed/1471-2156-2-3.txt
9947153       48 -rwxr-xr-x    1 heejin           staff               20685 Oct 26 13:56 ./technical/biomed/1471-2156-3-11.txt
9947086       80 -rwxr-xr-x    1 heejin           staff               39412 Oct 26 13:56 ./technical/biomed/1471-2121-3-10.txt
9947220       88 -rwxr-xr-x    1 heejin           staff               40982 Oct 26 13:56 ./technical/biomed/1471-2172-3-4.txt
9947820       96 -rwxr-xr-x    1 heejin           staff               48746 Oct 26 13:56 ./technical/biomed/gb-2002-4-1-r2.txt
9947839       48 -rwxr-xr-x    1 heejin           staff               22764 Oct 26 13:56 ./technical/biomed/gb-2003-4-6-r41.txt
9947453       48 -rwxr-xr-x    1 heejin           staff               23163 Oct 26 13:56 ./technical/biomed/1471-2466-1-1.txt
9947254       56 -rwxr-xr-x    1 heejin           staff               26466 Oct 26 13:56 ./technical/biomed/1471-2199-2-10.txt
9947286       80 -rwxr-xr-x    1 heejin           staff               40360 Oct 26 13:56 ./technical/biomed/1471-2202-2-9.txt
9947730       56 -rwxr-xr-x    1 heejin           staff               24929 Oct 26 13:56 ./technical/biomed/cc991.txt
9947394       48 -rwxr-xr-x    1 heejin           staff               22370 Oct 26 13:56 ./technical/biomed/1471-2369-3-9.txt
9947697       72 -rwxr-xr-x    1 heejin           staff               35035 Oct 26 13:56 ./technical/biomed/bcr620.txt
9947596      104 -rwxr-xr-x    1 heejin           staff               53109 Oct 26 13:56 ./technical/biomed/1476-069X-2-4.txt
9947478       32 -rwxr-xr-x    1 heejin           staff               15015 Oct 26 13:56 ./technical/biomed/1472-6750-3-11.txt
9947169       96 -rwxr-xr-x    1 heejin           staff               47898 Oct 26 13:56 ./technical/biomed/1471-2164-2-9.txt
9947024       48 -rwxr-xr-x    1 heejin           staff               24028 Oct 26 13:56 ./technical/biomed/1471-2091-2-10.txt
9947749       96 -rwxr-xr-x    1 heejin           staff               47665 Oct 26 13:56 ./technical/biomed/gb-2001-2-4-research0010.txt
9947831       80 -rwxr-xr-x    1 heejin           staff               38892 Oct 26 13:56 ./technical/biomed/gb-2003-4-4-r24.txt
9947119       88 -rwxr-xr-x    1 heejin           staff               41353 Oct 26 13:56 ./technical/biomed/1471-213X-2-1.txt
9947537       72 -rwxr-xr-x    1 heejin           staff               35409 Oct 26 13:56 ./technical/biomed/1472-6882-3-3.txt
9947414       56 -rwxr-xr-x    1 heejin           staff               27937 Oct 26 13:56 ./technical/biomed/1471-2407-2-3.txt
9947655       48 -rwxr-xr-x    1 heejin           staff               20970 Oct 26 13:56 ./technical/biomed/ar331.txt
9947652       64 -rwxr-xr-x    1 heejin           staff               29069 Oct 26 13:56 ./technical/biomed/ar319.txt
9947160       56 -rwxr-xr-x    1 heejin           staff               27525 Oct 26 13:56 ./technical/biomed/1471-2156-4-5.txt
9947430       64 -rwxr-xr-x    1 heejin           staff               30767 Oct 26 13:56 ./technical/biomed/1471-2431-2-1.txt
9947611       32 -rwxr-xr-x    1 heejin           staff               15699 Oct 26 13:56 ./technical/biomed/1476-4598-2-22.txt
9947239       56 -rwxr-xr-x    1 heejin           staff               26497 Oct 26 13:56 ./technical/biomed/1471-2180-2-22.txt
9947378       48 -rwxr-xr-x    1 heejin           staff               23741 Oct 26 13:56 ./technical/biomed/1471-2334-3-9.txt
9947025       72 -rwxr-xr-x    1 heejin           staff               35103 Oct 26 13:56 ./technical/biomed/1471-2091-2-11.txt
9947750       88 -rwxr-xr-x    1 heejin           staff               43999 Oct 26 13:56 ./technical/biomed/gb-2001-2-4-research0011.txt
9947302       48 -rwxr-xr-x    1 heejin           staff               21868 Oct 26 13:56 ./technical/biomed/1471-2202-4-12.txt
9947855       40 -rwxr-xr-x    1 heejin           staff               16843 Oct 26 13:56 ./technical/biomed/rr73.txt
9947168       56 -rwxr-xr-x    1 heejin           staff               26490 Oct 26 13:56 ./technical/biomed/1471-2164-2-8.txt
9947131       64 -rwxr-xr-x    1 heejin           staff               32108 Oct 26 13:56 ./technical/biomed/1471-2148-2-12.txt
9947699       32 -rwxr-xr-x    1 heejin           staff               13481 Oct 26 13:56 ./technical/biomed/bcr635.txt
9947020       64 -rwxr-xr-x    1 heejin           staff               29585 Oct 26 13:56 ./technical/biomed/1468-6708-3-10.txt
9947836      144 -rwxr-xr-x    1 heejin           staff               70729 Oct 26 13:56 ./technical/biomed/gb-2003-4-5-r34.txt
9947285       88 -rwxr-xr-x    1 heejin           staff               41564 Oct 26 13:56 ./technical/biomed/1471-2202-2-8.txt
9947087       64 -rwxr-xr-x    1 heejin           staff               28955 Oct 26 13:56 ./technical/biomed/1471-2121-3-11.txt
9947152       48 -rwxr-xr-x    1 heejin           staff               23096 Oct 26 13:56 ./technical/biomed/1471-2156-3-10.txt
9947450       48 -rwxr-xr-x    1 heejin           staff               22605 Oct 26 13:56 ./technical/biomed/1471-2458-3-20.txt
9947387       72 -rwxr-xr-x    1 heejin           staff               34416 Oct 26 13:56 ./technical/biomed/1471-2350-4-2.txt
9947512       96 -rwxr-xr-x    1 heejin           staff               48482 Oct 26 13:56 ./technical/biomed/1472-6807-2-3.txt
9947510       48 -rwxr-xr-x    1 heejin           staff               23376 Oct 26 13:56 ./technical/biomed/1472-6807-2-1.txt
9947607       56 -rwxr-xr-x    1 heejin           staff               28420 Oct 26 13:56 ./technical/biomed/1476-4598-1-8.txt
9947625       56 -rwxr-xr-x    1 heejin           staff               26223 Oct 26 13:56 ./technical/biomed/1477-7525-1-9.txt
9947674       72 -rwxr-xr-x    1 heejin           staff               35253 Oct 26 13:56 ./technical/biomed/ar79.txt
9947601       64 -rwxr-xr-x    1 heejin           staff               31054 Oct 26 13:56 ./technical/biomed/1476-0711-2-7.txt
9947555       72 -rwxr-xr-x    1 heejin           staff               34254 Oct 26 13:56 ./technical/biomed/1472-6947-3-8.txt
9947089       88 -rwxr-xr-x    1 heejin           staff               43442 Oct 26 13:56 ./technical/biomed/1471-2121-3-13.txt
9947819       64 -rwxr-xr-x    1 heejin           staff               30292 Oct 26 13:56 ./technical/biomed/gb-2002-4-1-r1.txt
9947422       80 -rwxr-xr-x    1 heejin           staff               37922 Oct 26 13:56 ./technical/biomed/1471-2407-3-18.txt
9947326       96 -rwxr-xr-x    1 heejin           staff               46406 Oct 26 13:56 ./technical/biomed/1471-2229-2-3.txt
9947364       40 -rwxr-xr-x    1 heejin           staff               19590 Oct 26 13:56 ./technical/biomed/1471-2334-1-9.txt
9947812      112 -rwxr-xr-x    1 heejin           staff               57158 Oct 26 13:56 ./technical/biomed/gb-2002-3-9-research0043.txt
9947429       88 -rwxr-xr-x    1 heejin           staff               44803 Oct 26 13:56 ./technical/biomed/1471-2415-3-5.txt
9947362       40 -rwxr-xr-x    1 heejin           staff               16640 Oct 26 13:56 ./technical/biomed/1471-2334-1-21.txt
9947757      136 -rwxr-xr-x    1 heejin           staff               69168 Oct 26 13:56 ./technical/biomed/gb-2001-2-7-research0025.txt
9947647       96 -rwxr-xr-x    1 heejin           staff               46550 Oct 26 13:56 ./technical/biomed/ar130.txt
9947598       56 -rwxr-xr-x    1 heejin           staff               28318 Oct 26 13:56 ./technical/biomed/1476-069X-2-7.txt
9947539       40 -rwxr-xr-x    1 heejin           staff               19200 Oct 26 13:56 ./technical/biomed/1472-6890-2-5.txt
9947645       72 -rwxr-xr-x    1 heejin           staff               36324 Oct 26 13:56 ./technical/biomed/ar118.txt
9947805       64 -rwxr-xr-x    1 heejin           staff               30444 Oct 26 13:56 ./technical/biomed/gb-2002-3-7-research0032.txt
9947333      112 -rwxr-xr-x    1 heejin           staff               53437 Oct 26 13:56 ./technical/biomed/1471-2253-2-5.txt
9947309       64 -rwxr-xr-x    1 heejin           staff               29200 Oct 26 13:56 ./technical/biomed/1471-2210-1-10.txt
9947027       56 -rwxr-xr-x    1 heejin           staff               27970 Oct 26 13:56 ./technical/biomed/1471-2091-2-13.txt
9947238       80 -rwxr-xr-x    1 heejin           staff               38478 Oct 26 13:56 ./technical/biomed/1471-2180-2-20.txt
9947293       64 -rwxr-xr-x    1 heejin           staff               30039 Oct 26 13:56 ./technical/biomed/1471-2202-3-19.txt
9947300       64 -rwxr-xr-x    1 heejin           staff               29083 Oct 26 13:56 ./technical/biomed/1471-2202-4-10.txt
9947559       64 -rwxr-xr-x    1 heejin           staff               29285 Oct 26 13:56 ./technical/biomed/1472-6963-2-10.txt
9947610       56 -rwxr-xr-x    1 heejin           staff               26696 Oct 26 13:56 ./technical/biomed/1476-4598-2-20.txt
9947161       72 -rwxr-xr-x    1 heejin           staff               35378 Oct 26 13:56 ./technical/biomed/1471-2156-4-6.txt
9947451       56 -rwxr-xr-x    1 heejin           staff               25679 Oct 26 13:56 ./technical/biomed/1471-2458-3-5.txt
9947484       24 -rwxr-xr-x    1 heejin           staff                9952 Oct 26 13:56 ./technical/biomed/1472-6769-1-4.txt
9947832      128 -rwxr-xr-x    1 heejin           staff               62553 Oct 26 13:56 ./technical/biomed/gb-2003-4-4-r26.txt
9947536       96 -rwxr-xr-x    1 heejin           staff               48170 Oct 26 13:56 ./technical/biomed/1472-6882-3-1.txt
9947727       88 -rwxr-xr-x    1 heejin           staff               43694 Oct 26 13:56 ./technical/biomed/cc4.txt
9947243       96 -rwxr-xr-x    1 heejin           staff               47423 Oct 26 13:56 ./technical/biomed/1471-2180-2-35.txt
9947301       88 -rwxr-xr-x    1 heejin           staff               42348 Oct 26 13:56 ./technical/biomed/1471-2202-4-11.txt
9947751       72 -rwxr-xr-x    1 heejin           staff               35659 Oct 26 13:56 ./technical/biomed/gb-2001-2-4-research0012.txt
9947026       56 -rwxr-xr-x    1 heejin           staff               24851 Oct 26 13:56 ./technical/biomed/1471-2091-2-12.txt
9947332       40 -rwxr-xr-x    1 heejin           staff               17387 Oct 26 13:56 ./technical/biomed/1471-2253-2-4.txt
9947756       88 -rwxr-xr-x    1 heejin           staff               44121 Oct 26 13:56 ./technical/biomed/gb-2001-2-7-research0024.txt
9947428       48 -rwxr-xr-x    1 heejin           staff               22465 Oct 26 13:56 ./technical/biomed/1471-2415-3-4.txt
9947255       48 -rwxr-xr-x    1 heejin           staff               24301 Oct 26 13:56 ./technical/biomed/1471-2199-2-12.txt
9947088       88 -rwxr-xr-x    1 heejin           staff               44218 Oct 26 13:56 ./technical/biomed/1471-2121-3-12.txt
9947130       96 -rwxr-xr-x    1 heejin           staff               48738 Oct 26 13:56 ./technical/biomed/1471-2148-1-8.txt
9947748       72 -rwxr-xr-x    1 heejin           staff               33499 Oct 26 13:56 ./technical/biomed/gb-2001-2-3-research0008.txt
9947144       80 -rwxr-xr-x    1 heejin           staff               38628 Oct 26 13:56 ./technical/biomed/1471-2156-2-1.txt
9947456       32 -rwxr-xr-x    1 heejin           staff               15457 Oct 26 13:56 ./technical/biomed/1471-2466-3-1.txt
9947688       40 -rwxr-xr-x    1 heejin           staff               19743 Oct 26 13:56 ./technical/biomed/bcr568.txt
9947842       80 -rwxr-xr-x    1 heejin           staff               37359 Oct 26 13:56 ./technical/biomed/gb-2003-4-7-r46.txt
9947578       80 -rwxr-xr-x    1 heejin           staff               39946 Oct 26 13:56 ./technical/biomed/1475-2875-2-14.txt
9947341       64 -rwxr-xr-x    1 heejin           staff               30077 Oct 26 13:56 ./technical/biomed/1471-2288-2-4.txt
9947485       48 -rwxr-xr-x    1 heejin           staff               24168 Oct 26 13:56 ./technical/biomed/1472-6785-1-3.txt
9947678       72 -rwxr-xr-x    1 heejin           staff               32793 Oct 26 13:56 ./technical/biomed/ar93.txt
9947521       64 -rwxr-xr-x    1 heejin           staff               29057 Oct 26 13:56 ./technical/biomed/1472-6831-2-2.txt
9947691       40 -rwxr-xr-x    1 heejin           staff               19181 Oct 26 13:56 ./technical/biomed/bcr583.txt
9947726       40 -rwxr-xr-x    1 heejin           staff               20130 Oct 26 13:56 ./technical/biomed/cc367.txt
9947628       64 -rwxr-xr-x    1 heejin           staff               30587 Oct 26 13:56 ./technical/biomed/1477-7827-1-17.txt
9947627      112 -rwxr-xr-x    1 heejin           staff               55102 Oct 26 13:56 ./technical/biomed/1477-7827-1-13.txt
9947513       80 -rwxr-xr-x    1 heejin           staff               39829 Oct 26 13:56 ./technical/biomed/1472-6807-2-4.txt
9947155      104 -rwxr-xr-x    1 heejin           staff               49960 Oct 26 13:56 ./technical/biomed/1471-2156-3-17.txt
9947577       72 -rwxr-xr-x    1 heejin           staff               35430 Oct 26 13:56 ./technical/biomed/1475-2875-2-10.txt
9947840      128 -rwxr-xr-x    1 heejin           staff               64870 Oct 26 13:56 ./technical/biomed/gb-2003-4-7-r42.txt
9947149       48 -rwxr-xr-x    1 heejin           staff               22998 Oct 26 13:56 ./technical/biomed/1471-2156-2-5.txt
9947669       56 -rwxr-xr-x    1 heejin           staff               27018 Oct 26 13:56 ./technical/biomed/ar68.txt
9947219       80 -rwxr-xr-x    1 heejin           staff               38202 Oct 26 13:56 ./technical/biomed/1471-2172-3-2.txt
9947091      104 -rwxr-xr-x    1 heejin           staff               52637 Oct 26 13:56 ./technical/biomed/1471-2121-3-16.txt
9947469       56 -rwxr-xr-x    1 heejin           staff               25046 Oct 26 13:56 ./technical/biomed/1472-6750-1-12.txt
9947544       88 -rwxr-xr-x    1 heejin           staff               44524 Oct 26 13:56 ./technical/biomed/1472-6904-2-7.txt
9947533       56 -rwxr-xr-x    1 heejin           staff               25465 Oct 26 13:56 ./technical/biomed/1472-6882-1-7.txt
9947363       48 -rwxr-xr-x    1 heejin           staff               22860 Oct 26 13:56 ./technical/biomed/1471-2334-1-24.txt
9947398       56 -rwxr-xr-x    1 heejin           staff               24779 Oct 26 13:56 ./technical/biomed/1471-2377-2-4.txt
9947815       72 -rwxr-xr-x    1 heejin           staff               33810 Oct 26 13:56 ./technical/biomed/gb-2002-3-9-research0046.txt
9947856       48 -rwxr-xr-x    1 heejin           staff               22290 Oct 26 13:56 ./technical/biomed/rr74.txt
9947808       72 -rwxr-xr-x    1 heejin           staff               36803 Oct 26 13:56 ./technical/biomed/gb-2002-3-7-research0037.txt
9947758       64 -rwxr-xr-x    1 heejin           staff               32241 Oct 26 13:56 ./technical/biomed/gb-2001-2-8-research0027.txt
9947595       72 -rwxr-xr-x    1 heejin           staff               34475 Oct 26 13:56 ./technical/biomed/1476-069X-2-2.txt
9947133       56 -rwxr-xr-x    1 heejin           staff               28216 Oct 26 13:56 ./technical/biomed/1471-2148-2-15.txt
9947526       40 -rwxr-xr-x    1 heejin           staff               17569 Oct 26 13:56 ./technical/biomed/1472-6874-2-1.txt
9947314       40 -rwxr-xr-x    1 heejin           staff               20085 Oct 26 13:56 ./technical/biomed/1471-2210-1-8.txt
9947043       48 -rwxr-xr-x    1 heejin           staff               23491 Oct 26 13:56 ./technical/biomed/1471-2091-3-8.txt
9947504       80 -rwxr-xr-x    1 heejin           staff               38847 Oct 26 13:56 ./technical/biomed/1472-6793-2-8.txt
9947120       80 -rwxr-xr-x    1 heejin           staff               37751 Oct 26 13:56 ./technical/biomed/1471-213X-2-7.txt
9947294       72 -rwxr-xr-x    1 heejin           staff               36617 Oct 26 13:56 ./technical/biomed/1471-2202-3-20.txt
9947028       40 -rwxr-xr-x    1 heejin           staff               18716 Oct 26 13:56 ./technical/biomed/1471-2091-2-16.txt
9947613       72 -rwxr-xr-x    1 heejin           staff               33005 Oct 26 13:56 ./technical/biomed/1476-4598-2-25.txt
9947353       32 -rwxr-xr-x    1 heejin           staff               16226 Oct 26 13:56 ./technical/biomed/1471-230X-2-21.txt
9947612       88 -rwxr-xr-x    1 heejin           staff               42549 Oct 26 13:56 ./technical/biomed/1476-4598-2-24.txt
9947381       48 -rwxr-xr-x    1 heejin           staff               23483 Oct 26 13:56 ./technical/biomed/1471-2350-2-2.txt
9947741      120 -rwxr-xr-x    1 heejin           staff               59433 Oct 26 13:56 ./technical/biomed/gb-2001-2-11-research0046.txt
9947481       80 -rwxr-xr-x    1 heejin           staff               37906 Oct 26 13:56 ./technical/biomed/1472-6769-1-1.txt
9947646       64 -rwxr-xr-x    1 heejin           staff               32393 Oct 26 13:56 ./technical/biomed/ar120.txt
9947132       40 -rwxr-xr-x    1 heejin           staff               16776 Oct 26 13:56 ./technical/biomed/1471-2148-2-14.txt
9947403       56 -rwxr-xr-x    1 heejin           staff               26498 Oct 26 13:56 ./technical/biomed/1471-2407-1-19.txt
9947761       56 -rwxr-xr-x    1 heejin           staff               25897 Oct 26 13:56 ./technical/biomed/gb-2001-2-8-research0032.txt
9947807      144 -rwxr-xr-x    1 heejin           staff               73428 Oct 26 13:56 ./technical/biomed/gb-2002-3-7-research0036.txt
9947426       48 -rwxr-xr-x    1 heejin           staff               22594 Oct 26 13:56 ./technical/biomed/1471-2415-3-1.txt
9947835       80 -rwxr-xr-x    1 heejin           staff               39796 Oct 26 13:56 ./technical/biomed/gb-2003-4-5-r32.txt
9947470       56 -rwxr-xr-x    1 heejin           staff               25697 Oct 26 13:56 ./technical/biomed/1472-6750-1-13.txt
9947546       48 -rwxr-xr-x    1 heejin           staff               22501 Oct 26 13:56 ./technical/biomed/1472-6920-1-3.txt
9947457       48 -rwxr-xr-x    1 heejin           staff               20548 Oct 26 13:56 ./technical/biomed/1471-2474-2-1.txt
9947600       48 -rwxr-xr-x    1 heejin           staff               20492 Oct 26 13:56 ./technical/biomed/1476-0711-2-3.txt
9947850       80 -rwxr-xr-x    1 heejin           staff               38006 Oct 26 13:56 ./technical/biomed/rr171.txt
9947154       80 -rwxr-xr-x    1 heejin           staff               39328 Oct 26 13:56 ./technical/biomed/1471-2156-3-16.txt
9947841      128 -rwxr-xr-x    1 heejin           staff               63280 Oct 26 13:56 ./technical/biomed/gb-2003-4-7-r43.txt
9947514       32 -rwxr-xr-x    1 heejin           staff               13059 Oct 26 13:56 ./technical/biomed/1472-6807-2-5.txt
9947389       32 -rwxr-xr-x    1 heejin           staff               13635 Oct 26 13:56 ./technical/biomed/1471-2350-4-4.txt
9947210       72 -rwxr-xr-x    1 heejin           staff               33407 Oct 26 13:56 ./technical/biomed/1471-2172-1-1.txt
9947650       40 -rwxr-xr-x    1 heejin           staff               18795 Oct 26 13:56 ./technical/biomed/ar297.txt
9947390       80 -rwxr-xr-x    1 heejin           staff               39062 Oct 26 13:56 ./technical/biomed/1471-2350-4-6.txt
9947849       80 -rwxr-xr-x    1 heejin           staff               36971 Oct 26 13:56 ./technical/biomed/rr167.txt
9947459       56 -rwxr-xr-x    1 heejin           staff               25964 Oct 26 13:56 ./technical/biomed/1471-2474-2-3.txt
9947090      128 -rwxr-xr-x    1 heejin           staff               62063 Oct 26 13:56 ./technical/biomed/1471-2121-3-15.txt
9947215       40 -rwxr-xr-x    1 heejin           staff               19007 Oct 26 13:56 ./technical/biomed/1471-2172-3-1.txt
9947542       80 -rwxr-xr-x    1 heejin           staff               38390 Oct 26 13:56 ./technical/biomed/1472-6904-2-4.txt
9947468       72 -rwxr-xr-x    1 heejin           staff               34610 Oct 26 13:56 ./technical/biomed/1472-6750-1-11.txt
9947834       72 -rwxr-xr-x    1 heejin           staff               36113 Oct 26 13:56 ./technical/biomed/gb-2003-4-5-r30.txt
9947818       88 -rwxr-xr-x    1 heejin           staff               44326 Oct 26 13:56 ./technical/biomed/gb-2002-3-9-research0051.txt
9947427       72 -rwxr-xr-x    1 heejin           staff               33886 Oct 26 13:56 ./technical/biomed/1471-2415-3-3.txt
9947814      120 -rwxr-xr-x    1 heejin           staff               58484 Oct 26 13:56 ./technical/biomed/gb-2002-3-9-research0045.txt
9947759      104 -rwxr-xr-x    1 heejin           staff               49958 Oct 26 13:56 ./technical/biomed/gb-2001-2-8-research0030.txt
9947698       88 -rwxr-xr-x    1 heejin           staff               44886 Oct 26 13:56 ./technical/biomed/bcr631.txt
9947483       32 -rwxr-xr-x    1 heejin           staff               14626 Oct 26 13:56 ./technical/biomed/1472-6769-1-3.txt
9947721       48 -rwxr-xr-x    1 heejin           staff               22668 Oct 26 13:56 ./technical/biomed/cc3.txt
9947242       48 -rwxr-xr-x    1 heejin           staff               21144 Oct 26 13:56 ./technical/biomed/1471-2180-2-32.txt
9947303       64 -rwxr-xr-x    1 heejin           staff               29125 Oct 26 13:56 ./technical/biomed/1471-2202-4-16.txt
9947240       56 -rwxr-xr-x    1 heejin           staff               24787 Oct 26 13:56 ./technical/biomed/1471-2180-2-26.txt
9947433       40 -rwxr-xr-x    1 heejin           staff               18045 Oct 26 13:56 ./technical/biomed/1471-2431-2-4.txt
9947449       64 -rwxr-xr-x    1 heejin           staff               31894 Oct 26 13:56 ./technical/biomed/1471-2458-3-2.txt
9947593       56 -rwxr-xr-x    1 heejin           staff               26713 Oct 26 13:56 ./technical/biomed/1475-9276-1-3.txt
9947653       56 -rwxr-xr-x    1 heejin           staff               24928 Oct 26 13:56 ./technical/biomed/ar321.txt
9947354       40 -rwxr-xr-x    1 heejin           staff               19639 Oct 26 13:56 ./technical/biomed/1471-230X-2-23.txt
9947651       40 -rwxr-xr-x    1 heejin           staff               19157 Oct 26 13:56 ./technical/biomed/ar309.txt
9947752       72 -rwxr-xr-x    1 heejin           staff               34260 Oct 26 13:56 ./technical/biomed/gb-2001-2-4-research0014.txt
9947626       24 -rwxr-xr-x    1 heejin           staff               12265 Oct 26 13:56 ./technical/biomed/1477-7819-1-10.txt
9947740       72 -rwxr-xr-x    1 heejin           staff               34018 Oct 26 13:56 ./technical/biomed/gb-2001-2-11-research0045.txt
9947304       64 -rwxr-xr-x    1 heejin           staff               29568 Oct 26 13:56 ./technical/biomed/1471-2202-4-17.txt
9947482       32 -rwxr-xr-x    1 heejin           staff               15688 Oct 26 13:56 ./technical/biomed/1472-6769-1-2.txt
9947696       56 -rwxr-xr-x    1 heejin           staff               24966 Oct 26 13:56 ./technical/biomed/bcr618.txt
9947806       96 -rwxr-xr-x    1 heejin           staff               48887 Oct 26 13:56 ./technical/biomed/gb-2002-3-7-research0035.txt
9947760       96 -rwxr-xr-x    1 heejin           staff               47386 Oct 26 13:56 ./technical/biomed/gb-2001-2-8-research0031.txt
9947134       96 -rwxr-xr-x    1 heejin           staff               46786 Oct 26 13:56 ./technical/biomed/1471-2148-2-17.txt
9947327       72 -rwxr-xr-x    1 heejin           staff               33066 Oct 26 13:56 ./technical/biomed/1471-2229-2-4.txt
9947384       96 -rwxr-xr-x    1 heejin           staff               47393 Oct 26 13:56 ./technical/biomed/1471-2350-3-12.txt
9947813       64 -rwxr-xr-x    1 heejin           staff               32469 Oct 26 13:56 ./technical/biomed/gb-2002-3-9-research0044.txt
9947399       40 -rwxr-xr-x    1 heejin           staff               19796 Oct 26 13:56 ./technical/biomed/1471-2377-2-6.txt
9947462       40 -rwxr-xr-x    1 heejin           staff               19899 Oct 26 13:56 ./technical/biomed/1471-2474-4-4.txt
9947543      176 -rwxr-xr-x    1 heejin           staff               89104 Oct 26 13:56 ./technical/biomed/1472-6904-2-5.txt
9947520       72 -rwxr-xr-x    1 heejin           staff               34387 Oct 26 13:56 ./technical/biomed/1472-6823-3-1.txt
9947458       56 -rwxr-xr-x    1 heejin           staff               27445 Oct 26 13:56 ./technical/biomed/1471-2474-2-2.txt
9947848       48 -rwxr-xr-x    1 heejin           staff               22439 Oct 26 13:56 ./technical/biomed/rr166.txt
9947851       56 -rwxr-xr-x    1 heejin           staff               24900 Oct 26 13:56 ./technical/biomed/rr172.txt
9947150       40 -rwxr-xr-x    1 heejin           staff               17411 Oct 26 13:56 ./technical/biomed/1471-2156-2-7.txt
9947486       48 -rwxr-xr-x    1 heejin           staff               21135 Oct 26 13:56 ./technical/biomed/1472-6785-1-5.txt
9947680       80 -rwxr-xr-x    1 heejin           staff               40398 Oct 26 13:56 ./technical/biomed/bcr284.txt
9947791       80 -rwxr-xr-x    1 heejin           staff               38916 Oct 26 13:56 ./technical/biomed/gb-2002-3-2-research0008.txt
9947772      152 -rwxr-xr-x    1 heejin           staff               74234 Oct 26 13:56 ./technical/biomed/gb-2002-3-11-research0059.txt
9947719       40 -rwxr-xr-x    1 heejin           staff               20124 Oct 26 13:56 ./technical/biomed/cc2190.txt
9947776      104 -rwxr-xr-x    1 heejin           staff               51918 Oct 26 13:56 ./technical/biomed/gb-2002-3-11-research0065.txt
9947122       56 -rwxr-xr-x    1 heejin           staff               26809 Oct 26 13:56 ./technical/biomed/1471-213X-3-2.txt
9947140       64 -rwxr-xr-x    1 heejin           staff               29059 Oct 26 13:56 ./technical/biomed/1471-2148-3-18.txt
9947330       32 -rwxr-xr-x    1 heejin           staff               15141 Oct 26 13:56 ./technical/biomed/1471-2229-3-3.txt
9947222       56 -rwxr-xr-x    1 heejin           staff               27888 Oct 26 13:56 ./technical/biomed/1471-2172-4-1.txt
9947676       56 -rwxr-xr-x    1 heejin           staff               27719 Oct 26 13:56 ./technical/biomed/ar795.txt
9947173       48 -rwxr-xr-x    1 heejin           staff               22329 Oct 26 13:56 ./technical/biomed/1471-2164-3-15.txt
9947711       40 -rwxr-xr-x    1 heejin           staff               16482 Oct 26 13:56 ./technical/biomed/cc1843.txt
9947182       48 -rwxr-xr-x    1 heejin           staff               22442 Oct 26 13:56 ./technical/biomed/1471-2164-3-29.txt
9947442       56 -rwxr-xr-x    1 heejin           staff               26515 Oct 26 13:56 ./technical/biomed/1471-2458-2-16.txt
9947586       88 -rwxr-xr-x    1 heejin           staff               41765 Oct 26 13:56 ./technical/biomed/1475-925X-2-10.txt
9947516      144 -rwxr-xr-x    1 heejin           staff               73091 Oct 26 13:56 ./technical/biomed/1472-6807-3-1.txt
9947846       56 -rwxr-xr-x    1 heejin           staff               27080 Oct 26 13:56 ./technical/biomed/gb-2003-4-9-r58.txt
9947072       48 -rwxr-xr-x    1 heejin           staff               23355 Oct 26 13:56 ./technical/biomed/1471-2105-4-27.txt
9947050       48 -rwxr-xr-x    1 heejin           staff               21074 Oct 26 13:56 ./technical/biomed/1471-2105-3-12.txt
9947825       64 -rwxr-xr-x    1 heejin           staff               32489 Oct 26 13:56 ./technical/biomed/gb-2003-4-2-r16.txt
9947659       56 -rwxr-xr-x    1 heejin           staff               26013 Oct 26 13:56 ./technical/biomed/ar408.txt
9947660       56 -rwxr-xr-x    1 heejin           staff               27953 Oct 26 13:56 ./technical/biomed/ar409.txt
9947405       64 -rwxr-xr-x    1 heejin           staff               30455 Oct 26 13:56 ./technical/biomed/1471-2407-2-11.txt
9947738       72 -rwxr-xr-x    1 heejin           staff               36125 Oct 26 13:56 ./technical/biomed/gb-2001-2-10-research0041.txt
9947342       80 -rwxr-xr-x    1 heejin           staff               39781 Oct 26 13:56 ./technical/biomed/1471-2288-3-4.txt
9947071       64 -rwxr-xr-x    1 heejin           staff               29786 Oct 26 13:56 ./technical/biomed/1471-2105-4-26.txt
9947349       48 -rwxr-xr-x    1 heejin           staff               22520 Oct 26 13:56 ./technical/biomed/1471-230X-1-5.txt
9947811       56 -rwxr-xr-x    1 heejin           staff               25182 Oct 26 13:56 ./technical/biomed/gb-2002-3-8-research0040.txt
9947587       40 -rwxr-xr-x    1 heejin           staff               17188 Oct 26 13:56 ./technical/biomed/1475-925X-2-11.txt
9947762       48 -rwxr-xr-x    1 heejin           staff               22853 Oct 26 13:56 ./technical/biomed/gb-2001-2-9-research0035.txt
9947217       72 -rwxr-xr-x    1 heejin           staff               33309 Oct 26 13:56 ./technical/biomed/1471-2172-3-12.txt
9947837       88 -rwxr-xr-x    1 heejin           staff               41587 Oct 26 13:56 ./technical/biomed/gb-2003-4-6-r37.txt
9947472       48 -rwxr-xr-x    1 heejin           staff               24163 Oct 26 13:56 ./technical/biomed/1472-6750-1-8.txt
9947438       64 -rwxr-xr-x    1 heejin           staff               32110 Oct 26 13:56 ./technical/biomed/1471-244X-2-9.txt
9947787       96 -rwxr-xr-x    1 heejin           staff               48768 Oct 26 13:56 ./technical/biomed/gb-2002-3-12-research0085.txt
9947108       40 -rwxr-xr-x    1 heejin           staff               16722 Oct 26 13:56 ./technical/biomed/1471-213X-1-1.txt
9947200       80 -rwxr-xr-x    1 heejin           staff               40895 Oct 26 13:56 ./technical/biomed/1471-2164-4-21.txt
9947713       40 -rwxr-xr-x    1 heejin           staff               17889 Oct 26 13:56 ./technical/biomed/cc1856.txt
9947249       80 -rwxr-xr-x    1 heejin           staff               39977 Oct 26 13:56 ./technical/biomed/1471-2180-3-15.txt
9947181       80 -rwxr-xr-x    1 heejin           staff               39250 Oct 26 13:56 ./technical/biomed/1471-2164-3-28.txt
9947702       48 -rwxr-xr-x    1 heejin           staff               21650 Oct 26 13:56 ./technical/biomed/cc105.txt
9947271       32 -rwxr-xr-x    1 heejin           staff               16156 Oct 26 13:56 ./technical/biomed/1471-2202-2-10.txt
9947233       72 -rwxr-xr-x    1 heejin           staff               35320 Oct 26 13:56 ./technical/biomed/1471-2180-1-8.txt
9947434       56 -rwxr-xr-x    1 heejin           staff               25954 Oct 26 13:56 ./technical/biomed/1471-2431-3-3.txt
9947392       48 -rwxr-xr-x    1 heejin           staff               22598 Oct 26 13:56 ./technical/biomed/1471-2369-3-10.txt
9947123      112 -rwxr-xr-x    1 heejin           staff               55468 Oct 26 13:56 ./technical/biomed/1471-213X-3-3.txt
9947707       48 -rwxr-xr-x    1 heejin           staff               23920 Oct 26 13:56 ./technical/biomed/cc1498.txt
9947397       32 -rwxr-xr-x    1 heejin           staff               16023 Oct 26 13:56 ./technical/biomed/1471-2377-1-2.txt
9947385       40 -rwxr-xr-x    1 heejin           staff               18161 Oct 26 13:56 ./technical/biomed/1471-2350-3-7.txt
9947792       48 -rwxr-xr-x    1 heejin           staff               22813 Oct 26 13:56 ./technical/biomed/gb-2002-3-2-research0009.txt
9947681       72 -rwxr-xr-x    1 heejin           staff               35311 Oct 26 13:56 ./technical/biomed/bcr285.txt
9947804       72 -rwxr-xr-x    1 heejin           staff               34079 Oct 26 13:56 ./technical/biomed/gb-2002-3-6-software0001.txt
9947571       72 -rwxr-xr-x    1 heejin           staff               34655 Oct 26 13:56 ./technical/biomed/1475-2867-3-12.txt
9947323       56 -rwxr-xr-x    1 heejin           staff               25656 Oct 26 13:56 ./technical/biomed/1471-2229-1-2.txt
9947423       80 -rwxr-xr-x    1 heejin           staff               39297 Oct 26 13:56 ./technical/biomed/1471-2407-3-3.txt
9947538       88 -rwxr-xr-x    1 heejin           staff               42977 Oct 26 13:56 ./technical/biomed/1472-6890-1-4.txt
9947223       56 -rwxr-xr-x    1 heejin           staff               28351 Oct 26 13:56 ./technical/biomed/1471-2172-4-2.txt
9947174       56 -rwxr-xr-x    1 heejin           staff               27283 Oct 26 13:56 ./technical/biomed/1471-2164-3-16.txt
9947037       80 -rwxr-xr-x    1 heejin           staff               40558 Oct 26 13:56 ./technical/biomed/1471-2091-3-18.txt
9947272       64 -rwxr-xr-x    1 heejin           staff               29596 Oct 26 13:56 ./technical/biomed/1471-2202-2-12.txt
9947202       64 -rwxr-xr-x    1 heejin           staff               31625 Oct 26 13:56 ./technical/biomed/1471-2164-4-23.txt
9947115       80 -rwxr-xr-x    1 heejin           staff               39354 Oct 26 13:56 ./technical/biomed/1471-213X-1-3.txt
9947789       96 -rwxr-xr-x    1 heejin           staff               46321 Oct 26 13:56 ./technical/biomed/gb-2002-3-12-research0087.txt
9947040       72 -rwxr-xr-x    1 heejin           staff               34168 Oct 26 13:56 ./technical/biomed/1471-2091-3-30.txt
9947781       72 -rwxr-xr-x    1 heejin           staff               34732 Oct 26 13:56 ./technical/biomed/gb-2002-3-12-research0078.txt
9947193       64 -rwxr-xr-x    1 heejin           staff               29123 Oct 26 13:56 ./technical/biomed/1471-2164-3-9.txt
9947216       80 -rwxr-xr-x    1 heejin           staff               40190 Oct 26 13:56 ./technical/biomed/1471-2172-3-10.txt
9947213       72 -rwxr-xr-x    1 heejin           staff               35974 Oct 26 13:56 ./technical/biomed/1471-2172-2-4.txt
9947224       72 -rwxr-xr-x    1 heejin           staff               36285 Oct 26 13:56 ./technical/biomed/1471-2180-1-12.txt
9947753       88 -rwxr-xr-x    1 heejin           staff               42611 Oct 26 13:56 ./technical/biomed/gb-2001-2-6-research0018.txt
9947763       88 -rwxr-xr-x    1 heejin           staff               44019 Oct 26 13:56 ./technical/biomed/gb-2001-2-9-research0037.txt
9947049       56 -rwxr-xr-x    1 heejin           staff               25632 Oct 26 13:56 ./technical/biomed/1471-2105-2-9.txt
9947545      128 -rwxr-xr-x    1 heejin           staff               63901 Oct 26 13:56 ./technical/biomed/1472-6904-3-1.txt
9947497       64 -rwxr-xr-x    1 heejin           staff               29048 Oct 26 13:56 ./technical/biomed/1472-6793-2-16.txt
9947517       40 -rwxr-xr-x    1 heejin           staff               20394 Oct 26 13:56 ./technical/biomed/1472-6807-3-2.txt
9947603      104 -rwxr-xr-x    1 heejin           staff               51827 Oct 26 13:56 ./technical/biomed/1476-072X-2-4.txt
9947081       80 -rwxr-xr-x    1 heejin           staff               39018 Oct 26 13:56 ./technical/biomed/1471-2121-2-18.txt
9947138       72 -rwxr-xr-x    1 heejin           staff               34954 Oct 26 13:56 ./technical/biomed/1471-2148-2-8.txt
9947069       64 -rwxr-xr-x    1 heejin           staff               31885 Oct 26 13:56 ./technical/biomed/1471-2105-4-24.txt
9947157       48 -rwxr-xr-x    1 heejin           staff               21552 Oct 26 13:56 ./technical/biomed/1471-2156-3-3.txt
9947454       72 -rwxr-xr-x    1 heejin           staff               34691 Oct 26 13:56 ./technical/biomed/1471-2466-2-3.txt
9947356       48 -rwxr-xr-x    1 heejin           staff               21842 Oct 26 13:56 ./technical/biomed/1471-230X-3-5.txt
9947406       40 -rwxr-xr-x    1 heejin           staff               18959 Oct 26 13:56 ./technical/biomed/1471-2407-2-12.txt
9947824      112 -rwxr-xr-x    1 heejin           staff               55514 Oct 26 13:56 ./technical/biomed/gb-2003-4-2-r14.txt
9947541       64 -rwxr-xr-x    1 heejin           staff               29304 Oct 26 13:56 ./technical/biomed/1472-6904-1-2.txt
9947709       64 -rwxr-xr-x    1 heejin           staff               29974 Oct 26 13:56 ./technical/biomed/cc1538.txt
9947070       40 -rwxr-xr-x    1 heejin           staff               20276 Oct 26 13:56 ./technical/biomed/1471-2105-4-25.txt
9947065       64 -rwxr-xr-x    1 heejin           staff               32376 Oct 26 13:56 ./technical/biomed/1471-2105-3-38.txt
9947661       64 -rwxr-xr-x    1 heejin           staff               31030 Oct 26 13:56 ./technical/biomed/ar422.txt
9947739       88 -rwxr-xr-x    1 heejin           staff               44791 Oct 26 13:56 ./technical/biomed/gb-2001-2-10-research0042.txt
9947074       56 -rwxr-xr-x    1 heejin           staff               27649 Oct 26 13:56 ./technical/biomed/1471-2105-4-31.txt
9947522       64 -rwxr-xr-x    1 heejin           staff               30221 Oct 26 13:56 ./technical/biomed/1472-6831-3-1.txt
9947657       40 -rwxr-xr-x    1 heejin           staff               18845 Oct 26 13:56 ./technical/biomed/ar387.txt
9947350       32 -rwxr-xr-x    1 heejin           staff               13669 Oct 26 13:56 ./technical/biomed/1471-230X-1-6.txt
9947498       56 -rwxr-xr-x    1 heejin           staff               25629 Oct 26 13:56 ./technical/biomed/1472-6793-2-17.txt
9947147       80 -rwxr-xr-x    1 heejin           staff               37452 Oct 26 13:56 ./technical/biomed/1471-2156-2-18.txt
9947048      136 -rwxr-xr-x    1 heejin           staff               68152 Oct 26 13:56 ./technical/biomed/1471-2105-2-8.txt
9947588       48 -rwxr-xr-x    1 heejin           staff               23897 Oct 26 13:56 ./technical/biomed/1475-925X-2-12.txt
9947643       72 -rwxr-xr-x    1 heejin           staff               33145 Oct 26 13:56 ./technical/biomed/1478-7954-1-3.txt
9947509       40 -rwxr-xr-x    1 heejin           staff               17081 Oct 26 13:56 ./technical/biomed/1472-6807-1-1.txt
9947714       48 -rwxr-xr-x    1 heejin           staff               23617 Oct 26 13:56 ./technical/biomed/cc1882.txt
9947192       72 -rwxr-xr-x    1 heejin           staff               32805 Oct 26 13:56 ./technical/biomed/1471-2164-3-8.txt
9947252       72 -rwxr-xr-x    1 heejin           staff               35916 Oct 26 13:56 ./technical/biomed/1471-2180-3-9.txt
9947782      120 -rwxr-xr-x    1 heejin           staff               59919 Oct 26 13:56 ./technical/biomed/gb-2002-3-12-research0079.txt
9947041      112 -rwxr-xr-x    1 heejin           staff               56000 Oct 26 13:56 ./technical/biomed/1471-2091-3-31.txt
9947788      168 -rwxr-xr-x    1 heejin           staff               83990 Oct 26 13:56 ./technical/biomed/gb-2002-3-12-research0086.txt
9947201       72 -rwxr-xr-x    1 heejin           staff               35306 Oct 26 13:56 ./technical/biomed/1471-2164-4-22.txt
9947114       88 -rwxr-xr-x    1 heejin           staff               42612 Oct 26 13:56 ./technical/biomed/1471-213X-1-2.txt
9947299       56 -rwxr-xr-x    1 heejin           staff               26090 Oct 26 13:56 ./technical/biomed/1471-2202-3-8.txt
9947447       64 -rwxr-xr-x    1 heejin           staff               31785 Oct 26 13:56 ./technical/biomed/1471-2458-2-6.txt
9947636       56 -rwxr-xr-x    1 heejin           staff               25856 Oct 26 13:56 ./technical/biomed/1477-7827-1-48.txt
9947324       40 -rwxr-xr-x    1 heejin           staff               20162 Oct 26 13:56 ./technical/biomed/1471-2229-1-3.txt
9947124       96 -rwxr-xr-x    1 heejin           staff               48262 Oct 26 13:56 ./technical/biomed/1471-213X-3-4.txt
9947722       48 -rwxr-xr-x    1 heejin           staff               23472 Oct 26 13:56 ./technical/biomed/cc300.txt
9947594       56 -rwxr-xr-x    1 heejin           staff               26286 Oct 26 13:56 ./technical/biomed/1476-069X-1-3.txt
9947331       40 -rwxr-xr-x    1 heejin           staff               17890 Oct 26 13:56 ./technical/biomed/1471-2253-1-1.txt
9947435       72 -rwxr-xr-x    1 heejin           staff               36152 Oct 26 13:56 ./technical/biomed/1471-2431-3-4.txt
9947320       48 -rwxr-xr-x    1 heejin           staff               21547 Oct 26 13:56 ./technical/biomed/1471-2210-2-9.txt
9947785       88 -rwxr-xr-x    1 heejin           staff               42932 Oct 26 13:56 ./technical/biomed/gb-2002-3-12-research0082.txt
9947117       80 -rwxr-xr-x    1 heejin           staff               37943 Oct 26 13:56 ./technical/biomed/1471-213X-1-6.txt
9947205       64 -rwxr-xr-x    1 heejin           staff               31252 Oct 26 13:56 ./technical/biomed/1471-2164-4-26.txt
9947172       56 -rwxr-xr-x    1 heejin           staff               25132 Oct 26 13:56 ./technical/biomed/1471-2164-3-13.txt
9947276       64 -rwxr-xr-x    1 heejin           staff               29890 Oct 26 13:56 ./technical/biomed/1471-2202-2-17.txt
9947529       40 -rwxr-xr-x    1 heejin           staff               18530 Oct 26 13:56 ./technical/biomed/1472-6874-3-2.txt
9947673       80 -rwxr-xr-x    1 heejin           staff               39259 Oct 26 13:56 ./technical/biomed/ar778.txt
9947671       40 -rwxr-xr-x    1 heejin           staff               18059 Oct 26 13:56 ./technical/biomed/ar750.txt
9947461       48 -rwxr-xr-x    1 heejin           staff               20593 Oct 26 13:56 ./technical/biomed/1471-2474-3-3.txt
9947487       56 -rwxr-xr-x    1 heejin           staff               25115 Oct 26 13:56 ./technical/biomed/1472-6785-2-6.txt
9947464       16 -rwxr-xr-x    1 heejin           staff                6804 Oct 26 13:56 ./technical/biomed/1471-2490-3-2.txt
9947639       96 -rwxr-xr-x    1 heejin           staff               45807 Oct 26 13:56 ./technical/biomed/1477-7827-1-9.txt
9947755       72 -rwxr-xr-x    1 heejin           staff               36620 Oct 26 13:56 ./technical/biomed/gb-2001-2-6-research0021.txt
9947668       56 -rwxr-xr-x    1 heejin           staff               25700 Oct 26 13:56 ./technical/biomed/ar624.txt
9947082       64 -rwxr-xr-x    1 heejin           staff               29502 Oct 26 13:56 ./technical/biomed/1471-2121-2-21.txt
9947548       40 -rwxr-xr-x    1 heejin           staff               19761 Oct 26 13:56 ./technical/biomed/1472-6920-2-3.txt
9947656       32 -rwxr-xr-x    1 heejin           staff               14731 Oct 26 13:56 ./technical/biomed/ar383.txt
9947051      112 -rwxr-xr-x    1 heejin           staff               54441 Oct 26 13:56 ./technical/biomed/1471-2105-3-14.txt
9947408       48 -rwxr-xr-x    1 heejin           staff               23819 Oct 26 13:56 ./technical/biomed/1471-2407-2-16.txt
9947060       80 -rwxr-xr-x    1 heejin           staff               38482 Oct 26 13:56 ./technical/biomed/1471-2105-3-28.txt
9947823       88 -rwxr-xr-x    1 heejin           staff               42624 Oct 26 13:56 ./technical/biomed/gb-2003-4-2-r11.txt
9947708       56 -rwxr-xr-x    1 heejin           staff               25108 Oct 26 13:56 ./technical/biomed/cc1529.txt
9947409       96 -rwxr-xr-x    1 heejin           staff               45137 Oct 26 13:56 ./technical/biomed/1471-2407-2-17.txt
9947518       64 -rwxr-xr-x    1 heejin           staff               32679 Oct 26 13:56 ./technical/biomed/1472-6815-2-3.txt
9947667       40 -rwxr-xr-x    1 heejin           staff               19149 Oct 26 13:56 ./technical/biomed/ar619.txt
9947441       56 -rwxr-xr-x    1 heejin           staff               26761 Oct 26 13:56 ./technical/biomed/1471-2458-2-11.txt
9947754       56 -rwxr-xr-x    1 heejin           staff               27074 Oct 26 13:56 ./technical/biomed/gb-2001-2-6-research0020.txt
9947488       80 -rwxr-xr-x    1 heejin           staff               40558 Oct 26 13:56 ./technical/biomed/1472-6785-2-7.txt
9947225       56 -rwxr-xr-x    1 heejin           staff               27490 Oct 26 13:56 ./technical/biomed/1471-2180-1-16.txt
9947670       56 -rwxr-xr-x    1 heejin           staff               27848 Oct 26 13:56 ./technical/biomed/ar745.txt
9947540       72 -rwxr-xr-x    1 heejin           staff               34258 Oct 26 13:56 ./technical/biomed/1472-6890-3-2.txt
9947700       64 -rwxr-xr-x    1 heejin           staff               30360 Oct 26 13:56 ./technical/biomed/cc103.txt
9947275       72 -rwxr-xr-x    1 heejin           staff               32894 Oct 26 13:56 ./technical/biomed/1471-2202-2-16.txt
9947675       56 -rwxr-xr-x    1 heejin           staff               25237 Oct 26 13:56 ./technical/biomed/ar792.txt
9947786      176 -rwxr-xr-x    1 heejin           staff               88698 Oct 26 13:56 ./technical/biomed/gb-2002-3-12-research0083.txt
9947248       64 -rwxr-xr-x    1 heejin           staff               31355 Oct 26 13:56 ./technical/biomed/1471-2180-3-13.txt
9947319       56 -rwxr-xr-x    1 heejin           staff               25317 Oct 26 13:56 ./technical/biomed/1471-2210-2-8.txt
9947494       88 -rwxr-xr-x    1 heejin           staff               42284 Oct 26 13:56 ./technical/biomed/1472-6793-1-8.txt
9947446       64 -rwxr-xr-x    1 heejin           staff               29911 Oct 26 13:56 ./technical/biomed/1471-2458-2-3.txt
9947477       64 -rwxr-xr-x    1 heejin           staff               31607 Oct 26 13:56 ./technical/biomed/1472-6750-2-21.txt
9947436       72 -rwxr-xr-x    1 heejin           staff               34936 Oct 26 13:56 ./technical/biomed/1471-2431-3-5.txt
9947534       48 -rwxr-xr-x    1 heejin           staff               21093 Oct 26 13:56 ./technical/biomed/1472-6882-2-10.txt
9947383       96 -rwxr-xr-x    1 heejin           staff               48211 Oct 26 13:56 ./technical/biomed/1471-2350-3-1.txt
9947775       88 -rwxr-xr-x    1 heejin           staff               44323 Oct 26 13:56 ./technical/biomed/gb-2002-3-11-research0062.txt
9947535       32 -rwxr-xr-x    1 heejin           staff               15301 Oct 26 13:56 ./technical/biomed/1472-6882-2-5.txt
9947773       56 -rwxr-xr-x    1 heejin           staff               27931 Oct 26 13:56 ./technical/biomed/gb-2002-3-11-research0060.txt
9947125       72 -rwxr-xr-x    1 heejin           staff               34190 Oct 26 13:56 ./technical/biomed/1471-213X-3-7.txt
9947723       64 -rwxr-xr-x    1 heejin           staff               32569 Oct 26 13:56 ./technical/biomed/cc303.txt
9947704       48 -rwxr-xr-x    1 heejin           staff               22286 Oct 26 13:56 ./technical/biomed/cc1477.txt
9947425       48 -rwxr-xr-x    1 heejin           staff               24515 Oct 26 13:56 ./technical/biomed/1471-2407-3-5.txt
9947400      104 -rwxr-xr-x    1 heejin           staff               50740 Oct 26 13:56 ./technical/biomed/1471-2377-3-4.txt
9947247       80 -rwxr-xr-x    1 heejin           staff               37919 Oct 26 13:56 ./technical/biomed/1471-2180-3-11.txt
9947784       88 -rwxr-xr-x    1 heejin           staff               41121 Oct 26 13:56 ./technical/biomed/gb-2002-3-12-research0081.txt
9947712       64 -rwxr-xr-x    1 heejin           staff               31319 Oct 26 13:56 ./technical/biomed/cc1852.txt
9947204       40 -rwxr-xr-x    1 heejin           staff               20338 Oct 26 13:56 ./technical/biomed/1471-2164-4-25.txt
9947038       80 -rwxr-xr-x    1 heejin           staff               40379 Oct 26 13:56 ./technical/biomed/1471-2091-3-22.txt
9947273       48 -rwxr-xr-x    1 heejin           staff               23188 Oct 26 13:56 ./technical/biomed/1471-2202-2-14.txt
9947171       40 -rwxr-xr-x    1 heejin           staff               18841 Oct 26 13:56 ./technical/biomed/1471-2164-3-10.txt
9947198       64 -rwxr-xr-x    1 heejin           staff               31181 Oct 26 13:56 ./technical/biomed/1471-2164-4-19.txt
9947728       32 -rwxr-xr-x    1 heejin           staff               12557 Oct 26 13:56 ./technical/biomed/cc713.txt
9947218       88 -rwxr-xr-x    1 heejin           staff               41490 Oct 26 13:56 ./technical/biomed/1471-2172-3-16.txt
9947227       56 -rwxr-xr-x    1 heejin           staff               26000 Oct 26 13:56 ./technical/biomed/1471-2180-1-28.txt
9947348       56 -rwxr-xr-x    1 heejin           staff               25804 Oct 26 13:56 ./technical/biomed/1471-230X-1-10.txt
9947083       56 -rwxr-xr-x    1 heejin           staff               26337 Oct 26 13:56 ./technical/biomed/1471-2121-2-22.txt
9947369       56 -rwxr-xr-x    1 heejin           staff               25529 Oct 26 13:56 ./technical/biomed/1471-2334-2-29.txt
9947101       56 -rwxr-xr-x    1 heejin           staff               25531 Oct 26 13:56 ./technical/biomed/1471-2121-3-8.txt
9947558       56 -rwxr-xr-x    1 heejin           staff               27938 Oct 26 13:56 ./technical/biomed/1472-6963-1-8.txt
9947346       48 -rwxr-xr-x    1 heejin           staff               23589 Oct 26 13:56 ./technical/biomed/1471-2296-3-19.txt
9947407       56 -rwxr-xr-x    1 heejin           staff               28027 Oct 26 13:56 ./technical/biomed/1471-2407-2-15.txt
9947053       96 -rwxr-xr-x    1 heejin           staff               47239 Oct 26 13:56 ./technical/biomed/1471-2105-3-17.txt
9947355       48 -rwxr-xr-x    1 heejin           staff               21061 Oct 26 13:56 ./technical/biomed/1471-230X-3-3.txt
9947663       40 -rwxr-xr-x    1 heejin           staff               17933 Oct 26 13:56 ./technical/biomed/ar430.txt
9947158       96 -rwxr-xr-x    1 heejin           staff               46131 Oct 26 13:56 ./technical/biomed/1471-2156-3-4.txt
9947455       48 -rwxr-xr-x    1 heejin           staff               20589 Oct 26 13:56 ./technical/biomed/1471-2466-2-4.txt
9947345       64 -rwxr-xr-x    1 heejin           staff               31087 Oct 26 13:56 ./technical/biomed/1471-2296-3-18.txt
9947052       80 -rwxr-xr-x    1 heejin           staff               37446 Oct 26 13:56 ./technical/biomed/1471-2105-3-16.txt
9947547       72 -rwxr-xr-x    1 heejin           staff               32906 Oct 26 13:56 ./technical/biomed/1472-6920-2-1.txt
9947602       64 -rwxr-xr-x    1 heejin           staff               29768 Oct 26 13:56 ./technical/biomed/1476-072X-2-3.txt
9947847       56 -rwxr-xr-x    1 heejin           staff               27689 Oct 26 13:56 ./technical/biomed/gb-2003-4-9-r60.txt
9947648       80 -rwxr-xr-x    1 heejin           staff               38211 Oct 26 13:56 ./technical/biomed/ar140.txt
9947828      104 -rwxr-xr-x    1 heejin           staff               52824 Oct 26 13:56 ./technical/biomed/gb-2003-4-3-r17.txt
9947496       80 -rwxr-xr-x    1 heejin           staff               37722 Oct 26 13:56 ./technical/biomed/1472-6793-2-11.txt
9947519       40 -rwxr-xr-x    1 heejin           staff               19040 Oct 26 13:56 ./technical/biomed/1472-6823-2-2.txt
9947228       64 -rwxr-xr-x    1 heejin           staff               30845 Oct 26 13:56 ./technical/biomed/1471-2180-1-29.txt
9947212       96 -rwxr-xr-x    1 heejin           staff               46108 Oct 26 13:56 ./technical/biomed/1471-2172-2-3.txt
9947404       48 -rwxr-xr-x    1 heejin           staff               21314 Oct 26 13:56 ./technical/biomed/1471-2407-1-6.txt
9947031       56 -rwxr-xr-x    1 heejin           staff               25298 Oct 26 13:56 ./technical/biomed/1471-2091-2-9.txt
9947274       56 -rwxr-xr-x    1 heejin           staff               28119 Oct 26 13:56 ./technical/biomed/1471-2202-2-15.txt
9947039       72 -rwxr-xr-x    1 heejin           staff               33815 Oct 26 13:56 ./technical/biomed/1471-2091-3-23.txt
9947203       56 -rwxr-xr-x    1 heejin           staff               26222 Oct 26 13:56 ./technical/biomed/1471-2164-4-24.txt
9947116       40 -rwxr-xr-x    1 heejin           staff               18068 Oct 26 13:56 ./technical/biomed/1471-213X-1-4.txt
9947783       64 -rwxr-xr-x    1 heejin           staff               28874 Oct 26 13:56 ./technical/biomed/gb-2002-3-12-research0080.txt
9947246       64 -rwxr-xr-x    1 heejin           staff               30027 Oct 26 13:56 ./technical/biomed/1471-2180-3-10.txt
9947703       56 -rwxr-xr-x    1 heejin           staff               26600 Oct 26 13:56 ./technical/biomed/cc1476.txt
9947424       56 -rwxr-xr-x    1 heejin           staff               25661 Oct 26 13:56 ./technical/biomed/1471-2407-3-4.txt
9947437       48 -rwxr-xr-x    1 heejin           staff               22131 Oct 26 13:56 ./technical/biomed/1471-2431-3-6.txt
9947682       56 -rwxr-xr-x    1 heejin           staff               25685 Oct 26 13:56 ./technical/biomed/bcr294.txt
9947774       56 -rwxr-xr-x    1 heejin           staff               26586 Oct 26 13:56 ./technical/biomed/gb-2002-3-11-research0061.txt
9947634       80 -rwxr-xr-x    1 heejin           staff               39369 Oct 26 13:56 ./technical/biomed/1477-7827-1-43.txt
9947567       56 -rwxr-xr-x    1 heejin           staff               25725 Oct 26 13:56 ./technical/biomed/1475-2832-1-1.txt
9947263       64 -rwxr-xr-x    1 heejin           staff               30440 Oct 26 13:56 ./technical/biomed/1471-2199-3-12.txt
9947269       48 -rwxr-xr-x    1 heejin           staff               20783 Oct 26 13:56 ./technical/biomed/1471-2202-1-1.txt
9947474       40 -rwxr-xr-x    1 heejin           staff               19066 Oct 26 13:56 ./technical/biomed/1472-6750-2-13.txt
9947718       48 -rwxr-xr-x    1 heejin           staff               20745 Oct 26 13:56 ./technical/biomed/cc2172.txt
9947493       40 -rwxr-xr-x    1 heejin           staff               19300 Oct 26 13:56 ./technical/biomed/1472-6793-1-6.txt
9947318       72 -rwxr-xr-x    1 heejin           staff               35907 Oct 26 13:56 ./technical/biomed/1471-2210-2-6.txt
9947118       80 -rwxr-xr-x    1 heejin           staff               37729 Oct 26 13:56 ./technical/biomed/1471-213X-1-9.txt
9947187       48 -rwxr-xr-x    1 heejin           staff               20958 Oct 26 13:56 ./technical/biomed/1471-2164-3-34.txt
9947196       56 -rwxr-xr-x    1 heejin           staff               26254 Oct 26 13:56 ./technical/biomed/1471-2164-4-15.txt
9947295       72 -rwxr-xr-x    1 heejin           staff               35079 Oct 26 13:56 ./technical/biomed/1471-2202-3-3.txt
9947277       40 -rwxr-xr-x    1 heejin           staff               20061 Oct 26 13:56 ./technical/biomed/1471-2202-2-18.txt
9947720       40 -rwxr-xr-x    1 heejin           staff               18512 Oct 26 13:56 ./technical/biomed/cc2358.txt
9947506       56 -rwxr-xr-x    1 heejin           staff               26409 Oct 26 13:56 ./technical/biomed/1472-6793-3-4.txt
9947778      112 -rwxr-xr-x    1 heejin           staff               56348 Oct 26 13:56 ./technical/biomed/gb-2002-3-12-research0072.txt
9947561       40 -rwxr-xr-x    1 heejin           staff               16645 Oct 26 13:56 ./technical/biomed/1472-6963-3-11.txt
9947565       56 -rwxr-xr-x    1 heejin           staff               27276 Oct 26 13:56 ./technical/biomed/1472-6963-3-6.txt
9947615       32 -rwxr-xr-x    1 heejin           staff               15618 Oct 26 13:56 ./technical/biomed/1476-4598-2-3.txt
9947638       48 -rwxr-xr-x    1 heejin           staff               20506 Oct 26 13:56 ./technical/biomed/1477-7827-1-6.txt
9947583      128 -rwxr-xr-x    1 heejin           staff               62700 Oct 26 13:56 ./technical/biomed/1475-4924-1-10.txt
9947527       56 -rwxr-xr-x    1 heejin           staff               27708 Oct 26 13:56 ./technical/biomed/1472-6874-2-13.txt
9947396       40 -rwxr-xr-x    1 heejin           staff               18617 Oct 26 13:56 ./technical/biomed/1471-2369-4-5.txt
9947099       96 -rwxr-xr-x    1 heejin           staff               48187 Oct 26 13:56 ./technical/biomed/1471-2121-3-4.txt
9947079       56 -rwxr-xr-x    1 heejin           staff               26002 Oct 26 13:56 ./technical/biomed/1471-2121-2-12.txt
9947135       56 -rwxr-xr-x    1 heejin           staff               24898 Oct 26 13:56 ./technical/biomed/1471-2148-2-2.txt
9947590       80 -rwxr-xr-x    1 heejin           staff               39964 Oct 26 13:56 ./technical/biomed/1475-925X-2-6.txt
9947127       64 -rwxr-xr-x    1 heejin           staff               29403 Oct 26 13:56 ./technical/biomed/1471-2148-1-14.txt
9947411       64 -rwxr-xr-x    1 heejin           staff               29550 Oct 26 13:56 ./technical/biomed/1471-2407-2-19.txt
9947315       72 -rwxr-xr-x    1 heejin           staff               35701 Oct 26 13:56 ./technical/biomed/1471-2210-2-14.txt
9947574       72 -rwxr-xr-x    1 heejin           staff               36377 Oct 26 13:56 ./technical/biomed/1475-2867-3-4.txt
9947662       40 -rwxr-xr-x    1 heejin           staff               18681 Oct 26 13:56 ./technical/biomed/ar429.txt
9947415       40 -rwxr-xr-x    1 heejin           staff               19545 Oct 26 13:56 ./technical/biomed/1471-2407-2-31.txt
9947059       64 -rwxr-xr-x    1 heejin           staff               31764 Oct 26 13:56 ./technical/biomed/1471-2105-3-26.txt
9947624       40 -rwxr-xr-x    1 heejin           staff               17188 Oct 26 13:56 ./technical/biomed/1477-7525-1-12.txt
9947410       56 -rwxr-xr-x    1 heejin           staff               26749 Oct 26 13:56 ./technical/biomed/1471-2407-2-18.txt
9947068       80 -rwxr-xr-x    1 heejin           staff               37814 Oct 26 13:56 ./technical/biomed/1471-2105-4-13.txt
9947821       96 -rwxr-xr-x    1 heejin           staff               46030 Oct 26 13:56 ./technical/biomed/gb-2003-4-1-r5.txt
9947366       64 -rwxr-xr-x    1 heejin           staff               32166 Oct 26 13:56 ./technical/biomed/1471-2334-2-24.txt
9947357       72 -rwxr-xr-x    1 heejin           staff               33364 Oct 26 13:56 ./technical/biomed/1471-2318-3-2.txt
9947145       72 -rwxr-xr-x    1 heejin           staff               36043 Oct 26 13:56 ./technical/biomed/1471-2156-2-12.txt
9947229       64 -rwxr-xr-x    1 heejin           staff               29292 Oct 26 13:56 ./technical/biomed/1471-2180-1-31.txt
9947609       32 -rwxr-xr-x    1 heejin           staff               15818 Oct 26 13:56 ./technical/biomed/1476-4598-2-2.txt
9947524       56 -rwxr-xr-x    1 heejin           staff               24653 Oct 26 13:56 ./technical/biomed/1472-684X-2-1.txt
9947467       32 -rwxr-xr-x    1 heejin           staff               12826 Oct 26 13:56 ./technical/biomed/1471-5945-3-3.txt
9947566       80 -rwxr-xr-x    1 heejin           staff               37540 Oct 26 13:56 ./technical/biomed/1472-6963-3-7.txt
9947582       56 -rwxr-xr-x    1 heejin           staff               27864 Oct 26 13:56 ./technical/biomed/1475-2891-2-1.txt
9947029       96 -rwxr-xr-x    1 heejin           staff               45414 Oct 26 13:56 ./technical/biomed/1471-2091-2-5.txt
9947507       56 -rwxr-xr-x    1 heejin           staff               27647 Oct 26 13:56 ./technical/biomed/1472-6793-3-5.txt
9947584       64 -rwxr-xr-x    1 heejin           staff               29681 Oct 26 13:56 ./technical/biomed/1475-4924-1-5.txt
9947278       72 -rwxr-xr-x    1 heejin           staff               32908 Oct 26 13:56 ./technical/biomed/1471-2202-2-19.txt
9947032       64 -rwxr-xr-x    1 heejin           staff               29139 Oct 26 13:56 ./technical/biomed/1471-2091-3-13.txt
9947195       40 -rwxr-xr-x    1 heejin           staff               18940 Oct 26 13:56 ./technical/biomed/1471-2164-4-14.txt
9947188       72 -rwxr-xr-x    1 heejin           staff               36670 Oct 26 13:56 ./technical/biomed/1471-2164-3-35.txt
9947206       72 -rwxr-xr-x    1 heejin           staff               33886 Oct 26 13:56 ./technical/biomed/1471-2164-4-28.txt
9947716       72 -rwxr-xr-x    1 heejin           staff               33687 Oct 26 13:56 ./technical/biomed/cc2167.txt
9947679       88 -rwxr-xr-x    1 heejin           staff               43955 Oct 26 13:56 ./technical/biomed/bcr273.txt
9947637       80 -rwxr-xr-x    1 heejin           staff               40046 Oct 26 13:56 ./technical/biomed/1477-7827-1-54.txt
9947365       48 -rwxr-xr-x    1 heejin           staff               21319 Oct 26 13:56 ./technical/biomed/1471-2334-2-1.txt
9947262       56 -rwxr-xr-x    1 heejin           staff               25396 Oct 26 13:56 ./technical/biomed/1471-2199-3-11.txt
9947473       48 -rwxr-xr-x    1 heejin           staff               21912 Oct 26 13:56 ./technical/biomed/1472-6750-2-10.txt
9947317       72 -rwxr-xr-x    1 heejin           staff               33152 Oct 26 13:56 ./technical/biomed/1471-2210-2-5.txt
9947717       64 -rwxr-xr-x    1 heejin           staff               29402 Oct 26 13:56 ./technical/biomed/cc2171.txt
9947177       48 -rwxr-xr-x    1 heejin           staff               20694 Oct 26 13:56 ./technical/biomed/1471-2164-3-23.txt
9947197       72 -rwxr-xr-x    1 heejin           staff               33581 Oct 26 13:56 ./technical/biomed/1471-2164-4-16.txt
9947672       56 -rwxr-xr-x    1 heejin           staff               24602 Oct 26 13:56 ./technical/biomed/ar774.txt
9947616      168 -rwxr-xr-x    1 heejin           staff               83194 Oct 26 13:56 ./technical/biomed/1476-511X-1-2.txt
9947562       56 -rwxr-xr-x    1 heejin           staff               25064 Oct 26 13:56 ./technical/biomed/1472-6963-3-12.txt
9947030       56 -rwxr-xr-x    1 heejin           staff               25458 Oct 26 13:56 ./technical/biomed/1471-2091-2-7.txt
9947777      112 -rwxr-xr-x    1 heejin           staff               57162 Oct 26 13:56 ./technical/biomed/gb-2002-3-12-research0071.txt
9947230       64 -rwxr-xr-x    1 heejin           staff               30646 Oct 26 13:56 ./technical/biomed/1471-2180-1-33.txt
9947736       56 -rwxr-xr-x    1 heejin           staff               24629 Oct 26 13:56 ./technical/biomed/gb-2000-1-1-research002.txt
9947766       64 -rwxr-xr-x    1 heejin           staff               28714 Oct 26 13:56 ./technical/biomed/gb-2001-3-1-research0005.txt
9947685       88 -rwxr-xr-x    1 heejin           staff               44544 Oct 26 13:56 ./technical/biomed/bcr45.txt
9947044       64 -rwxr-xr-x    1 heejin           staff               30279 Oct 26 13:56 ./technical/biomed/1471-2091-4-1.txt
9947822       64 -rwxr-xr-x    1 heejin           staff               29546 Oct 26 13:56 ./technical/biomed/gb-2003-4-1-r7.txt
9947367       56 -rwxr-xr-x    1 heejin           staff               27094 Oct 26 13:56 ./technical/biomed/1471-2334-2-26.txt
9947078       88 -rwxr-xr-x    1 heejin           staff               42311 Oct 26 13:56 ./technical/biomed/1471-2121-2-11.txt
9947465       48 -rwxr-xr-x    1 heejin           staff               22954 Oct 26 13:56 ./technical/biomed/1471-5945-1-3.txt
9947054      160 -rwxr-xr-x    1 heejin           staff               78562 Oct 26 13:56 ./technical/biomed/1471-2105-3-18.txt
9947337       64 -rwxr-xr-x    1 heejin           staff               28796 Oct 26 13:56 ./technical/biomed/1471-2261-3-5.txt
9947058       24 -rwxr-xr-x    1 heejin           staff               12110 Oct 26 13:56 ./technical/biomed/1471-2105-3-24.txt
9947619       40 -rwxr-xr-x    1 heejin           staff               19791 Oct 26 13:56 ./technical/biomed/1476-5918-1-2.txt
9947623       48 -rwxr-xr-x    1 heejin           staff               21781 Oct 26 13:56 ./technical/biomed/1477-7525-1-10.txt
9947801       64 -rwxr-xr-x    1 heejin           staff               31838 Oct 26 13:56 ./technical/biomed/gb-2002-3-5-research0024.txt
9947062       88 -rwxr-xr-x    1 heejin           staff               43797 Oct 26 13:56 ./technical/biomed/1471-2105-3-30.txt
9947416       64 -rwxr-xr-x    1 heejin           staff               31098 Oct 26 13:56 ./technical/biomed/1471-2407-2-33.txt
9947802      104 -rwxr-xr-x    1 heejin           staff               49968 Oct 26 13:56 ./technical/biomed/gb-2002-3-5-research0025.txt
9947336       88 -rwxr-xr-x    1 heejin           staff               43855 Oct 26 13:56 ./technical/biomed/1471-2261-3-4.txt
9947265       88 -rwxr-xr-x    1 heejin           staff               41339 Oct 26 13:56 ./technical/biomed/1471-2199-3-3.txt
9947077      104 -rwxr-xr-x    1 heejin           staff               51543 Oct 26 13:56 ./technical/biomed/1471-2121-2-10.txt
9947100       80 -rwxr-xr-x    1 heejin           staff               39935 Oct 26 13:56 ./technical/biomed/1471-2121-3-6.txt
9947368       72 -rwxr-xr-x    1 heejin           staff               35377 Oct 26 13:56 ./technical/biomed/1471-2334-2-27.txt
9947765       56 -rwxr-xr-x    1 heejin           staff               26047 Oct 26 13:56 ./technical/biomed/gb-2001-3-1-research0004.txt
9947047       72 -rwxr-xr-x    1 heejin           staff               34261 Oct 26 13:56 ./technical/biomed/1471-2105-2-1.txt
9947334       40 -rwxr-xr-x    1 heejin           staff               19386 Oct 26 13:56 ./technical/biomed/1471-2261-1-6.txt
9947829       40 -rwxr-xr-x    1 heejin           staff               18620 Oct 26 13:56 ./technical/biomed/gb-2003-4-3-r18.txt
9947666       72 -rwxr-xr-x    1 heejin           staff               34084 Oct 26 13:56 ./technical/biomed/ar615.txt
9947664       40 -rwxr-xr-x    1 heejin           staff               18964 Oct 26 13:56 ./technical/biomed/ar601.txt
9947608       48 -rwxr-xr-x    1 heejin           staff               24279 Oct 26 13:56 ./technical/biomed/1476-4598-2-1.txt
9947525       64 -rwxr-xr-x    1 heejin           staff               29525 Oct 26 13:56 ./technical/biomed/1472-684X-2-2.txt
9947226       96 -rwxr-xr-x    1 heejin           staff               47026 Oct 26 13:56 ./technical/biomed/1471-2180-1-26.txt
9947444       56 -rwxr-xr-x    1 heejin           staff               27043 Oct 26 13:56 ./technical/biomed/1471-2458-2-21.txt
9947508       64 -rwxr-xr-x    1 heejin           staff               29507 Oct 26 13:56 ./technical/biomed/1472-6793-3-6.txt
9947563       40 -rwxr-xr-x    1 heejin           staff               20388 Oct 26 13:56 ./technical/biomed/1472-6963-3-13.txt
9947170       64 -rwxr-xr-x    1 heejin           staff               30676 Oct 26 13:56 ./technical/biomed/1471-2164-3-1.txt
9947287      152 -rwxr-xr-x    1 heejin           staff               75711 Oct 26 13:56 ./technical/biomed/1471-2202-3-1.txt
9947316       48 -rwxr-xr-x    1 heejin           staff               23490 Oct 26 13:56 ./technical/biomed/1471-2210-2-4.txt
9947261       40 -rwxr-xr-x    1 heejin           staff               19877 Oct 26 13:56 ./technical/biomed/1471-2199-3-10.txt
9947380       32 -rwxr-xr-x    1 heejin           staff               15134 Oct 26 13:56 ./technical/biomed/1471-2350-2-12.txt
9947386       56 -rwxr-xr-x    1 heejin           staff               26118 Oct 26 13:56 ./technical/biomed/1471-2350-3-9.txt
9947591       88 -rwxr-xr-x    1 heejin           staff               43338 Oct 26 13:56 ./technical/biomed/1475-9268-1-1.txt
9947746       72 -rwxr-xr-x    1 heejin           staff               36028 Oct 26 13:56 ./technical/biomed/gb-2001-2-2-research0004.txt
9947715       40 -rwxr-xr-x    1 heejin           staff               17840 Oct 26 13:56 ./technical/biomed/cc2160.txt
9947479       72 -rwxr-xr-x    1 heejin           staff               34558 Oct 26 13:56 ./technical/biomed/1472-6750-3-4.txt
9947297       96 -rwxr-xr-x    1 heejin           staff               47766 Oct 26 13:56 ./technical/biomed/1471-2202-3-5.txt
9947194       64 -rwxr-xr-x    1 heejin           staff               32319 Oct 26 13:56 ./technical/biomed/1471-2164-4-13.txt
9947033      112 -rwxr-xr-x    1 heejin           staff               54849 Oct 26 13:56 ./technical/biomed/1471-2091-3-14.txt
9947466       72 -rwxr-xr-x    1 heejin           staff               35587 Oct 26 13:56 ./technical/biomed/1471-5945-2-13.txt
9947185       64 -rwxr-xr-x    1 heejin           staff               29324 Oct 26 13:56 ./technical/biomed/1471-2164-3-32.txt
9947179       48 -rwxr-xr-x    1 heejin           staff               21046 Oct 26 13:56 ./technical/biomed/1471-2164-3-26.txt
9947340       64 -rwxr-xr-x    1 heejin           staff               30852 Oct 26 13:56 ./technical/biomed/1471-2288-2-11.txt
9947250       80 -rwxr-xr-x    1 heejin           staff               37694 Oct 26 13:56 ./technical/biomed/1471-2180-3-4.txt
9947471       64 -rwxr-xr-x    1 heejin           staff               31799 Oct 26 13:56 ./technical/biomed/1472-6750-1-6.txt
9947838      104 -rwxr-xr-x    1 heejin           staff               51187 Oct 26 13:56 ./technical/biomed/gb-2003-4-6-r39.txt
9947445       72 -rwxr-xr-x    1 heejin           staff               36580 Oct 26 13:56 ./technical/biomed/1471-2458-2-25.txt
9947830      104 -rwxr-xr-x    1 heejin           staff               51112 Oct 26 13:56 ./technical/biomed/gb-2003-4-3-r20.txt
9947845       72 -rwxr-xr-x    1 heejin           staff               35998 Oct 26 13:56 ./technical/biomed/gb-2003-4-9-r57.txt
9947094       72 -rwxr-xr-x    1 heejin           staff               34129 Oct 26 13:56 ./technical/biomed/1471-2121-3-2.txt
9947413       40 -rwxr-xr-x    1 heejin           staff               20230 Oct 26 13:56 ./technical/biomed/1471-2407-2-23.txt
9947073       72 -rwxr-xr-x    1 heejin           staff               33821 Oct 26 13:56 ./technical/biomed/1471-2105-4-28.txt
9947553       88 -rwxr-xr-x    1 heejin           staff               42551 Oct 26 13:56 ./technical/biomed/1472-6947-2-7.txt
9947798       72 -rwxr-xr-x    1 heejin           staff               32848 Oct 26 13:56 ./technical/biomed/gb-2002-3-5-research0021.txt
9947658       56 -rwxr-xr-x    1 heejin           staff               27321 Oct 26 13:56 ./technical/biomed/ar407.txt
9947266       64 -rwxr-xr-x    1 heejin           staff               29608 Oct 26 13:56 ./technical/biomed/1471-2199-3-7.txt
9947572       72 -rwxr-xr-x    1 heejin           staff               35654 Oct 26 13:56 ./technical/biomed/1475-2867-3-2.txt
9947585       48 -rwxr-xr-x    1 heejin           staff               21404 Oct 26 13:56 ./technical/biomed/1475-925X-2-1.txt
9947573       48 -rwxr-xr-x    1 heejin           staff               23790 Oct 26 13:56 ./technical/biomed/1475-2867-3-3.txt
9947063       72 -rwxr-xr-x    1 heejin           staff               34563 Oct 26 13:56 ./technical/biomed/1471-2105-3-34.txt
9947797       80 -rwxr-xr-x    1 heejin           staff               39368 Oct 26 13:56 ./technical/biomed/gb-2002-3-5-research0020.txt
9947412       48 -rwxr-xr-x    1 heejin           staff               22429 Oct 26 13:56 ./technical/biomed/1471-2407-2-22.txt
9947080       72 -rwxr-xr-x    1 heejin           staff               32852 Oct 26 13:56 ./technical/biomed/1471-2121-2-15.txt
9947136       32 -rwxr-xr-x    1 heejin           staff               14560 Oct 26 13:56 ./technical/biomed/1471-2148-2-5.txt
9947701       40 -rwxr-xr-x    1 heejin           staff               19035 Oct 26 13:56 ./technical/biomed/cc1044.txt
9947045       64 -rwxr-xr-x    1 heejin           staff               28719 Oct 26 13:56 ./technical/biomed/1471-2091-4-5.txt
9947338       56 -rwxr-xr-x    1 heejin           staff               25922 Oct 26 13:56 ./technical/biomed/1471-2288-1-9.txt
9947854       64 -rwxr-xr-x    1 heejin           staff               32562 Oct 26 13:56 ./technical/biomed/rr37.txt
9947764      120 -rwxr-xr-x    1 heejin           staff               60518 Oct 26 13:56 ./technical/biomed/gb-2001-3-1-research0001.txt
9947560       56 -rwxr-xr-x    1 heejin           staff               26929 Oct 26 13:56 ./technical/biomed/1472-6963-3-1.txt
9947214       40 -rwxr-xr-x    1 heejin           staff               19565 Oct 26 13:56 ./technical/biomed/1471-2172-2-9.txt
9947443       32 -rwxr-xr-x    1 heejin           staff               16116 Oct 26 13:56 ./technical/biomed/1471-2458-2-18.txt
9947251       88 -rwxr-xr-x    1 heejin           staff               43688 Oct 26 13:56 ./technical/biomed/1471-2180-3-5.txt
9947339       88 -rwxr-xr-x    1 heejin           staff               42772 Oct 26 13:56 ./technical/biomed/1471-2288-2-10.txt
9947189       96 -rwxr-xr-x    1 heejin           staff               45524 Oct 26 13:56 ./technical/biomed/1471-2164-3-4.txt
9947505       48 -rwxr-xr-x    1 heejin           staff               20943 Oct 26 13:56 ./technical/biomed/1472-6793-3-3.txt
9947779       48 -rwxr-xr-x    1 heejin           staff               22757 Oct 26 13:56 ./technical/biomed/gb-2002-3-12-research0075.txt
9947180       48 -rwxr-xr-x    1 heejin           staff               24329 Oct 26 13:56 ./technical/biomed/1471-2164-3-27.txt
9947186       64 -rwxr-xr-x    1 heejin           staff               32602 Oct 26 13:56 ./technical/biomed/1471-2164-3-33.txt
9947034       72 -rwxr-xr-x    1 heejin           staff               34209 Oct 26 13:56 ./technical/biomed/1471-2091-3-15.txt
9947296       64 -rwxr-xr-x    1 heejin           staff               32489 Oct 26 13:56 ./technical/biomed/1471-2202-3-4.txt
9947475       96 -rwxr-xr-x    1 heejin           staff               47947 Oct 26 13:56 ./technical/biomed/1472-6750-2-14.txt
9947232       80 -rwxr-xr-x    1 heejin           staff               38765 Oct 26 13:56 ./technical/biomed/1471-2180-1-7.txt
9947706       32 -rwxr-xr-x    1 heejin           staff               16242 Oct 26 13:56 ./technical/biomed/cc1497.txt
9947370       48 -rwxr-xr-x    1 heejin           staff               22233 Oct 26 13:56 ./technical/biomed/1471-2334-2-5.txt
9947264       48 -rwxr-xr-x    1 heejin           staff               22226 Oct 26 13:56 ./technical/biomed/1471-2199-3-17.txt
9947379       48 -rwxr-xr-x    1 heejin           staff               23338 Oct 26 13:56 ./technical/biomed/1471-2350-2-11.txt
9947372       56 -rwxr-xr-x    1 heejin           staff               27097 Oct 26 13:56 ./technical/biomed/1471-2334-2-7.txt
9947705       32 -rwxr-xr-x    1 heejin           staff               16376 Oct 26 13:56 ./technical/biomed/cc1495.txt
9947592       48 -rwxr-xr-x    1 heejin           staff               20942 Oct 26 13:56 ./technical/biomed/1475-9268-1-2.txt
9947635       96 -rwxr-xr-x    1 heejin           staff               48259 Oct 26 13:56 ./technical/biomed/1477-7827-1-46.txt
9947036       64 -rwxr-xr-x    1 heejin           staff               29469 Oct 26 13:56 ./technical/biomed/1471-2091-3-17.txt
9947677       56 -rwxr-xr-x    1 heejin           staff               25350 Oct 26 13:56 ./technical/biomed/ar799.txt
9947176       72 -rwxr-xr-x    1 heejin           staff               33671 Oct 26 13:56 ./technical/biomed/1471-2164-3-19.txt
9947790      104 -rwxr-xr-x    1 heejin           staff               51726 Oct 26 13:56 ./technical/biomed/gb-2002-3-12-research0088.txt
9947184       80 -rwxr-xr-x    1 heejin           staff               40400 Oct 26 13:56 ./technical/biomed/1471-2164-3-31.txt
9947780       88 -rwxr-xr-x    1 heejin           staff               41682 Oct 26 13:56 ./technical/biomed/gb-2002-3-12-research0077.txt
9947564       88 -rwxr-xr-x    1 heejin           staff               41716 Oct 26 13:56 ./technical/biomed/1472-6963-3-14.txt
9947575       72 -rwxr-xr-x    1 heejin           staff               33494 Oct 26 13:56 ./technical/biomed/1475-2875-1-14.txt
9947190       48 -rwxr-xr-x    1 heejin           staff               21289 Oct 26 13:56 ./technical/biomed/1471-2164-3-6.txt
9947844       48 -rwxr-xr-x    1 heejin           staff               20637 Oct 26 13:56 ./technical/biomed/gb-2003-4-8-r51.txt
9947579       64 -rwxr-xr-x    1 heejin           staff               29607 Oct 26 13:56 ./technical/biomed/1475-2875-2-4.txt
9947557       48 -rwxr-xr-x    1 heejin           staff               21711 Oct 26 13:56 ./technical/biomed/1472-6963-1-11.txt
9947665       56 -rwxr-xr-x    1 heejin           staff               28204 Oct 26 13:56 ./technical/biomed/ar612.txt
9947500       64 -rwxr-xr-x    1 heejin           staff               28870 Oct 26 13:56 ./technical/biomed/1472-6793-2-19.txt
9947351       40 -rwxr-xr-x    1 heejin           staff               17629 Oct 26 13:56 ./technical/biomed/1471-230X-1-8.txt
9947137       40 -rwxr-xr-x    1 heejin           staff               19427 Oct 26 13:56 ./technical/biomed/1471-2148-2-7.txt
9947799       80 -rwxr-xr-x    1 heejin           staff               38544 Oct 26 13:56 ./technical/biomed/gb-2002-3-5-research0022.txt
9947344       96 -rwxr-xr-x    1 heejin           staff               46390 Oct 26 13:56 ./technical/biomed/1471-2288-3-9.txt
9947056       64 -rwxr-xr-x    1 heejin           staff               29117 Oct 26 13:56 ./technical/biomed/1471-2105-3-22.txt
9947552       72 -rwxr-xr-x    1 heejin           staff               33905 Oct 26 13:56 ./technical/biomed/1472-6947-2-4.txt
9947684       48 -rwxr-xr-x    1 heejin           staff               23358 Oct 26 13:56 ./technical/biomed/bcr317.txt
9947589       40 -rwxr-xr-x    1 heejin           staff               17695 Oct 26 13:56 ./technical/biomed/1475-925X-2-3.txt
9947683       64 -rwxr-xr-x    1 heejin           staff               30804 Oct 26 13:56 ./technical/biomed/bcr303.txt
9947057       64 -rwxr-xr-x    1 heejin           staff               30792 Oct 26 13:56 ./technical/biomed/1471-2105-3-23.txt
9947343       48 -rwxr-xr-x    1 heejin           staff               23191 Oct 26 13:56 ./technical/biomed/1471-2288-3-8.txt
9947686       48 -rwxr-xr-x    1 heejin           staff               22904 Oct 26 13:56 ./technical/biomed/bcr458.txt
9947064       64 -rwxr-xr-x    1 heejin           staff               29508 Oct 26 13:56 ./technical/biomed/1471-2105-3-37.txt
9947800       40 -rwxr-xr-x    1 heejin           staff               19700 Oct 26 13:56 ./technical/biomed/gb-2002-3-5-research0023.txt
9947499       96 -rwxr-xr-x    1 heejin           staff               45713 Oct 26 13:56 ./technical/biomed/1472-6793-2-18.txt
9947146       56 -rwxr-xr-x    1 heejin           staff               27688 Oct 26 13:56 ./technical/biomed/1471-2156-2-17.txt
9947395       48 -rwxr-xr-x    1 heejin           staff               21464 Oct 26 13:56 ./technical/biomed/1471-2369-4-1.txt
9947649       56 -rwxr-xr-x    1 heejin           staff               25253 Oct 26 13:56 ./technical/biomed/ar149.txt
9947803       56 -rwxr-xr-x    1 heejin           staff               26711 Oct 26 13:56 ./technical/biomed/gb-2002-3-6-research0029.txt
9947075       64 -rwxr-xr-x    1 heejin           staff               29793 Oct 26 13:56 ./technical/biomed/1471-2121-1-2.txt
9947231       72 -rwxr-xr-x    1 heejin           staff               34076 Oct 26 13:56 ./technical/biomed/1471-2180-1-34.txt
9947843       64 -rwxr-xr-x    1 heejin           staff               29369 Oct 26 13:56 ./technical/biomed/gb-2003-4-8-r50.txt
9947191       80 -rwxr-xr-x    1 heejin           staff               40413 Oct 26 13:56 ./technical/biomed/1471-2164-3-7.txt
9947183       40 -rwxr-xr-x    1 heejin           staff               18364 Oct 26 13:56 ./technical/biomed/1471-2164-3-30.txt
9947280       88 -rwxr-xr-x    1 heejin           staff               41831 Oct 26 13:56 ./technical/biomed/1471-2202-2-20.txt
9947178       72 -rwxr-xr-x    1 heejin           staff               35306 Oct 26 13:56 ./technical/biomed/1471-2164-3-24.txt
9947298       64 -rwxr-xr-x    1 heejin           staff               28821 Oct 26 13:56 ./technical/biomed/1471-2202-3-7.txt
9947035       72 -rwxr-xr-x    1 heejin           staff               35953 Oct 26 13:56 ./technical/biomed/1471-2091-3-16.txt
9947175       96 -rwxr-xr-x    1 heejin           staff               47848 Oct 26 13:56 ./technical/biomed/1471-2164-3-18.txt
9947480       80 -rwxr-xr-x    1 heejin           staff               36952 Oct 26 13:56 ./technical/biomed/1472-6750-3-6.txt
9947492       64 -rwxr-xr-x    1 heejin           staff               32160 Oct 26 13:56 ./technical/biomed/1472-6793-1-2.txt
9947371       72 -rwxr-xr-x    1 heejin           staff               33504 Oct 26 13:56 ./technical/biomed/1471-2334-2-6.txt
9947113       96 -rwxr-xr-x    1 heejin           staff               46555 Oct 26 13:56 ./technical/biomed/1471-213X-1-15.txt
9947725       32 -rwxr-xr-x    1 heejin           staff               16150 Oct 26 13:56 ./technical/biomed/cc350.txt
9947139       40 -rwxr-xr-x    1 heejin           staff               19888 Oct 26 13:56 ./technical/biomed/1471-2148-3-1.txt
9947692       48 -rwxr-xr-x    1 heejin           staff               22429 Oct 26 13:56 ./technical/biomed/bcr588.txt
9947256       48 -rwxr-xr-x    1 heejin           staff               23248 Oct 26 13:56 ./technical/biomed/1471-2199-2-2.txt
9947570       48 -rwxr-xr-x    1 heejin           staff               21894 Oct 26 13:56 ./technical/biomed/1475-2867-2-7.txt
9947022       64 -rwxr-xr-x    1 heejin           staff               31378 Oct 26 13:56 ./technical/biomed/1468-6708-3-4.txt
9947097      104 -rwxr-xr-x    1 heejin           staff               51597 Oct 26 13:56 ./technical/biomed/1471-2121-3-25.txt
9947375       40 -rwxr-xr-x    1 heejin           staff               17234 Oct 26 13:56 ./technical/biomed/1471-2334-3-12.txt
9947308       56 -rwxr-xr-x    1 heejin           staff               27415 Oct 26 13:56 ./technical/biomed/1471-2202-4-6.txt
9947530      160 -rwxr-xr-x    1 heejin           staff               78507 Oct 26 13:56 ./technical/biomed/1472-6882-1-10.txt
9947093       96 -rwxr-xr-x    1 heejin           staff               46803 Oct 26 13:56 ./technical/biomed/1471-2121-3-19.txt
9947209       64 -rwxr-xr-x    1 heejin           staff               32085 Oct 26 13:56 ./technical/biomed/1471-2164-4-6.txt
9947329       72 -rwxr-xr-x    1 heejin           staff               34915 Oct 26 13:56 ./technical/biomed/1471-2229-2-9.txt
9947817       64 -rwxr-xr-x    1 heejin           staff               29598 Oct 26 13:56 ./technical/biomed/gb-2002-3-9-research0049.txt
9947361       48 -rwxr-xr-x    1 heejin           staff               24239 Oct 26 13:56 ./technical/biomed/1471-2334-1-17.txt
9947234       72 -rwxr-xr-x    1 heejin           staff               32867 Oct 26 13:56 ./technical/biomed/1471-2180-2-1.txt
9947729       24 -rwxr-xr-x    1 heejin           staff               11287 Oct 26 13:56 ./technical/biomed/cc973.txt
9947313      104 -rwxr-xr-x    1 heejin           staff               53072 Oct 26 13:56 ./technical/biomed/1471-2210-1-7.txt
9947358       48 -rwxr-xr-x    1 heejin           staff               24415 Oct 26 13:56 ./technical/biomed/1471-2326-2-4.txt
9947236       72 -rwxr-xr-x    1 heejin           staff               35235 Oct 26 13:56 ./technical/biomed/1471-2180-2-16.txt
9947102       40 -rwxr-xr-x    1 heejin           staff               17621 Oct 26 13:56 ./technical/biomed/1471-2121-4-1.txt
9947121       32 -rwxr-xr-x    1 heejin           staff               13689 Oct 26 13:56 ./technical/biomed/1471-213X-2-8.txt
9947490       56 -rwxr-xr-x    1 heejin           staff               25055 Oct 26 13:56 ./technical/biomed/1472-6793-1-12.txt
9947267       64 -rwxr-xr-x    1 heejin           staff               30658 Oct 26 13:56 ./technical/biomed/1471-2199-4-4.txt
9947268       56 -rwxr-xr-x    1 heejin           staff               25184 Oct 26 13:56 ./technical/biomed/1471-2199-4-5.txt
9947391       56 -rwxr-xr-x    1 heejin           staff               25926 Oct 26 13:56 ./technical/biomed/1471-2369-3-1.txt
9947163       80 -rwxr-xr-x    1 heejin           staff               39804 Oct 26 13:56 ./technical/biomed/1471-2164-2-1.txt
9947270       80 -rwxr-xr-x    1 heejin           staff               38924 Oct 26 13:56 ./technical/biomed/1471-2202-2-1.txt
9947816       96 -rwxr-xr-x    1 heejin           staff               45928 Oct 26 13:56 ./technical/biomed/gb-2002-3-9-research0048.txt
9947328       48 -rwxr-xr-x    1 heejin           staff               23226 Oct 26 13:56 ./technical/biomed/1471-2229-2-8.txt
9947463       56 -rwxr-xr-x    1 heejin           staff               25832 Oct 26 13:56 ./technical/biomed/1471-2474-4-8.txt
9947092       72 -rwxr-xr-x    1 heejin           staff               35704 Oct 26 13:56 ./technical/biomed/1471-2121-3-18.txt
9947531       64 -rwxr-xr-x    1 heejin           staff               31620 Oct 26 13:56 ./technical/biomed/1472-6882-1-11.txt
9947376       16 -rwxr-xr-x    1 heejin           staff                6297 Oct 26 13:56 ./technical/biomed/1471-2334-3-13.txt
9947731       48 -rwxr-xr-x    1 heejin           staff               21676 Oct 26 13:56 ./technical/biomed/cvm-2-1-038.txt
9947098      112 -rwxr-xr-x    1 heejin           staff               56063 Oct 26 13:56 ./technical/biomed/1471-2121-3-30.txt
9947159       72 -rwxr-xr-x    1 heejin           staff               33991 Oct 26 13:56 ./technical/biomed/1471-2156-4-10.txt
9947257       40 -rwxr-xr-x    1 heejin           staff               20447 Oct 26 13:56 ./technical/biomed/1471-2199-2-3.txt
9947604       48 -rwxr-xr-x    1 heejin           staff               21898 Oct 26 13:56 ./technical/biomed/1476-4598-1-3.txt
9947211       80 -rwxr-xr-x    1 heejin           staff               38772 Oct 26 13:56 ./technical/biomed/1471-2172-2-10.txt
9947085       64 -rwxr-xr-x    1 heejin           staff               31043 Oct 26 13:56 ./technical/biomed/1471-2121-2-6.txt
9947629       48 -rwxr-xr-x    1 heejin           staff               23010 Oct 26 13:56 ./technical/biomed/1477-7827-1-21.txt
9947630       72 -rwxr-xr-x    1 heejin           staff               35797 Oct 26 13:56 ./technical/biomed/1477-7827-1-23.txt
9947581       56 -rwxr-xr-x    1 heejin           staff               25430 Oct 26 13:56 ./technical/biomed/1475-2891-1-2.txt
9947023       40 -rwxr-xr-x    1 heejin           staff               18114 Oct 26 13:56 ./technical/biomed/1468-6708-3-7.txt
9947253       64 -rwxr-xr-x    1 heejin           staff               32069 Oct 26 13:56 ./technical/biomed/1471-2199-2-1.txt
9947046       72 -rwxr-xr-x    1 heejin           staff               36588 Oct 26 13:56 ./technical/biomed/1471-2105-1-1.txt
9947767      112 -rwxr-xr-x    1 heejin           staff               55347 Oct 26 13:56 ./technical/biomed/gb-2002-3-10-research0052.txt
9947307       56 -rwxr-xr-x    1 heejin           staff               26021 Oct 26 13:56 ./technical/biomed/1471-2202-4-5.txt
9947374       48 -rwxr-xr-x    1 heejin           staff               24252 Oct 26 13:56 ./technical/biomed/1471-2334-3-11.txt
9947208       56 -rwxr-xr-x    1 heejin           staff               24850 Oct 26 13:56 ./technical/biomed/1471-2164-4-5.txt
9947734       56 -rwxr-xr-x    1 heejin           staff               25831 Oct 26 13:56 ./technical/biomed/cvm-2-6-278.txt
9947732       40 -rwxr-xr-x    1 heejin           staff               19679 Oct 26 13:56 ./technical/biomed/cvm-2-4-180.txt
9947061       96 -rwxr-xr-x    1 heejin           staff               47668 Oct 26 13:56 ./technical/biomed/1471-2105-3-3.txt
9947827      112 -rwxr-xr-x    1 heejin           staff               55181 Oct 26 13:56 ./technical/biomed/gb-2003-4-2-r9.txt
9947580       56 -rwxr-xr-x    1 heejin           staff               24661 Oct 26 13:56 ./technical/biomed/1475-2883-2-11.txt
9947568       48 -rwxr-xr-x    1 heejin           staff               22387 Oct 26 13:56 ./technical/biomed/1475-2867-2-10.txt
9947281       64 -rwxr-xr-x    1 heejin           staff               30961 Oct 26 13:56 ./technical/biomed/1471-2202-2-3.txt
9947693       40 -rwxr-xr-x    1 heejin           staff               19094 Oct 26 13:56 ./technical/biomed/bcr602.txt
9947237       48 -rwxr-xr-x    1 heejin           staff               20538 Oct 26 13:56 ./technical/biomed/1471-2180-2-2.txt
9947745       96 -rwxr-xr-x    1 heejin           staff               48870 Oct 26 13:56 ./technical/biomed/gb-2001-2-12-research0055.txt
9947642       72 -rwxr-xr-x    1 heejin           staff               35659 Oct 26 13:56 ./technical/biomed/1478-1336-1-4.txt
9947502       64 -rwxr-xr-x    1 heejin           staff               31160 Oct 26 13:56 ./technical/biomed/1472-6793-2-4.txt
9947312       72 -rwxr-xr-x    1 heejin           staff               33669 Oct 26 13:56 ./technical/biomed/1471-2210-1-4.txt
9947042      104 -rwxr-xr-x    1 heejin           staff               52697 Oct 26 13:56 ./technical/biomed/1471-2091-3-4.txt
9947103       72 -rwxr-xr-x    1 heejin           staff               34571 Oct 26 13:56 ./technical/biomed/1471-2121-4-2.txt
9947796       72 -rwxr-xr-x    1 heejin           staff               34914 Oct 26 13:56 ./technical/biomed/gb-2002-3-4-research0019.txt
9947288       48 -rwxr-xr-x    1 heejin           staff               23827 Oct 26 13:56 ./technical/biomed/1471-2202-3-10.txt
9947241       32 -rwxr-xr-x    1 heejin           staff               13909 Oct 26 13:56 ./technical/biomed/1471-2180-2-29.txt
9947476       48 -rwxr-xr-x    1 heejin           staff               22140 Oct 26 13:56 ./technical/biomed/1472-6750-2-2.txt
9947618       48 -rwxr-xr-x    1 heejin           staff               23183 Oct 26 13:56 ./technical/biomed/1476-511X-2-3.txt
9947710       32 -rwxr-xr-x    1 heejin           staff               15211 Oct 26 13:56 ./technical/biomed/cc1547.txt
9947489       64 -rwxr-xr-x    1 heejin           staff               28809 Oct 26 13:56 ./technical/biomed/1472-6793-1-11.txt
9947418       32 -rwxr-xr-x    1 heejin           staff               14795 Oct 26 13:56 ./technical/biomed/1471-2407-2-9.txt
9947417       40 -rwxr-xr-x    1 heejin           staff               18174 Oct 26 13:56 ./technical/biomed/1471-2407-2-8.txt
9947614       72 -rwxr-xr-x    1 heejin           staff               35675 Oct 26 13:56 ./technical/biomed/1476-4598-2-28.txt
9947617       56 -rwxr-xr-x    1 heejin           staff               28467 Oct 26 13:56 ./technical/biomed/1476-511X-2-2.txt
9947289       64 -rwxr-xr-x    1 heejin           staff               31287 Oct 26 13:56 ./technical/biomed/1471-2202-3-11.txt
9947104       80 -rwxr-xr-x    1 heejin           staff               37156 Oct 26 13:56 ./technical/biomed/1471-2121-4-3.txt
9947795       64 -rwxr-xr-x    1 heejin           staff               29148 Oct 26 13:56 ./technical/biomed/gb-2002-3-4-research0018.txt
9947335       56 -rwxr-xr-x    1 heejin           staff               25902 Oct 26 13:56 ./technical/biomed/1471-2261-2-11.txt
9947503       72 -rwxr-xr-x    1 heejin           staff               33228 Oct 26 13:56 ./technical/biomed/1472-6793-2-5.txt
9947164       80 -rwxr-xr-x    1 heejin           staff               37800 Oct 26 13:56 ./technical/biomed/1471-2164-2-2.txt
9947744       80 -rwxr-xr-x    1 heejin           staff               40003 Oct 26 13:56 ./technical/biomed/gb-2001-2-12-research0054.txt
9947644       80 -rwxr-xr-x    1 heejin           staff               37212 Oct 26 13:56 ./technical/biomed/ar104.txt
9947402       80 -rwxr-xr-x    1 heejin           staff               37667 Oct 26 13:56 ./technical/biomed/1471-2407-1-15.txt
9947279       40 -rwxr-xr-x    1 heejin           staff               18827 Oct 26 13:56 ./technical/biomed/1471-2202-2-2.txt
9947826       88 -rwxr-xr-x    1 heejin           staff               43710 Oct 26 13:56 ./technical/biomed/gb-2003-4-2-r8.txt
9947549       40 -rwxr-xr-x    1 heejin           staff               16536 Oct 26 13:56 ./technical/biomed/1472-6947-1-2.txt
9947055      272 -rwxr-xr-x    1 heejin           staff              136424 Oct 26 13:56 ./technical/biomed/1471-2105-3-2.txt
9947325       80 -rwxr-xr-x    1 heejin           staff               37128 Oct 26 13:56 ./technical/biomed/1471-2229-2-11.txt
9947207      112 -rwxr-xr-x    1 heejin           staff               54077 Oct 26 13:56 ./technical/biomed/1471-2164-4-4.txt
9947735       40 -rwxr-xr-x    1 heejin           staff               19340 Oct 26 13:56 ./technical/biomed/cvm-2-6-286.txt
9947126       48 -rwxr-xr-x    1 heejin           staff               23842 Oct 26 13:56 ./technical/biomed/1471-2148-1-1.txt
9947373       64 -rwxr-xr-x    1 heejin           staff               30506 Oct 26 13:56 ./technical/biomed/1471-2334-3-10.txt
9947532       64 -rwxr-xr-x    1 heejin           staff               31937 Oct 26 13:56 ./technical/biomed/1472-6882-1-12.txt
9947768       64 -rwxr-xr-x    1 heejin           staff               31808 Oct 26 13:56 ./technical/biomed/gb-2002-3-10-research0053.txt
9947151       24 -rwxr-xr-x    1 heejin           staff               10530 Oct 26 13:56 ./technical/biomed/1471-2156-2-8.txt
9947853       80 -rwxr-xr-x    1 heejin           staff               37082 Oct 26 13:56 ./technical/biomed/rr196.txt
9947141       88 -rwxr-xr-x    1 heejin           staff               45044 Oct 26 13:56 ./technical/biomed/1471-2148-3-3.txt
9947515       40 -rwxr-xr-x    1 heejin           staff               19498 Oct 26 13:56 ./technical/biomed/1472-6807-2-9.txt
9947633      112 -rwxr-xr-x    1 heejin           staff               53800 Oct 26 13:56 ./technical/biomed/1477-7827-1-36.txt
9947143       80 -rwxr-xr-x    1 heejin           staff               40153 Oct 26 13:56 ./technical/biomed/1471-2148-3-7.txt
9947112       72 -rwxr-xr-x    1 heejin           staff               36535 Oct 26 13:56 ./technical/biomed/1471-213X-1-13.txt
9947076       56 -rwxr-xr-x    1 heejin           staff               26820 Oct 26 13:56 ./technical/biomed/1471-2121-2-1.txt
9947794       64 -rwxr-xr-x    1 heejin           staff               31929 Oct 26 13:56 ./technical/biomed/gb-2002-3-3-research0012.txt
9947156       32 -rwxr-xr-x    1 heejin           staff               13363 Oct 26 13:56 ./technical/biomed/1471-2156-3-22.txt
9947690       48 -rwxr-xr-x    1 heejin           staff               21426 Oct 26 13:56 ./technical/biomed/bcr571.txt
9947258      112 -rwxr-xr-x    1 heejin           staff               54313 Oct 26 13:56 ./technical/biomed/1471-2199-2-4.txt
9947737       56 -rwxr-xr-x    1 heejin           staff               28019 Oct 26 13:56 ./technical/biomed/gb-2000-1-2-research0003.txt
9947556       48 -rwxr-xr-x    1 heejin           staff               22981 Oct 26 13:56 ./technical/biomed/1472-6955-2-1.txt
9947067       72 -rwxr-xr-x    1 heejin           staff               34496 Oct 26 13:56 ./technical/biomed/1471-2105-3-6.txt
9947460       56 -rwxr-xr-x    1 heejin           staff               24615 Oct 26 13:56 ./technical/biomed/1471-2474-3-23.txt
9947551       72 -rwxr-xr-x    1 heejin           staff               33487 Oct 26 13:56 ./technical/biomed/1472-6947-1-6.txt
9947419       56 -rwxr-xr-x    1 heejin           staff               26367 Oct 26 13:56 ./technical/biomed/1471-2407-3-14.txt
9947283       48 -rwxr-xr-x    1 heejin           staff               23922 Oct 26 13:56 ./technical/biomed/1471-2202-2-6.txt
9947569       56 -rwxr-xr-x    1 heejin           staff               25953 Oct 26 13:56 ./technical/biomed/1475-2867-2-15.txt
9947495       64 -rwxr-xr-x    1 heejin           staff               30811 Oct 26 13:56 ./technical/biomed/1472-6793-2-1.txt
9947810       48 -rwxr-xr-x    1 heejin           staff               20507 Oct 26 13:56 ./technical/biomed/gb-2002-3-8-research0039.txt
9947393       40 -rwxr-xr-x    1 heejin           staff               18646 Oct 26 13:56 ./technical/biomed/1471-2369-3-6.txt
9947695       48 -rwxr-xr-x    1 heejin           staff               20662 Oct 26 13:56 ./technical/biomed/bcr607.txt
9947528       40 -rwxr-xr-x    1 heejin           staff               18987 Oct 26 13:56 ./technical/biomed/1472-6874-2-8.txt
9947245       48 -rwxr-xr-x    1 heejin           staff               24381 Oct 26 13:56 ./technical/biomed/1471-2180-2-7.txt
9947166       48 -rwxr-xr-x    1 heejin           staff               20730 Oct 26 13:56 ./technical/biomed/1471-2164-2-6.txt
9947244       48 -rwxr-xr-x    1 heejin           staff               21154 Oct 26 13:56 ./technical/biomed/1471-2180-2-38.txt
9947322       32 -rwxr-xr-x    1 heejin           staff               16141 Oct 26 13:56 ./technical/biomed/1471-2210-3-3.txt
9947431       48 -rwxr-xr-x    1 heejin           staff               21527 Oct 26 13:56 ./technical/biomed/1471-2431-2-11.txt
9947491       72 -rwxr-xr-x    1 heejin           staff               33137 Oct 26 13:56 ./technical/biomed/1472-6793-1-15.txt
9947452       48 -rwxr-xr-x    1 heejin           staff               22386 Oct 26 13:56 ./technical/biomed/1471-2458-3-9.txt
9947107       56 -rwxr-xr-x    1 heejin           staff               26467 Oct 26 13:56 ./technical/biomed/1471-2121-4-6.txt
9947290       72 -rwxr-xr-x    1 heejin           staff               33896 Oct 26 13:56 ./technical/biomed/1471-2202-3-14.txt
9947167       64 -rwxr-xr-x    1 heejin           staff               32543 Oct 26 13:56 ./technical/biomed/1471-2164-2-7.txt
9947742       80 -rwxr-xr-x    1 heejin           staff               37186 Oct 26 13:56 ./technical/biomed/gb-2001-2-12-research0051.txt
9947809       96 -rwxr-xr-x    1 heejin           staff               45876 Oct 26 13:56 ./technical/biomed/gb-2002-3-8-research0038.txt
9947439       48 -rwxr-xr-x    1 heejin           staff               20900 Oct 26 13:56 ./technical/biomed/1471-244X-3-5.txt
9947284       56 -rwxr-xr-x    1 heejin           staff               27117 Oct 26 13:56 ./technical/biomed/1471-2202-2-7.txt
9947359       40 -rwxr-xr-x    1 heejin           staff               16775 Oct 26 13:56 ./technical/biomed/1471-2334-1-10.txt
9947420       56 -rwxr-xr-x    1 heejin           staff               25312 Oct 26 13:56 ./technical/biomed/1471-2407-3-15.txt
9947096       72 -rwxr-xr-x    1 heejin           staff               33441 Oct 26 13:56 ./technical/biomed/1471-2121-3-22.txt
9947377       72 -rwxr-xr-x    1 heejin           staff               35377 Oct 26 13:56 ./technical/biomed/1471-2334-3-15.txt
9947128       64 -rwxr-xr-x    1 heejin           staff               29837 Oct 26 13:56 ./technical/biomed/1471-2148-1-4.txt
9947259       72 -rwxr-xr-x    1 heejin           staff               34740 Oct 26 13:56 ./technical/biomed/1471-2199-2-5.txt
9947021       40 -rwxr-xr-x    1 heejin           staff               16882 Oct 26 13:56 ./technical/biomed/1468-6708-3-3.txt
9947689       40 -rwxr-xr-x    1 heejin           staff               20468 Oct 26 13:56 ./technical/biomed/bcr570.txt
9947771       96 -rwxr-xr-x    1 heejin           staff               45288 Oct 26 13:56 ./technical/biomed/gb-2002-3-10-research0056.txt
9947554       64 -rwxr-xr-x    1 heejin           staff               30395 Oct 26 13:56 ./technical/biomed/1472-6947-3-5.txt
9947724       48 -rwxr-xr-x    1 heejin           staff               23825 Oct 26 13:56 ./technical/biomed/cc343.txt
9947111       64 -rwxr-xr-x    1 heejin           staff               29734 Oct 26 13:56 ./technical/biomed/1471-213X-1-12.txt
9947347       56 -rwxr-xr-x    1 heejin           staff               28483 Oct 26 13:56 ./technical/biomed/1471-2296-3-3.txt
9947631       56 -rwxr-xr-x    1 heejin           staff               25530 Oct 26 13:56 ./technical/biomed/1477-7827-1-27.txt
9947605       32 -rwxr-xr-x    1 heejin           staff               15245 Oct 26 13:56 ./technical/biomed/1476-4598-1-5.txt
9947852       64 -rwxr-xr-x    1 heejin           staff               30791 Oct 26 13:56 ./technical/biomed/rr191.txt
9947142       72 -rwxr-xr-x    1 heejin           staff               33162 Oct 26 13:56 ./technical/biomed/1471-2148-3-4.txt
9947448       72 -rwxr-xr-x    1 heejin           staff               35574 Oct 26 13:56 ./technical/biomed/1471-2458-3-11.txt
9947576       64 -rwxr-xr-x    1 heejin           staff               31562 Oct 26 13:56 ./technical/biomed/1475-2875-1-5.txt
9947632       88 -rwxr-xr-x    1 heejin           staff               41600 Oct 26 13:56 ./technical/biomed/1477-7827-1-31.txt
9947109       56 -rwxr-xr-x    1 heejin           staff               26832 Oct 26 13:56 ./technical/biomed/1471-213X-1-10.txt
9947793       96 -rwxr-xr-x    1 heejin           staff               46710 Oct 26 13:56 ./technical/biomed/gb-2002-3-3-research0011.txt
9947769       72 -rwxr-xr-x    1 heejin           staff               32878 Oct 26 13:56 ./technical/biomed/gb-2002-3-10-research0054.txt
9947019       48 -rwxr-xr-x    1 heejin           staff               24112 Oct 26 13:56 ./technical/biomed/1468-6708-3-1.txt
9947129       32 -rwxr-xr-x    1 heejin           staff               12833 Oct 26 13:56 ./technical/biomed/1471-2148-1-6.txt
9947306       72 -rwxr-xr-x    1 heejin           staff               32938 Oct 26 13:56 ./technical/biomed/1471-2202-4-3.txt
9947550       40 -rwxr-xr-x    1 heejin           staff               18158 Oct 26 13:56 ./technical/biomed/1472-6947-1-5.txt
9947282       72 -rwxr-xr-x    1 heejin           staff               32780 Oct 26 13:56 ./technical/biomed/1471-2202-2-5.txt
9947620       80 -rwxr-xr-x    1 heejin           staff               37006 Oct 26 13:56 ./technical/biomed/1476-9433-1-2.txt
9947310       32 -rwxr-xr-x    1 heejin           staff               14603 Oct 26 13:56 ./technical/biomed/1471-2210-1-2.txt
9947440       64 -rwxr-xr-x    1 heejin           staff               32387 Oct 26 13:56 ./technical/biomed/1471-2458-1-9.txt
9947501       72 -rwxr-xr-x    1 heejin           staff               35125 Oct 26 13:56 ./technical/biomed/1472-6793-2-2.txt
9947743       56 -rwxr-xr-x    1 heejin           staff               25094 Oct 26 13:56 ./technical/biomed/gb-2001-2-12-research0053.txt
9947640       48 -rwxr-xr-x    1 heejin           staff               22678 Oct 26 13:56 ./technical/biomed/1478-1336-1-2.txt
9947291       88 -rwxr-xr-x    1 heejin           staff               42803 Oct 26 13:56 ./technical/biomed/1471-2202-3-16.txt
9947235       56 -rwxr-xr-x    1 heejin           staff               28049 Oct 26 13:56 ./technical/biomed/1471-2180-2-13.txt
9947105       56 -rwxr-xr-x    1 heejin           staff               25444 Oct 26 13:56 ./technical/biomed/1471-2121-4-4.txt
9947833       64 -rwxr-xr-x    1 heejin           staff               28895 Oct 26 13:56 ./technical/biomed/gb-2003-4-4-r28.txt
9947352       24 -rwxr-xr-x    1 heejin           staff               11200 Oct 26 13:56 ./technical/biomed/1471-230X-2-17.txt
9947622       48 -rwxr-xr-x    1 heejin           staff               21459 Oct 26 13:56 ./technical/biomed/1477-5956-1-1.txt
9947162       88 -rwxr-xr-x    1 heejin           staff               43248 Oct 26 13:56 ./technical/biomed/1471-2156-4-9.txt
9947432       56 -rwxr-xr-x    1 heejin           staff               26239 Oct 26 13:56 ./technical/biomed/1471-2431-2-12.txt
9947654       32 -rwxr-xr-x    1 heejin           staff               15903 Oct 26 13:56 ./technical/biomed/ar328.txt
9947321       56 -rwxr-xr-x    1 heejin           staff               28562 Oct 26 13:56 ./technical/biomed/1471-2210-3-1.txt
9947106       56 -rwxr-xr-x    1 heejin           staff               27586 Oct 26 13:56 ./technical/biomed/1471-2121-4-5.txt
9947382       24 -rwxr-xr-x    1 heejin           staff               11237 Oct 26 13:56 ./technical/biomed/1471-2350-2-8.txt
9947292       64 -rwxr-xr-x    1 heejin           staff               29638 Oct 26 13:56 ./technical/biomed/1471-2202-3-17.txt
9947401       48 -rwxr-xr-x    1 heejin           staff               23484 Oct 26 13:56 ./technical/biomed/1471-2407-1-13.txt
9947694       96 -rwxr-xr-x    1 heejin           staff               46272 Oct 26 13:56 ./technical/biomed/bcr605.txt
9947599      152 -rwxr-xr-x    1 heejin           staff               74965 Oct 26 13:56 ./technical/biomed/1476-069X-2-9.txt
9947641       48 -rwxr-xr-x    1 heejin           staff               23526 Oct 26 13:56 ./technical/biomed/1478-1336-1-3.txt
9947165       56 -rwxr-xr-x    1 heejin           staff               27684 Oct 26 13:56 ./technical/biomed/1471-2164-2-4.txt
9947311       56 -rwxr-xr-x    1 heejin           staff               28252 Oct 26 13:56 ./technical/biomed/1471-2210-1-3.txt
9947621       48 -rwxr-xr-x    1 heejin           staff               21318 Oct 26 13:56 ./technical/biomed/1476-9433-1-3.txt
9947360       48 -rwxr-xr-x    1 heejin           staff               21797 Oct 26 13:56 ./technical/biomed/1471-2334-1-13.txt
9947421       48 -rwxr-xr-x    1 heejin           staff               22447 Oct 26 13:56 ./technical/biomed/1471-2407-3-16.txt
9947199       56 -rwxr-xr-x    1 heejin           staff               28119 Oct 26 13:56 ./technical/biomed/1471-2164-4-2.txt
9947733       56 -rwxr-xr-x    1 heejin           staff               25609 Oct 26 13:56 ./technical/biomed/cvm-2-4-187.txt
9947066       72 -rwxr-xr-x    1 heejin           staff               34817 Oct 26 13:56 ./technical/biomed/1471-2105-3-4.txt
9947095       64 -rwxr-xr-x    1 heejin           staff               32262 Oct 26 13:56 ./technical/biomed/1471-2121-3-21.txt
9947305       72 -rwxr-xr-x    1 heejin           staff               33888 Oct 26 13:56 ./technical/biomed/1471-2202-4-2.txt
9947221       48 -rwxr-xr-x    1 heejin           staff               21927 Oct 26 13:56 ./technical/biomed/1471-2172-3-9.txt
9947747       48 -rwxr-xr-x    1 heejin           staff               23524 Oct 26 13:56 ./technical/biomed/gb-2001-2-3-research0007.txt
9947260       56 -rwxr-xr-x    1 heejin           staff               26704 Oct 26 13:56 ./technical/biomed/1471-2199-2-6.txt
9947687       32 -rwxr-xr-x    1 heejin           staff               16229 Oct 26 13:56 ./technical/biomed/bcr567.txt
9947770       96 -rwxr-xr-x    1 heejin           staff               47650 Oct 26 13:56 ./technical/biomed/gb-2002-3-10-research0055.txt
9947084       32 -rwxr-xr-x    1 heejin           staff               14165 Oct 26 13:56 ./technical/biomed/1471-2121-2-3.txt
9947110       64 -rwxr-xr-x    1 heejin           staff               29630 Oct 26 13:56 ./technical/biomed/1471-213X-1-11.txt
9947523      104 -rwxr-xr-x    1 heejin           staff               49884 Oct 26 13:56 ./technical/biomed/1472-684X-1-5.txt
9947606       72 -rwxr-xr-x    1 heejin           staff               33139 Oct 26 13:56 ./technical/biomed/1476-4598-1-6.txt
9947000        0 drwxr-xr-x   19 heejin           staff                 608 Oct 26 13:56 ./technical/911report
9947008      520 -rwxr-xr-x    1 heejin           staff              265912 Oct 26 13:56 ./technical/911report/chapter-13.4.txt
9947009      576 -rwxr-xr-x    1 heejin           staff              290993 Oct 26 13:56 ./technical/911report/chapter-13.5.txt
9947005      176 -rwxr-xr-x    1 heejin           staff               89854 Oct 26 13:56 ./technical/911report/chapter-13.1.txt
9947006      216 -rwxr-xr-x    1 heejin           staff              110568 Oct 26 13:56 ./technical/911report/chapter-13.2.txt
9947007      296 -rwxr-xr-x    1 heejin           staff              150467 Oct 26 13:56 ./technical/911report/chapter-13.3.txt
9947011      520 -rwxr-xr-x    1 heejin           staff              264360 Oct 26 13:56 ./technical/911report/chapter-3.txt
9947010      160 -rwxr-xr-x    1 heejin           staff               79803 Oct 26 13:56 ./technical/911report/chapter-2.txt
9947001      232 -rwxr-xr-x    1 heejin           staff              118656 Oct 26 13:56 ./technical/911report/chapter-1.txt
9947012      200 -rwxr-xr-x    1 heejin           staff               99008 Oct 26 13:56 ./technical/911report/chapter-5.txt
9947013      296 -rwxr-xr-x    1 heejin           staff              149063 Oct 26 13:56 ./technical/911report/chapter-6.txt
9947014      256 -rwxr-xr-x    1 heejin           staff              128370 Oct 26 13:56 ./technical/911report/chapter-7.txt
9947016      296 -rwxr-xr-x    1 heejin           staff              149644 Oct 26 13:56 ./technical/911report/chapter-9.txt
9947015      168 -rwxr-xr-x    1 heejin           staff               84835 Oct 26 13:56 ./technical/911report/chapter-8.txt
9947017       24 -rwxr-xr-x    1 heejin           staff                9332 Oct 26 13:56 ./technical/911report/preface.txt
9947004      256 -rwxr-xr-x    1 heejin           staff              127587 Oct 26 13:56 ./technical/911report/chapter-12.txt
9947002       96 -rwxr-xr-x    1 heejin           staff               47307 Oct 26 13:56 ./technical/911report/chapter-10.txt
9947003      144 -rwxr-xr-x    1 heejin           staff               71151 Oct 26 13:56 ./technical/911report/chapter-11.txt
```
So it seems that the find -ls command also shows the content in the file. The table contains the user name, byte size, Last Changed Date. We can use this command when we want to have a general pictura of some associated statistics of the files rather than only looking into the filenames.

Thrid, we want to see what find -type can do:
input:
```
heejin@Annabelles-MBP skill-demo1 % find ./technical -type d
```
output:
```
./technical
./technical/government
./technical/government/About_LSC
./technical/government/Env_Prot_Agen
./technical/government/Alcohol_Problems
./technical/government/Gen_Account_Office
./technical/government/Post_Rate_Comm
./technical/government/Media
./technical/plos
./technical/biomed
./technical/911report
```
Find -type can help us to find the various types the directory holds. For example, if we add -d in the end as what the input does, the output will show us all the directories and subdirectories in the technical directory. We can use it when we want to see what directories are contained in our files. And check if any directory is missing.

 > Less command 

First, I want to try less -N to see what will happen.
input:
```
less -N ./technical/911report/preface.txt
```
output:
```
      1 
      2     
      3         
      4             PREFACE
      5             We present the narrative of this report and the recommendations that flow from it to
      6                 the President of the United States, the United States Congress, and the American
      7                 people for their consideration. Ten Commissioners-five Republicans and five
      8                 Democrats chosen by elected leaders from our nation's capital at a time of great
      9                 partisan division-have come together to present this report without dissent.
     10             We have come together with a unity of purpose because our nation demands it.
     11                 September 11, 2001, was a day of unprecedented shock and suffering in the history of
     12                 the United States. The nation was unprepared. How did this happen, and how can we
     13                 avoid such tragedy again?
     14             To answer these questions, the Congress and the President created the National
     15                 Commission on Terrorist Attacks Upon the United States (Public Law 107-306, November
     16                 27, 2002).
     17             Our mandate was sweeping. The law directed us to investigate "facts and circumstances
     18                 relating to the terrorist attacks of September 11, 2001," including those relating
     19                 to intelligence agencies, law enforcement agencies, diplomacy, immigration issues
     20                 and border control, the flow of assets to terrorist organizations, commercial
     21                 aviation, the role of congressional oversight and resource allocation, and other
     22                 areas determined relevant by the Commission. In pursuing our mandate, we have
     23                 reviewed more than 2.5 million pages of documents and interviewed more than 1,200
     24                 individuals in ten countries. This included nearly every senior official from the
     25                 current and previous administrations who had responsibility for topics covered in
     26                 our mandate. We have sought to be independent, impartial, thorough, and nonpartisan.
     27                 From the outset, we have been committed to share as much of our investigation as we
     28                 can with the American people. To that end, we held 19 days of hearings and took
     29                 public testimony from 160 witnesses.
     30             Our aim has not been to assign individual blame. Our aim has been to provide the
     31                 fullest possible account of the events surrounding 9/11 and to identify lessons
     32                 learned.
     33             We learned about an enemy who is sophisticated, patient, disciplined, and lethal. The
     34                 enemy rallies broad support in the Arab and Muslim world by demanding redress of
					35                 political grievances, but its hostility toward us and our values is limitless. Its
     36                 purpose is to rid the world of religious and political pluralism, the plebiscite,
     37                 and equal rights for women. It makes no distinction between military and civilian
     38                 targets. Collateral damage is not in its lexicon.
     39             We learned that the institutions charged with protecting our borders, civil aviation,
     40                 and national security did not understand how grave this threat could be, and did not
     41                 adjust their policies, plans, and practices to deter or defeat it. We learned of
     42                 fault lines within our government-between foreign and domestic intelligence, and
     43                 between and within agencies. We learned of the pervasive problems of managing and
     44                 sharing information across a large and unwieldy government that had been built in a
     45                 different era to confront different dangers.
     46             At the outset of our work, we said we were looking backward in order to look forward.
     47                 We hope that the terrible losses chronicled in this report can create something
     48                 positive-an America that is safer, stronger, and wiser. That September day, we came
     49                 together as a nation. The test before us is to sustain that unity of purpose and
     50                 meet the challenges now confronting us. We need to design a balanced strategy for
     51                 the long haul, to attack terrorists and prevent their ranks from swelling while at
     52                 the same time protecting our country against future attacks. We have been forced to
     53                 think about the way our government is organized. The massive departments and
     54                 agencies that prevailed in the great struggles of the twentieth century must work
     55                 together in new ways, so that all the instruments of national power can be combined.
     56                 Congress needs dramatic change as well to strengthen oversight and focus
     57                 accountability.
     58             As we complete our final report, we want to begin by thanking our fellow
     59                 Commissioners, whose dedication to this task has been profound. We have reasoned
     60                 together over every page, and the report has benefited from this remarkable
     61                 dialogue. We want to express our considerable respect for the intellect and judgment
     62                 of our colleagues, as well as our great affection for them.
     63             We want to thank the Commission staff. The dedicated professional staff, headed by
     64                 Philip Zelikow, has contributed innumerable hours to the completion of this report,
     65                 setting aside other important endeavors to take on this all-consuming assignment.
     66                 They have conducted the exacting investigative work upon which the Commission has
     67                 built. They have given good advice, and faithfully carried out our guidance. They
     68                 have been superb. We thank the Congress and the President. Executive branch agencies
     69                 have searched records and produced a multitude of documents for us. We thank
     70                 officials, past and present, who were generous with their time and provided us with
     71                 insight. The PENTTBOM team at the FBI, the Director's Review Group at the CIA, and
     72                 Inspectors General at the Department of Justice and the CIA provided great
     73                 assistance. We owe a huge debt to their investigative labors, painstaking attention
     74                 to detail, and readiness to share what they have learned. We have built on the work
     75                 of several previous Commissions, and we thank the Congressional Joint Inquiry, whose
     76                 fine work helped us get started. We thank the City of New York for assistance with
     77                 documents and witnesses, and the Government Printing Office and W.W. Norton
     78                 & Company for helping to get this report to the broad public.
     79             We conclude this list of thanks by coming full circle: We thank the families of 9/11,
     80                 whose persistence and dedication helped create the Commission. They have been with
     81                 us each step of the way, as partners and witnesses. They know better than any of us
     82                 the importance of the work we have undertaken.
     83             We want to note what we have done, and not done. We have endeavored to provide the
     84                 most complete account we can of the events of September 11, what happened and why.
     85                 This final report is only a summary of what we have done, citing only a fraction of
     86                 the sources we have consulted. But in an event of this scale, touching so many
     87                 issues and organizations, we are conscious of our limits. We have not interviewed
     88                 every knowledgeable person or found every relevant piece of paper. New information
     89                 inevitably will come to light. We present this report as a foundation for a better
     90                 understanding of a landmark in the history of our nation.
     91             We have listened to scores of overwhelming personal tragedies and astounding acts of
     92                 heroism and bravery. We have examined the staggering impact of the events of 9/11 on
     93                 the American people and their amazing resilience and courage as they fought back. We
     94                 have admired their determination to do their best to prevent another tragedy while
     95                 preparing to respond if it becomes necessary. We emerge from this investigation with
					96                 enormous sympathy for the victims and their loved ones, and with enhanced respect
     97                 for the American people. We recognize the formidable challenges that lie ahead.
     98             We also approach the task of recommendations with humility. We have made a limited
     99                 number of them. We decided consciously to focus on recommendations we believe to be
    100                 most important, whose implementation can make the greatest difference. We came into
    101                 this process with strong opinions about what would work. All of us have had to
    102                 pause, reflect, and sometimes change our minds as we studied these problems and
    103                 considered the views of others. We hope our report will encourage our fellow
    104                 citizens to study, reflect-and act.
    105             Thomas H. Kean, chair
    106             Lee H. Hamilton, vice chair
    107         
    108     
				
```
We can see that the less -N method actually print the content of the file with line number beside each line so that the file is more clear. This is helpful when we want to have a glimpse of the file content and the length of the file.

Second, we want to explore around less +F input.
input:
```
less -X ./technical/911report/preface.txt
```
output:
```
 We hope that the terrible losses chronicled in this report can create something
                positive-an America that is safer, stronger, and wiser. That September day, we came
                together as a nation. The test before us is to sustain that unity of purpose and
                meet the challenges now confronting us. We need to design a balanced strategy for
                the long haul, to attack terrorists and prevent their ranks from swelling while at
                the same time protecting our country against future attacks. We have been forced to
                think about the way our government is organized. The massive departments and
                agencies that prevailed in the great struggles of the twentieth century must work
                together in new ways, so that all the instruments of national power can be combined.
                Congress needs dramatic change as well to strengthen oversight and focus
                accountability.
            As we complete our final report, we want to begin by thanking our fellow
                Commissioners, whose dedication to this task has been profound. We have reasoned
                together over every page, and the report has benefited from this remarkable
                dialogue. We want to express our considerable respect for the intellect and judgment
                of our colleagues, as well as our great affection for them.
            We want to thank the Commission staff. The dedicated professional staff, headed by
                Philip Zelikow, has contributed innumerable hours to the completion of this report,
                setting aside other important endeavors to take on this all-consuming assignment.
                They have conducted the exacting investigative work upon which the Commission has
                built. They have given good advice, and faithfully carried out our guidance. They
                have been superb. We thank the Congress and the President. Executive branch agencies
                have searched records and produced a multitude of documents for us. We thank
                officials, past and present, who were generous with their time and provided us with
                insight. The PENTTBOM team at the FBI, the Director's Review Group at the CIA, and
                Inspectors General at the Department of Justice and the CIA provided great
                assistance. We owe a huge debt to their investigative labors, painstaking attention
                to detail, and readiness to share what they have learned. We have built on the work
                of several previous Commissions, and we thank the Congressional Joint Inquiry, whose
                fine work helped us get started. We thank the City of New York for assistance with
                documents and witnesses, and the Government Printing Office and W.W. Norton
                & Company for helping to get this report to the broad public.
            We conclude this list of thanks by coming full circle: We thank the families of 9/11,
                whose persistence and dedication helped create the Commission. They have been with
                us each step of the way, as partners and witnesses. They know better than any of us
                the importance of the work we have undertaken.
            We want to note what we have done, and not done. We have endeavored to provide the
                most complete account we can of the events of September 11, what happened and why.
                This final report is only a summary of what we have done, citing only a fraction of
                the sources we have consulted. But in an event of this scale, touching so many
                issues and organizations, we are conscious of our limits. We have not interviewed
                every knowledgeable person or found every relevant piece of paper. New information
                inevitably will come to light. We present this report as a foundation for a better
                understanding of a landmark in the history of our nation.
            We have listened to scores of overwhelming personal tragedies and astounding acts of
                heroism and bravery. We have examined the staggering impact of the events of 9/11 on
                the American people and their amazing resilience and courage as they fought back. We
                have admired their determination to do their best to prevent another tragedy while
                preparing to respond if it becomes necessary. We emerge from this investigation with
                enormous sympathy for the victims and their loved ones, and with enhanced respect
                for the American people. We recognize the formidable challenges that lie ahead.
            We also approach the task of recommendations with humility. We have made a limited
                number of them. We decided consciously to focus on recommendations we believe to be
                most important, whose implementation can make the greatest difference. We came into
                this process with strong opinions about what would work. All of us have had to
                pause, reflect, and sometimes change our minds as we studied these problems and
                considered the views of others. We hope our report will encourage our fellow
                citizens to study, reflect-and act.
            Thomas H. Kean, chair
            Lee H. Hamilton, vice chair
        
    
Waiting for data... (interrupt to abort)
```
The less +F command will display the last page of the file and wait for more data for me to add into the file. We can use this command when we want to directly write after the file.

Third, I want to explore less -V.
input:
```
 less -V ./technical/911report/preface.txt
```
output:
```
less 581.2 (POSIX regular expressions)
Copyright (C) 1984-2021  Mark Nudelman

less comes with NO WARRANTY, to the extent permitted by law.
For information about the terms of redistribution,
see the file named README in the less distribution.
Home page: https://greenwoodsoftware.com/less
```
By myself, I have no clue what the output is about. So I type less --help in command line and look for V. The answer is less -V shows the version number of less. I guess this will be useful if we want to share the file to others and want to make sure every tool is in the same version.

> Grep command 


First, we try grep -i to see what is surprising.
input:
```
grep -i "understand" ./technical/911report/preface.txt
```
output:
```
and national security did not understand how grave this threat could be, and did not
                understanding of a landmark in the history of our nation.
```
See! This is so cool. grep -i actually searches for the word in the string and return the line with the string in it. It is more like a search method in the file. We can use it when we want to search for particular word or code in the file.

Second, we try grep -c

input:
```
 grep -c "understand"  ./technical/911report/preface.txt 
```
output:
```
2
```
Combined with the grep -i method we used above, we can tell that in preface.txt, the word "understand" appears 2 times. Now, with -c method, we can know times of a word appears in the file if we want to.

Third, we explore grep -o
input:
```
grep -o "understand"  ./technical/911report/preface.txt
```
output:
```
understand
understand
```
The grep -o only displays the matched string appeared in the preface.txt instead of the line that it is in. We can use grep -o to possibly check the times it is in the file and probably with other commands, we can check with case insensitive. 

That is the end of lab report 3 where we play around the grep, less, find in command line. Thank you for reading!
