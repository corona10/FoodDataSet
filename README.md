# Food DataSet
#### This datasets are provided by deep learning contest 2016 by [Nvidia Korea](http://kr.nvidia.com/).
#### And they answered that some of data are from [Food 101](https://www.vision.ee.ethz.ch/datasets_extra/food-101/).

# Download
#### Github is limited to upload all data set, so we decide to upload to external storage.
#### Byt we don't have enough server to provide this data. So we linked it to Google drive.
#### If anybody want to add download link, please contact to us.

| Download Link | MD5  |
| --------------|:----:|
|   [Google Drive hosted by Chungnam National University](https://drive.google.com/file/d/0B_lM0116PvbEOVR4MVBmdXMwX3M/view?usp=sharing)            | 6780d6b556699d9b6db102406de8ef7f     |

# Usage
* First, download all data.tar.gz and extract to where you want to work on it.
* Second, modify `BINARY_FILES_DIR` on config.py to where you extract.
* Finally, run tensorflow. You can use your own library or please refer our nvidia_input.py.

# Data description

### Train / Validation set

| Label   no (numpy uint8)   | Image binary (numpy uint8)  |
| ------------- |:---------------------------:| 
| 1byte         | 256x256x3 bytes             |

### Test set
| Image binary (numpy uint8)  |
|:---------------------------:|
|256x256x3 bytes              |

### Label
| Label no | Label name          |
|----------| :------------------:|
|     0    |  samgupsal          |
|     1    |   churros           |
|     2    |   bulgogi           |
|     3    | ojingeo_bokkeum     |
|     4    |    samosa           |
|     5    |  dakbokkeumtang     |
|     6    | spaghetti_bolognese |
|     7    |  galchijorim        |
|     8    |    sashimi          |
|     9    |  pork_chop          |
|    10    |   spring_rolls      |
|    11    |   panna_cotta       |
|    12    |   jeyuk_bokkeum     |
|    13    |   beef_tartare      |
|14|cannoli |
|15|foie_gras|
|16|tacos|
|17|pad_thai|
|18|poutine|
|19|ramen|
|20|pulled_pork_sandwich|
|21|bibimbap    |
|22|beignets  |
|23|crab_cakes |
|24|apple_pie   |
|25|risotto     |
|26|galbijjim    |
|27|paella       |
|28|soondubu_jjigae  |
|29|baby_back_ribs   |
|30|miso_soup        |
|31|frozen_yogurt    |
|32|club_sandwich    |
|33|carrot_cake      |
|34|falafel          |
|35|bread_pudding    |
|36|kimchi           |
|37|chicken_wings    |
|38|gnocchi          |
|39|caprese_salad    |
|40|creme_brulee     |
|41|escargots        |
|42|chocolate_cake   |
|43|tiramisu         |
|44|samgyetang       |
|45|garlic_bread     |
|46|scallops         |
|47|baklava          |
|48|edamame          |
|49|macaroni_and_cheese   |
|50|pancakes              |
|51|mussels               |
|52|beet_salad            |
|53|onion_rings           |
|54|red_velvet_cake       |
|55|steak                 |
|56|grilled_salmon        |
|57|daegaejjim            |
|58|tuna_tartare          |
|59|deviled_eggs          |
|60|caesar_salad          |
|61|hummus                |
|62|fish_and_chips        |
|63|lasagna               |
|64|peking_duck           |
|65|guacamole             |
|66|strawberry_shortcake  |
|67|clam_chowder          |
|68|croque_madame         |
|69|french_onion_soup     |
|70|beef_carpaccio        |
|71|fried_rice            |
|72|donuts                |
|73|gyoza                 |
|74|soondae               |
|75|ravioli               |
|76|fried_calamari        |
|77|spaghetti_carbonara   |
|78|omelette              |
|79|french_toast          |
|80|lobster_bisque        |
|81|ceviche               |
|82|bruschetta            |
|83|french_fries          |
|84|nangmyeon             |
|85|shrimp_and_grits      |
|86|gimbob                |
|87|filet_mignon          |
|88|hamburger             |
|89|dumplings             |
|90|chicken_curry         |
|91|sushi                 |
|92|cheese_plate          |
|93|eggs_benedict         |
|94|cup_cakes             |
|95|takoyaki              |
|96|chocolate_mousse      |
|97|bossam                |
|98|breakfast_burrito     |
|99|hot_dog               |
|100|macarons              |
|101|waffles               |
|102|seaweed_salad         |
|103|greek_salad           |
|104|huevos_rancheros      |
|105|doenjang_chigae       |
|106|pizza                 |
|107|chicken_quesadilla    |
|108|hot_and_sour_soup     |
|109|prime_rib             |
|110|cheesecake            |
|111|ice_cream             |
|112|ganjang_gejang        |
|113|jjajangmyeon          |
|114|pajeon                |
|115|grilled_cheese_sandwich |
|116|pho                     |
|117|lobster_roll_sandwich   |
|118|nachos                  |
|119|oysters                 |

### Contributor
| name         | email                     | Organization            |
|--------------|---------------------------|-------------------------|
| Dong-hee Na   | corona10@gmail.com        | Chungnam National Univ. |
| Sanggi Hong  | sanggi.hong11@gmail.com   | Chungnam National Univ. |
| Sanghee Lee  | sanghee.lee1992@gmail.com | Chungnam National Univ. |
