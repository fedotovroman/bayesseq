Отчет по тестированию
==============================
Отчет к покрытию лежит в папке htmlcov, index.html
https://htmlpreview.github.io/?https://github.com/fedotovroman/aaa_python/blob/main/5%20tests%20in%20python/5_issue/htmlcov/index.html
1. Откройте консоль (cmd).
2. Перейдите в директорию проекта (cd directory) и выполните: python what_is_year_now_test.py -v
3. В случае прохождения всех тестов будет выведено: 
```
================================================= test session starts =================================================
test_first_type_data (__main__.Test_what_is_year_now)
checks the correctness of execution in the case of the format ymd ... ok
test_second_type_data (__main__.Test_what_is_year_now)
checks the correctness of execution in the case of the format dmy ... ok
test_value_error (__main__.Test_what_is_year_now) ... ok

----------------------------------------------------------------------
Ran 3 tests in 0.001s

OK
```
