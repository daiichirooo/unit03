# Quiz43

## Code
```.py
DROP TABLE if exists movies;
CREATE TABLE if not exists movies(
    id INTEGER PRIMARY KEY ,
    name TEXT,
    year INTEGER NOT NULL,
    producer NOT NULL,
    director NOT NULL,
    budget INTEGER NOT NULL,
    category NOT NULL
);

INSERT into movies (name, year, director, producer, budget, category) VALUES ('Start Wars 4', 1977, 'George Lucas', 'Gary Kurtz', 11000000, 'fantasy');
INSERT into movies (name, year, director, producer, budget, category) VALUES ('Top Gun: Maverick', 2022, 'Joseph Kosinski', 'Christopher McQuarrie', 170000000, 'Action');
```

## Proof

![](43.png)
