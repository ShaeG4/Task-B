��#   T a s k - B 
Through working task b I had run into a lot of issues, with the restock in particular as well as the sales file which I had managed to work through with time. 
Another issue I had worked through was with the invetory_report_Tshirts, because the restock was not refreshing at every 7 days which I had only realised,
a lot later than when I started it was duplicating itself and not restocking weekly
 
"""
#Example logic for sales and restocking
    sales_today = random.randiint(0,available_items)
    restocked_items_today = random.randint(0, available_items)

    # Update available items
    available_items = available_items-sales_today+restocked_items_today

    # Append the new record to the inventory records
    inventory_records.append((current_day, sales_today, restocked_items_today, available_items))

    return available_items

 """

 I had fixed this but there was an error for my code becuase I was not aware of the "randiint" input instead of it being "randint"
