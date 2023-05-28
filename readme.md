### naming convention:

all key will be camel cased , string values starts with small letter

#### api schema:
follows mongoose Schema

```
{
mealId: Number,
mealTitle: String,
mealCatecory: String,
mealThumb: String,
mealThumbSmall:String,
mealTags: [String],
mealPrice: Number,
mealQuantity: Number,
}

```

#### category & id range:

each category will have id range

appetizer => 101-120
main dish => 121-140
salad => 141-160
soup => 161-180
vegetables => 181-200
vegeterian => 201-220
fish => 221-240
rice and noodles => 241-260
drinks => 261-280

#### image thumb resolution

main => 700x700 px
small => 300x300 px
