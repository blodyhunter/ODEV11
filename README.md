# ODEV11

1- (select first_name from actor)
UNION
(select first_name from customer);

2- (select first_name from actor)
Intersect
(select first_name from customer);

3- (select first_name from actor)
Except
(select first_name from customer);
