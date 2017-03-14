## Offset keyword

  ```apex
  QB.select_x()
    .from_x('Account')
    .offset(100)
  ```
*Equivalent SOQL Query*

  ```sql
  SELECT Id FROM Account OFFSET 100
  ```