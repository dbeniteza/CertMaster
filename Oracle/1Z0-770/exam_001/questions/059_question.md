# Examine this code used in Quick SQL. Quick SQL is using default settings. Which table creation script or other output is produced?

```
students name roll no num
```

1. [ ] An Invalid column definition error message will be displayed
1. [ ] create table students(id number generated by default on null as identity constraint students id pk primary key, name varchar2 (255 char) not null, roll no number);
1. [x] create table students(id number generated by default on null as identity constraint students id pk primary key, name varchar2 (255 char), roll no number);