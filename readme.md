### naming convention:

all key will be camel cased , string values start with Capital letter

### api schema:

follows mongoose Schema

```
{
mealId: Number,
mealTitle: String,
mealCategory: String,
mealThumb: String,
mealThumbSmall:String,
mealTags: [String],
mealPrice: Number,
mealQuantity: Number,
}

```

### category & id range:

 each category will have id range

- Appetizer => 101-120
- Main dish => 121-140
- Salad => 141-160
- Soup => 161-180
- Vegetables => 181-200
- Vegetarian => 201-220
- Fish => 221-240
- Rice and Noodles => 241-260
- Drinks => 261-280
- Biriyani => 281-300

### image thumb resolution

main => 700x700 px
small => 300x300 px
