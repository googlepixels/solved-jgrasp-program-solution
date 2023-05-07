Download Link: https://assignmentchef.com/product/solved-jgrasp-program-solution
<br>
<ol start="11">

 <li>Here is starter code: <a href="https://www2.hawaii.edu/~walbritt/ics211/assignments/LastnameFirstname11.java">java</a></li>

 <li>Read over how interface Comparable works:

  <ol>

   <li><a href="https://www2.hawaii.edu/~walbritt/ics211/examples/Comparable.java">java</a>is interface Comparable with a detailed description of how it is implemented.</li>

   <li><a href="https://docs.oracle.com/javase/7/docs/api/java/lang/Comparable.html">Java API Interface Comparable</a>has even more details.</li>

  </ol></li>

 <li>Add <strong>interface java.lang.Comparable</strong>to the first line of your class HawaiiNativeBirds.</li>

 <li>For example:<strong>class </strong>HawaiiNativeBirds<strong> implements java.lang.Comparable{</strong></li>

 <li>Add the compareTo() method to class HawaiiNativeBirds to sort any data field that you wish. In other words, write a compareTo() method definition nested inside your class HawaiiNativeBirds that sorts one of the data fields of class HawaiiNativeBirds. Here are examples of compareTo() method definitions:

  <ol>

   <li><a href="https://www2.hawaii.edu/~walbritt/ics211/examples/Fraction.java">java</a>shows an example compareTo() method.</li>

   <li><a href="https://www2.hawaii.edu/~walbritt/ics211/examples/Name.java">java</a>shows an example compareTo() method.</li>

   <li><a href="https://www2.hawaii.edu/~walbritt/ics211/examples/ThreeNames.java">java</a>shows an example compareTo() method.</li>

  </ol></li>

 <li>To prevent the automatic output of the <a href="http://www2.hawaii.edu/~walbritt/ics211/examples/Sorting.java">java</a>program, use this code before you sort: <strong>Sorting.display = false;</strong></li>

 <li>Use the one of the methods from the <a href="https://www2.hawaii.edu/~walbritt/ics211/examples/Sorting.java">java</a>program to sort your array of HawaiianTheme objects. In other words, in your main() method, write a method call from one of the sorting methods from the <a href="https://www2.hawaii.edu/~walbritt/ics211/examples/Sorting.java">Sorting.java</a> program. For example:<strong>Sorting.selectionSort(arrayOfHawaiianThemeObjects);</strong>Here are examples of sorting method calls:

  <ol>

   <li><a href="https://www2.hawaii.edu/~walbritt/ics211/examples/TestComparable.java">java</a>shows examples of using interface Comparable by comparing two objects of several different classes.</li>

   <li><a href="https://www2.hawaii.edu/~walbritt/ics211/examples/Sorting.java">java</a>shows examples of using interface Comparable for sorting arrays with different sorting algorithms.</li>

  </ol></li>

</ol>

Make sure to have comments and Javacoding in every method.




Sample output: with a different theme.

Display MarineMammalsOfHawaii array[] without initializing elements:

index   element

0     null

1     null

2     null

3     null

4     null

5     null

6     null

7     null

8     null

9     null

10     null

11     null

12     null

13     null

14     null

15     null

16     null

17     null




Read from input file: mammals2.csv




Display MarineMammalsOfHawaii array[] after initializing elements:

index   name                        population   length (meters) Genus species

0     Hawaiian monk seal               1100      2.40          Monachus schauinslandi

1     humpback whale                  10000     16.00          Megaptera novaeangliae

2     spinner dolphin                  3351      2.35          Stenella longirostris

3     common bottlenose dolphin         235      3.50          Tursiops truncatus

4     Risso’s dolphin                 85000      4.00          Grampus griseus

5     rough-toothed dolphin          150000      2.83          Steno bredanensis

6     striped dolphin               2000000      2.60          Stenella coeruleoalba

7     pygmy killer whale                817     20.50          Feresa attenuata

8     false killer whale                150      2.80          Pseudorca crassidens

9     melon-headed whale               2950      3.00          Peponocephala electra

10     short-finned pilot whale         8850      3.70          Globicephala macrorhynchus

11     sperm whale                      7082     17.30          Physeter macrocephalus

12     dwarf sperm whale               19000      3.00          Kogia sima

13     pygmy sperm whale                  50      3.50          Kogia breviceps

14     orca                               50     10.70          Orcinus orca

15     Blainville’s beaked whale        2200      5.00          Mesoplodon densirostris

16     Cuvier’s beaked Whale           13000      8.30          Ziphius cavirostris

17     pantropical spotted dolphin   3000000      2.50          Stenella attenuata




Display MarineMammalsOfHawaii array[] sorted by name:

index   name                        population   length (feet)   Genus species

0     Blainville’s beaked whale        2200      5.00          Mesoplodon densirostris

1     Cuvier’s beaked Whale           13000      8.30          Ziphius cavirostris

2     Hawaiian monk seal               1100      2.40          Monachus schauinslandi

3     Risso’s dolphin                 85000      4.00          Grampus griseus

4     common bottlenose dolphin         235      3.50          Tursiops truncatus

5     dwarf sperm whale               19000      3.00          Kogia sima

6     false killer whale                150      2.80          Pseudorca crassidens

7     humpback whale                  10000     16.00          Megaptera novaeangliae

8     melon-headed whale               2950      3.00          Peponocephala electra

9     orca                               50     10.70          Orcinus orca

10     pantropical spotted dolphin   3000000      2.50          Stenella attenuata

11     pygmy killer whale                817     20.50          Feresa attenuata

12     pygmy sperm whale                  50      3.50          Kogia breviceps

13     rough-toothed dolphin          150000      2.83          Steno bredanensis

14     short-finned pilot whale         8850      3.70          Globicephala macrorhynchus

15     sperm whale                      7082     17.30          Physeter macrocephalus

16     spinner dolphin                  3351      2.35          Stenella longirostris

17     striped dolphin               2000000      2.60          Stenella coeruleoalba





