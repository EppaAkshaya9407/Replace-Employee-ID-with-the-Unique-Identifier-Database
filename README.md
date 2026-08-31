# Replace-Employee-ID-with-the-Unique-Identifier-Database
select u.unique_id,e.name from Employees e left join EmployeeUNI u on e.id=u.id;
