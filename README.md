### TDD_2
In this project we're working in TDD & CICD approaches.
our features in the project are :   


1.give us the champion team for each leagues (premier league,La liga,primeria liga,Eredivisie,champion league,bundesliga,ligue1).

2.give us the best scorer for each league and sort it by amount of goals.


### Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
* Python interperter
* pip
* IDE - Development envenvironment (like PyCharm)

### How to install

#### Section A
* Clone this repo to your computer : https://github.com/amitamir/TDD_2/tree/master

#### Section B
* Open command line .

#### Section C
* Enter the following sentences in the CL:

```
1.  pip install re 
2.  pip install mock
3.  pip install pycodestyle
```

#### Section D
* Open the project in your IDE


## API's used 
The application uses [Soccer Data](https://www.football-data.org)- API in order to get the facts.

The project is synchronized with:
* SemaphoreCi - An API used to implement CI/CD (Continuous Integration & Continuous Deployment)
* Heroku - A virtual production environment

## Running the tests 
In order to run the test, use command line to enter the following command: (open command line in project's directory)
 ```
 python TestDrivenDevelopment.py
 ```
If all tests passed, you should see this output:
![Image of Yaktocat](https://github.com/amitamir/TDD_2/blob/master/images/pass%20test.jpeg)
  
  
## Using the application
Run the program with the command (you can on CL inside the directed file)
```
python Feature_Sport_Data.py
```
and the following output will be :

https://github.com/amitamir/TDD_2/blob/master/outputs.txt
