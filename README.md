## freecodecamp_celestial_bodies_database
#Celestial Bodies Relational Database Project

Welcome to the Celestial Bodies Relational Database project! This project is part of FreeCodeCamp's curriculum and focuses on creating a comprehensive database for various celestial bodies such as planets, stars, moons, and galaxies. Our goal is to design a well-structured and normalized database that captures essential characteristics of these celestial entities.

Key Features:

Structured database schema for planets, stars, moons, and galaxies.
Utilizes PostgreSQL for relational database management.
Includes foreign keys for establishing relationships between tables.
Represents various attributes of celestial bodies, such as size, temperature, atmosphere, and more.
Ideal for learning database design, SQL queries, and relational concepts.
Feel free to explore our repository to see the database schema, sample data, and documentation. Whether you're a beginner looking to understand databases or an enthusiast interested in celestial bodies, this project offers a hands-on learning experience in database design and management.

Get involved, contribute, and learn more about the fascinating world of celestial bodies through data and code. Let's explore the cosmos together!
/////////////////////////
This is the description of FreeCodeCamp.org chanllenge

  You should create a database named universe
  Be sure to connect to your database with \c universe. Then, you should add tables named galaxy, star, planet, and moon
  Each table should have a primary key
  Each primary key should automatically increment
  Each table should have a name column
  You should use the INT data type for at least two columns that are not a primary or foreign key
  You should use the NUMERIC data type at least once
  You should use the TEXT data type at least once
  You should use the BOOLEAN data type on at least two columns
  Each "star" should have a foreign key that references one of the rows in galaxy
  Each "planet" should have a foreign key that references one of the rows in star
  Each "moon" should have a foreign key that references one of the rows in planet
  Your database should have at least five tables
  Each table should have at least three rows
  The galaxy and star tables should each have at least six rows
  The planet table should have at least 12 rows
  The moon table should have at least 20 rows
  Each table should have at least three columns
  The galaxy, star, planet, and moon tables should each have at least five columns
  At least two columns per table should not accept NULL values
  At least one column from each table should be required to be UNIQUE
  All columns named name should be of type VARCHAR
  Each primary key column should follow the naming convention table_name_id. For example, the moon
  Tables created for this challenge

And the table Design as follows with the columns created for each one, you can review the data type of each one in the schema image added in this repository:
--------------+---------------+--------------------+-----------------------+
|   galaxy     |  galaxy_type  |       star         |      star_type        |
+--------------+---------------+--------------------+-----------------------+
| galaxy_id    | galaxy_type_id| star_id            | star_type_id          |
| name         | name          | name               | name                  |
| description  | description   | description        | description           |
| distance_mp  |               | supernova_potential| size                  |
| solar_masses |               | binary_star        | spectral_type         |
| num_exoplanets|              | surface_temp_K     | size_classification  |
| galactic_coll|               | solar_luminosity   |                       |
| galactic_halo|               | radius             |                       |
| galaxy_type_id|              | stellar_age        |                       |
+--------------+---------------+--------------------+-----------------------+

+--------------+---------------+--------------------+-----------------------+
|   planet     |      moon     |                    |                       |
+--------------+---------------+--------------------+-----------------------+
| planet_id    | moon_id       |                    |                       |
| name         | name          |                    |                       |
| description  | description   |                    |                       |
| has_life     | has_life      |                    |                       |
| ring_system  | volcanic_act  |                    |                       |
| num_moons    | radius        |                    |                       |
| orbital_period| orbital_per   |                    |                       |
| atm_pressure | atm_pressure  |                    |                       |
| surface_gravity| surface_grav |                    |                       |
| star_id      | planet_id     |                    |                       |
+--------------+---------------+--------------------+-----------------------+



