**Gold Medal Metrics**


   **Project Overview**

Gold Medal Metrics is an Olympic metrics reporting web application built using Spring Data JPA. This application allows users to:

  - View countries in a list with their population, GDP, and number of Olympic gold medals.
  
  - Sort the list of countries by any of these attributes, as well as alphabetically by name.
  
 - View a detailed description of a country, with statistics on their Olympic wins.
  
 - View a list of every Olympic win a country has, including the year, season, winner name, city, and event.
  
 - Sort the list of Olympic wins by any of these attributes.
  

**Features**

  - Country List View
      Displays a list of countries with their population, GDP, and number of Olympic gold medals.
      Allows sorting the list by population, GDP, number of gold medals, and alphabetically by country name.

 - Country Detail View
      Provides a detailed description of a country.
      Includes statistics on the country's Olympic wins.

 - Olympic Wins List View
      Shows a list of every Olympic win for a selected country.
      Includes details such as the year, season, winner name, city, and event.
      Allows sorting the list by year, season, winner name, city, and event.


To get a local copy up and running, follow these simple steps:

**Prerequisites**

 - Java Development Kit (JDK)
 - Spring Boot
 - Maven or Gradle

**Installation**

1. Clone the repository:
    
        git clone https://github.com/AKaraeva/goldMedalMetrics.git

2. Navigate to the project directory:



        cd goldMedalMetrics

3. Install dependencies and build the project:



        ./mvnw clean install

4. Run the application:


        ./mvnw spring-boot:run
