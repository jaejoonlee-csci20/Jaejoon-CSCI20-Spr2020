// Programmer's Name :Jaejoon Lee 
// Date : 13 Feb 2020
// Description : Project #1-2 Converting user's age to time, and estimating the calories and potato fries that they have consumed for their lifetime.
// Citations 1 : https://www.calculator.net/calorie-calculator.html (calories need for male and female)
// Citations 2 : https://www.mcdonalds.com/us/en-us/product/large-french-fries.html (Fries Calories information)

package main 

import "fmt" 

func main() {

// define variable age
var age int

// To make space between the outputs for look easy to users
fmt.Println(" ")

// Ask user to enter user's age
fmt.Println("Enter the age to convert it from year to time and date")

// User input their age
fmt.Scanln(&age)

// 1 year = 365 days
// 1 day = 24 hours
// (age x 365 = age to days)
// (age x 365 x 24 = age to time)

// To make space between the outputs for look easy to users
fmt.Println(" ")


// Showing the result of calculation of years to time and date.
fmt.Println("You are", age, "years old.")
fmt.Println(age, "years is equal to", age*365*24, "hours")
fmt.Println(age, "years is equal to", age*365, "days")


// To make space between the outputs for look easy to users
fmt.Println(" ")

// define variable pound
var pound int

// Ask user's weight (pound)
fmt.Println("Enter the weight(pound) to convert it from pound to ounce, kilogram and gram.")

// User input their weight
fmt.Scanln(&pound)

// 1 pound = 16 Ounce
// 1 pound = 0.454 kg
// 1 pound = 454 g

// To make space between the outputs for look easy to users
fmt.Println(" ")

// Show the calculation from their weight(pound) to Ounce, gram and kilogram.
fmt.Println(pound, "pound is equal to ", pound*16,"Ounce")

fmt.Println(pound, "pound is equal to ", pound*454,"g")

fmt.Println(pound, "pound is equal to ", pound*454/1000,"kg")

// To make space between the outputs for look easy to users
fmt.Println(" ")


//define variable gender
var gender int

// Ask user to enter their gender 
fmt.Println("Enter the gender to determine the calories that you have consumed for lifetime")

// To make space between the outputs for look easy to users
fmt.Println(" ")

// Showing how to input their gender by 1 and 2
fmt.Println("If you are male, enter the number 1")
fmt.Println("If you are female, enter the number 2")


// User type their gender by 1 or 2 (1 is male, 2 is female)
fmt.Scanln(&gender)

// To make space between the outputs for look easy to users
fmt.Println(" ")


// If user is male, calculate their age*365*2500 calories, so show amount of calories that user have taken in user's lifetime

// If user is female, calculate their age*365*2000 calories, so show amount of calories that user have taken in user's lifetime

// the average man needs 2,500 calories to maintain, and female needs 2,500 calories.

if gender == 1 {
fmt.Println("As you are male, the average man needs 2,500 calories to maintain, so " , age*365 ,"days x 2,500calories =", age*365*2500, "calories you have consumed in your lifetime." )
} else {
fmt.Println("As you are female, the average man needs 2,000 calories to maintain, so " , age*365 ,"days x 2,000calories =", age*365*2000, "calories you have consumed in your lifetime.")
}

// To make space between the outputs for look easy to users
fmt.Println(" ")

// Show the output of calculation (user age x 365days x 3 meals x 2500calories / 490calories) if they are male, so user can see how many fries could have eaten in his their lifetime 

// Show the output of calculation (user age x 365days x 3 meals x 2000calories / 490calories) if they are female, so user can see how many fries could have eaten in his their lifetime 

if gender == 1 {
fmt.Println("If your favorite food was potato fries(490 calories per a meal) in Mc Donald, and you have eaten only fries in your lifetime as breakfast, lunch and dinner per day, the amount of fries you could have eaten in your lifetime is ", age ,"x 365days x 3 meals x 2500calories / 490calories = ",(age*365*3*2500)/490, "fries in your lifetime" )
} else {
fmt.Println("If your favorite food was potato fries(490 calories per a meal) in Mc Donald, and you have eaten only fries in your lifetime as breakfast, lunch and dinner per day, the amount of fries you could have eaten in your lifetime is ", age ,"x 365days x 3 meals x 2000calories / 490calories = ",(age*365*3*2000)/490, "fries in your lifetime")
}

// To make space between the outputs for look easy to users
fmt.Println(" ")

//Letting user know the program is ended
fmt.Println("END")
}
