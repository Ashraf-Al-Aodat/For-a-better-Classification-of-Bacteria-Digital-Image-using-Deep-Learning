
 <img src="assets/Scientists-Have-Discovered-A-Bacteria-Species-Thats-Feeds-Upon-Electricity-12-640x384.jpg" raw="true" alt="For a better Classification of Bacteria Digital Image using Deep Learning"/>

 
# Bacteria Digital Image Classification

Academic research in the field of **Deep Learning (CNN)**

## The Dataset:

This project made use of the Digital Image of Bacterial Species, found here: http://misztal.edu.pl/software/databases/dibas/ . There are 33 classes of bacteria with around 20 examples each. A copy of the dataset has been uploaded to google drive; can be found here https://drive.google.com/drive/folders/1BlLxXkBJyz3nJojqsFmztc-SngMdFF4J?usp=sharing 

<table>
  <tr>
    <th>#</th>
    <th>Species</th>
    <th>Count</th>
  </tr>

  <tr>
    <td>1</td>
    <td>Lactobacillus johnsonii</td>
    <td>20</td>
  </tr>

  <tr>
    <td>2</td>
    <td>Listeria monocytogenes</td>
    <td>22</td>
  </tr>

  <tr>
    <td>3</td>
    <td>Propionibacterium acnes</td>
    <td>23</td>
  </tr>

  <tr>
    <td>4</td>
    <td>Veionella</td>
    <td>22</td>
  </tr>

  <tr>
    <td>5</td>
    <td>Staphylococcus aureus</td>
    <td>20</td>
  </tr>

  <tr>
    <td>6</td>
    <td>Enterococcus faecium</td>
    <td>20</td>
  </tr>

  <tr>
    <td>7</td>
    <td>Lactobacillus gasseri</td>
    <td>20</td>
  </tr>

  <tr>
    <td>8</td>
    <td>Streptococcus agalactiae</td>
    <td>20</td>
  </tr>

  <tr>
    <td>9</td>
    <td>Actinomyces Israeli</td>
    <td>23</td>
  </tr>

  <tr>
    <td>10</td>
    <td>Fusobacterium</td>
    <td>23</td>
  </tr>

  <tr>
    <td>11</td>
    <td>Pseudomonas aeruginosa</td>
    <td>20</td>
  </tr>

  <tr>
    <td>12</td>
    <td>Lactobacillus plantarum</td>
    <td>20</td>
  </tr>

  <tr>
    <td>13</td>
    <td>Lactobacillus reuteri</td>
    <td>20</td>
  </tr>

  <tr>
    <td>14</td>
    <td>Clostridium perfringens</td>
    <td>23</td>
  </tr>

  <tr>
    <td>15</td>
    <td>Neisseria gonorrhoeae</td>
    <td>23</td>
  </tr>

  <tr>
    <td>16</td>
    <td>Proteus</td>
    <td>20</td>
  </tr>

  <tr>
    <td>17</td>
    <td>Acinetobacter baumanii</td>
    <td>20</td>
  </tr>

  <tr>
    <td>18</td>
    <td>Lactobacillus casei</td>
    <td>20</td>
  </tr>

  <tr>
    <td>19</td>
    <td>Bacteroides fragilis</td>
    <td>23</td>
  </tr>

  <tr>
    <td>20</td>
    <td>Porfyromonas gingivalis</td>
    <td>23</td>
  </tr>

  <tr>
    <td>21</td>
    <td>Escherichia coli</td>
    <td>20</td>
  </tr>

  <tr>
    <td>22</td>
    <td>Lactobacillus crispatus</td>
    <td>20</td>
  </tr>

  <tr>
    <td>23</td>
    <td>Bifidobacterium spp</td>
    <td>23</td>
  </tr>

  <tr>
    <td>24</td>
    <td>Staphylococcus epidermidis</td>
    <td>20</td>
  </tr>

  <tr>
    <td>25</td>
    <td>Staphylococcus saprophiticus</td>
    <td>20</td>
  </tr>

  <tr>
    <td>26</td>
    <td>Lactobacillus salivarius</td>
    <td>20</td>
  </tr>

  <tr>
    <td>27</td>
    <td>Lactobacillus delbrueckii</td>
    <td>20</td>
  </tr>

  <tr>
    <td>28</td>
    <td>Lactobacillus jehnsenii</td>
    <td>20</td>
  </tr>

  <tr>
    <td>29</td>
    <td>Candida albicans</td>
    <td>20</td>
  </tr>

  <tr>
    <td>30</td>
    <td>Lactobacillus rhamnosus</td>
    <td>20</td>
  </tr>

  <tr>
    <td>31</td>
    <td>Micrococcus spp</td>
    <td>21</td>
  </tr>

  <tr>
    <td>32</td>
    <td>Lactobacillus paracasei</td>
    <td>20</td>
  </tr>

  <tr>
    <td>33</td>
    <td>Enterococcus faecalis</td>
    <td>20</td>
  </tr>

  <tr>
    <td colspan="2" style="text-align:center"><b>Total</b></td>
    <td><b>689</b></td>
  </tr>
</table>
 
## The Model (Xception):
the Xception Architecture has been used to classify the species and genera of bacteria. A Stratified-5-Folds cross validation was used to validate the performance of the model, An average of **99.71%** accuracy has been achieved, competing and even beating published State-of-The-Art models. The Keras library was used with Tensorflow backend.

The accuracy of the folds..
|Fold|Validation accuracy (%)|
|:---:|:---:|
|Fold-1 |99.28%|
|Fold-2 |99.28%|
|Fold-3 |100%|
|Fold-4 |100%|
|Fold-5 |100%|
|**Average**|**99.71%**|

A. Alaodat, M.Aloudat: **For a better Classification of Bacteria Digital Image using Deep Learning**, "under revision"
