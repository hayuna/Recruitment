# Catch the deal

### Backend
- [ ] Write a simple database (could be only JSON file) which store opportunities data.

### Frontend
#### Stage I
##### Write a component to store opportunity to buy a course 
- [ ] All of props should be retrieved from backend side
- [ ] Add to follow (heart icon) - heart icon should integrate with user events. When its in hover time it should have changed color into red and started some animation like heart beating
- [ ] Catch the deal! 189 PLN - it should be managed by component props like `price`
- [ ] Follow this course - heart icon should have the same animation as previous. If we click the heart, both should be changed into red color.
- [ ] Superheroes and the value in circle should be get from props `any name` but should be proper to purpose
- [ ] Go to course should have some icon on the right side and redirect us to external link

#### Stage II
##### Discount
- [ ] If we have `discount` prop with some value it should be added new section like `Get N discount`
- [ ] Each discount should be proceed with reference code. 
- [ ] To speed up copying discount code, we have a readonly input with code. After clicking input, we want to store this code into clipboard

#### Stage III
##### Discount with limited usage
- [ ] We want to have limited discount code to n usage. It should be stored in props

#### Stage IV
##### Discount with limited time
- [ ] We want to have limited discount code to specific time. It should be stored in props

