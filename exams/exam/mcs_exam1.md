# Exam Programming for Minor Computational Science

Date: October 24 2023

This is a digital exam. The exam consists of 3 assignment in which you have to write a short python program.

You're only evaluated based on the _correctness_ of your solutions, code design is not important. So, you don't have to worry about comments or the style guide.

You can test your code using checkpy. First download the tests for the exam:

    checkpy -d /spcourse/exam-tests

Run checkpy:

    checkpy mcs_exam1


# Rules

- Create one file for all your solutions called `mcs_exam1.py`. This is the file you'll hand in at the end of your exam.
- You're only allowed to use `pandas` package. You're not allowed any other external Python package.
- You're only allowed to use the websites mcs.mprog.nl and the Pandas documentation from https://pandas.pydata.org/. You're not allowed to use any other website. (So also no Google!)
- You are allowed to look at your own code that you wrote during the course.
- You cannot get any help with programming during the exam.
- Submit your solutions when you're done. **Check with the teacher present if you handed in your assignment correctly before leaving the exam venue.**

### Hints

The following steps should help you find solutions to the exercises:

1. Get an overview of the problem at hand:
  - What is the input? I.e., what external information does the function need?
  - What information is set? You might want to pre-define some values that will never change
  - What is the output? What should the function return?
2. Think of two examples, and predict what the output of the program should be given these examples. Determine how you would come to these answers
3. Propose a procedure in pseudocode, and try to find elements you will need to further work out
4. Implement your program in Python, include code that can be used to test your program
5. Test your program extensively using the examples you thought of in step 2, and see if you can find any edge cases where the program gives an unexpected output.
6. Finish your program and submit your solutions. *Before you leave the exam room, check with the proctor that your submission was correctly submitted!*


# 1. Palindrome Checker

Write a Python function `is_palindrome(word)` that takes a string word as input and returns `True` if the word is a palindrome (reads the same forwards and backwards), and `False` otherwise.

For example, if you call the function like this:

    result1 = is_palindrome("racecar")
    result2 = is_palindrome("hello")
    result3 = is_palindrome("level")
    print(result1)  # Should print True
    print(result2)  # Should print False
    print(result3)  # Should print True

Which should print:

    True
    False
    True

# 2. Population Data

You are given two dictionaries representing the populations of different cities in two different years. Your task is to write a Python function `calculate_growth(population_1, population_2)` that calculates the population growth or decline for each city and returns a new dictionary with this information. If a city is present in one dictionary but not the other, it should not be included in the result.

Here's an example:

    population_1 = {
        'New York': 8500000,
        'Los Angeles': 3900000,
        'Chicago': 2700000,
        'Houston': 2400000,
        'Phoenix': 1700000
    }

    population_2 = {
        'New York': 8700000,
        'Los Angeles': 4000000,
        'Chicago': 2800000,
        'Houston': 2300000,
        'Dallas': 1500000
    }

    print(calculate_growth(population_1, population_2))

Which should print the dictionary:

    {
        'New York': 200000,
        'Los Angeles': 100000,
        'Chicago': 100000,
        'Houston': -100000,
    }

# 3. The classics

[Download the `film.csv` file.](film.csv)

The file `film.csv` contains data of over a 1000 films from before the 2000s. In this exercise, you will use `film.csv` to answer a question about the data. The contents of the file look as follows:

    Year;Length;Title;Subject;Actor;Actress;Director;Popularity;Awards
    1990;111.0;Tie Me Up! Tie Me Down!;Comedy;Banderas, Antonio;Abril, Victoria;Almodvar, Pedro;68.0;No
    1991;113.0;High Heels;Comedy;Bos, Miguel;Abril, Victoria;Almodvar, Pedro;68.0;No
    1983;104.0;Dead Zone, The;Horror;Walken, Christopher;Adams, Brooke;Cronenberg, David;79.0;No
    ...
    1987;103.0;Heat;Mystery;Reynolds, Burt;Young, Karen;Jameson, Jerry;69.0;No
    1947;87.0;Night Is My Future;Drama;Malmsten, Birger;Zetterling, Mai;Bergman, Ingmar;17.0;No
    1990;92.0;Witches, The;Science Fiction;Fisher, Jasen;Zetterling, Mai;Roeg, Nicolas;18.0;No

As you can see, the fields in this file are separated by semicolons (`';'`), **so not a comma**. If you decide to use Pandas for this assignment, have a look at the [`delimiter` argument of `read_csv()` in the Pandas documentation](https://pandas.pydata.org/docs/reference/api/pandas.read_csv.html) The films have no particular order, and for each film the file contains the following information:

1. Year: the year in which the film was released
2. Length: the duration of the film in minutes
3. Title: the title of the film
4. Subject: the genre of the film
5. Actor: the name of the main actor in the movie
6. Actress: the name of the main actress in the movie
7. Director: the name of the director of the movie
8. Popularity: the popularity of the movie on a scale from 0 to 100
9. Awards: whether the movie has gotten an award (Yes/No)

The columns with names always only contain one name.

Write a function `average_popularity_year(filename, year)` that given a `filename` and a `year` (int) can calculate the average popularity of all films that were released in that year. Your function should return the average popularity as a float. If there are no movies released in the given `year`, your function should return `None`, and print an error message.

    filename = 'data/film.csv'
    year = 1984
    avg_popularity = average_popularity_year(filename, year)
    print(f'The average popularity of movies in the year {year} was {avg_popularity:.2f}.')

    year = 1990
    avg_popularity = average_popularity_year(filename, year)
    print(f'The average popularity of movies in the year {year} was {avg_popularity:.2f}.')

    year = 1994
    avg_popularity = average_popularity_year(filename, year)

Should print:

    The average popularity of movies in the year 1984 was 42.47.
    The average popularity of movies in the year 1990 was 39.42.
    There are no movies from the year 1994 in data/film.csv.
