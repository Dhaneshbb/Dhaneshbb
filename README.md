<h1 align="center">Hi 👋, I'm Dhanesh b b</h1>
- 📫 How to reach me **dhaneshbb05@gmail.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://www.linkedin.com/in/dhanesh-b-b-2a8971225/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="dhanesh b b" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> </p>


+---------------------+             +---------------------+             +---------------------+
|       actor_info    |             |     customer_list   |             |         film        |
+---------------------+             +---------------------+             +---------------------+
| actor_id            |             | id                  |             | film_id             |
| first_name          |             | name                |             | title               |
| last_name           |             | address             |             | description         |
| film_info           |             | zip code            |             | release_year        |
|                     |             | phone               |             | language_id         |
|                     |             | city                |             | original_language_id|
|                     |             | country             |             | rental_duration     |
|                     |             | notes               |             | rental_rate         |
|                     |             | sid                 |             | length              |
|                     |             |                     |             | replacement_cost    |
|                     |             |                     |             | rating              |
|                     |             |                     |             | last_update         |
+---------------------+             +---------------------+             | special_features    |
                                                                        | fulltext            |
                                                                        +---------------------+

+---------------------+             +---------------------+             +---------------------+
|        actor        |             |        address      |             |       category      |
+---------------------+             +---------------------+             +---------------------+
| actor_id            |             | address_id          |             | category_id         |
| first_name          |             | address             |             | name                |
| last_name           |             | address2            |             | last_update         |
| last_update         |             | district            |             |                     |
|                     |             | city_id             |             |                     |
|                     |             | postal_code         |             |                     |
|                     |             | phone               |             |                     |
|                     |             | last_update         |             |                     |
+---------------------+             +---------------------+             +---------------------+

+---------------------+             +---------------------+             +---------------------+
|        city         |             |       country       |             |      customer       |
+---------------------+             +---------------------+             +---------------------+
| city_id             |             | country_id          |             | customer_id         |
| city                |             | country             |             | store_id            |
| country_id          |             | last_update         |             | first_name          |
| last_update         |             |                     |             | last_name           |
|                     |             |                     |             | email               |
|                     |             |                     |             | address_id          |
|                     |             |                     |             | activebool          |
|                     |             |                     |             | create_date         |
|                     |             |                     |             | last_update         |
|                     |             |                     |             | active              |
+---------------------+             +---------------------+             +---------------------+

+---------------------+             +---------------------+             +---------------------+
|       film_actor    |             |     film_category   |             |      film_list      |
+---------------------+             +---------------------+             +---------------------+
| actor_id            |             | film_id             |             | fid                 |
| film_id             |             | category_id         |             | title               |
| last_update         |             | last_update         |             | description         |
|                     |             |                     |             | category            |
|                     |             |                     |             | price               |
|                     |             |                     |             | length              |
|                     |             |                     |             | rating              |
|                     |             |                     |             | actors              |
+---------------------+             +---------------------+             +---------------------+

+---------------------+             +---------------------+             +---------------------+
|        language     |             |       inventory     |             |       payment       |
+---------------------+             +---------------------+             +---------------------+
| language_id         |             | inventory_id        |             | payment_id          |
| name                |             | film_id             |             | customer_id         |
| last_update         |             | store_id            |             | staff_id            |
|                     |             | last_update         |             | rental_id           |
|                     |             |                     |             | amount              |
|                     |             |                     |             | payment_date        |
|                     |             |                     |             |                     |
|                     |             |                     |             |                     |
+---------------------+             +---------------------+             +---------------------+

+---------------------+             +---------------------+             +---------------------+
|   payment_p2020_01  |             |       rental        |             |       staff         |
+---------------------+             +---------------------+             +---------------------+
| payment_id          |             | rental_id           |             | staff_id            |
| customer_id         |             | rental_date         |             | first_name          |
| staff_id            |             | inventory_id        |             | last_name           |
| rental_id           |             | customer_id         |             | address_id          |
| amount              |             | return_date         |             | email               |
| payment_date        |             | staff_id            |             | store_id            |
|                     |             | last_update         |             | active              |
|                     |             |                     |             | username            |
|                     |             |                     |             | password            |
|                     |             |                     |             | last_update         |
+---------------------+             +---------------------+             | picture             |
                                                                        +---------------------+

+---------------------+             +---------------------+             +---------------------+
|      store          |             |       staff_list    |             |   film_category     |
+---------------------+             +---------------------+             +---------------------+
| store_id            |             | id                  |             | film_id             |
| manager_staff_id    |             | name                |             | category_id         |
| address_id          |             | address             |             | last_update         |
| last_update         |             | zip code            |             |                     |
|                     |             | phone               |             |                     |
|                     |             | city                |             |                     |
|                     |             | country             |             |                     |
|                     |             | sid                 |             |                     |
|                     |             |                     |             |                     |
+---------------------+             +---------------------+             +---------------------+

+---------------------+             +---------------------+             +---------------------+
|   payment_p2020_02   |             |  payment_p2020_04  |             |   payment_p2020_05  |
+---------------------+             +---------------------+             +---------------------+
| payment_id          |             | payment_id          |             | payment_id          |
| customer_id         |             | customer_id         |             | customer_id         |
| staff_id            |             | staff_id            |             | staff_id            |
| rental_id           |             | rental_id           |             | rental_id           |
| amount              |             | amount              |             | amount              |
| payment_date        |             |                     |             |                     |
+---------------------+             +---------------------+             +---------------------+
